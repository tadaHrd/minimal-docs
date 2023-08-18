# Tokenizer

Located in `src/tokenizer/`.

The purpose of the tokenizer is to turn text into tokens (tokenize it).

Its core is the `Tokenizer` struct from `src/tokenizer/mod.rs`.

`InputTextIter` is an iterator that iterates over a `&[char]`. It works like `Peekable`, but you can peek to the future, the past, or the present as far as you want.

It uses the `Tokenize` trait from `src/tokenizer/tokenize.rs`. It has a function called `tokenize`, which has 2 arguments: the whole text as a `&[char]` and the text iterator `InputTextIter`. These arguments are provided from the tokenizer, from the same text source.


## Tokens

Located in `src/tokenizer/token/`. It has the `Token` struct, which has 3 values:

1. `lexeme`: The whole token as a `&[char]`, sliced from the text input.
2. `value`: The value of the token as a `TokenValue`.
3. `span`: The span of the token (inclusive).

<!-- TODO: add the URL to the compiler rustdoc output tokenizer::token module -->
To get more information about this, look at the [compiler Rustdoc docs](TODO).
