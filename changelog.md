# 0.4.1

* Raise upper bound dependency on `attoparsec`.


# 0.4

* Remove `Pipes.Aeson.encode` in favour of `encodeObject` and
  `encodeArray`.

* `decode` and `decodeL` now return `Nothing` on end of input, instead
  of failing with a `DecodingError`. This follows the approach taken
  by `pipes-attoparsec-0.5`.

* Solved quadratic time complexity issue when decoding (#10).

* Depend on `pipes-attoparsec-0.5.*`.

* Raise upper bound for `transformers` to `0.4.*`.


# 0.3.0

* API revamped to be compatible with `pipes-parse-3.0.*`.

* Renamed `Pipes.Aeson.Unsafe` module to `Pipes.Aeson.Unchecked`.


# 0.2.1

* Generalize `encode` from `Producer` to `Producer'`.

* Depend on newer versions of `aeson`, `attoparsec`, `pipes-attoparsec`.


# 0.2.0

* Version compatible with `pipes-4.0.0` and `pipes-parse-2.0.0`.

* API radically changed. Removed `parseValue`, `fromValue` and
  `TopLevelValue`. Other things renamed.


# 0.1.0.0

* First version.