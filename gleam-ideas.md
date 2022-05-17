# Gleam Lib Ideas

This is a document of ideas for the Gleam language that where to awkward or rejected for other reasons.

These ideas may be great or utterly bad.

* Extended number types
  * Enforce size limits (if result is equal to maximum size, Result is Error)
  * Allow / Disallow 0
  * Enforce sign (always negative, always positive)
  * Only functions to do math operations
  * Conversion to basic Gleam types: from_float/from_int and to_float/to_int (all return Results)
* List builder which can always be used for optimal performance and abstracts away list prepend/reverse
* Add reduce alias (to fold?)
* Wrap <https://github.com/flmnt/graphemer/>
* assert_ok crashy stuff: <https://johndoneth.github.io/gleam-playground/?s=JYWwDg9gTgLgBAcwDYFMCGID0wIChSSyKoaYBmSEaM%2B408y6WwAdjQfcU5gK5TC1CDEligoAzjyQ1cmTHAAqAC2Di4ZFnBQAPVTDWs4YgMYo2XDAH1xMACZJgAIzgA3FFHE5NaA2wB04gCOPGhillAQEDQacKww1sGhKOGRMAAU2gBccACSbACUcAC0AHxwAEoSUukAYpTUADRwAHLASIUA3rhwcNrdcAA%2BZXF%2BMBCWFFQ0PUPq9TABiWERUbgAvri4MUo%2BlsC2ZjDAxmhIe2wZ2XVThaVwAEKRSHBdPdpwALwfc1N%2Bpm2sBAZfLrTYxMbndJZODXai3MqVSTSNJ5GBNVrtF79E7iFBwHbiPYHNjHU6Q4FYno9BRQHh4u4AeQA1mlJtQ%2FBEeCxbMCQVSYadccUygBRKARKBpDF8uAbDZbbziXGwSwQFliJEwbKI6ppNDotr5eFwNCUk1K9zwZlpFynOmFb4a6r9W1IOmg3BgHjOGIgNCsNKdfoAFn6sziCRCy1SYbKPmV8TVsbgELiyfjltVTOTOD8B0cPAQmx6GNBQA>
