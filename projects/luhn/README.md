# Luhn algorithm
[The Luhn algorithm](https://en.wikipedia.org/wiki/Luhn_algorithm) is a simple checksum formula used to validate an identification number. It's used everywhere, from credit cards to IMEI numbers.

The standard Luhn algorithm works with base-10 numbers. Your job is to implement Luhn for an identification code which comprises letters from [the ISO basic Latin alphabet](https://en.wikipedia.org/wiki/ISO_basic_Latin_alphabet) and [Arabic numerals](https://en.wikipedia.org/wiki/Arabic_numerals). In other words, a base-62 version of Luhn.

At a bare minimum, your solution should:

1. Implement a `validate` function, which accepts an identification code, and returns a boolean.
2. Implement a `generate` function, which accepts the first `x - 1` characters of an `x` digit identification code, and calculates the final character.