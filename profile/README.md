RapidFuzz provides libraries for fuzzy string matching in various programming languages.

## Python

For Python there are the following libraries:

- [RapidFuzz](https://github.com/rapidfuzz/RapidFuzz) provides various string metrics with a focus on making
  them as fast as possible.
- [Levenshtein](https://github.com/rapidfuzz/Levenshtein) provides a couple string metrics and median implementations.
  For string metrics generally rapidfuzz should be te preferred choice. Opposed to all other libraries this library is
  currently GPLv2 licensed.
- [python-Levenshtein](https://github.com/rapidfuzz/python-Levenshtein) this is an alias to the Levenshtein library that
  only exists for backwards compatibility reasons.
- [JaroWinkler](https://github.com/rapidfuzz/JaroWinkler) provides a fast implementation of Jaro and JaroWinkler similarity.
  This was placed in RapidFuzz at some point and so this largely exists for applications already using it.
- [CyDifflib](https://github.com/rapidfuzz/CyDifflib) drop in replacement for difflib in the Python standard library
  which is faster.

## C++

For C++ there are the following libraries:

- [rapidfuzz-cpp](https://github.com/rapidfuzz/rapidfuzz-cpp) provides various string metrics with a focus on making
  them as fast as possible. This should be used when the performance of the algorithms is more important than
  a slightly larger binary.

Similar to rust there will be an implementation focussing on binary size in the future.

## Rust

For rust there are the following libraries:

- [rapidfuzz-rs](https://github.com/rapidfuzz/rapidfuzz-rs) provides various string metrics with a focus on making
  them as fast as possible. This should be used when the performance of the algorithms is more important than
  a slightly larger binary.
- [strsim-rs](https://github.com/rapidfuzz/strsim-rs) provides a lot of string metrics of rapidfuzz, but has a focus on
  keeping the binary size as small as possible. This should be used when performance of the algorithms doesn't really
  matter too much, since the application only compares a small set of strings. An example for this would be suggestions in
  a CLI.
