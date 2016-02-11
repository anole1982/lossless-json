# History

## not yet released, version 0.1.0

- Implemented replacer for stringify and reviver for parse.
- Only parses `LosslessNumber` when a value cannot be represented in a regular
  number.
- Throw error in case of underflow.
- Performance improvements.


## 2016-02-08, version 0.0.2

- The `LosslessNumber` class now throws errors when you would lose information
  when converting from and to a `LosslessNumber`.
- Handle escape characters when stringifying a string.
- Exposed `LosslessNumber` in public API.


## 2016-02-08, version 0.0.1

- First functional version which can parse and stringify.