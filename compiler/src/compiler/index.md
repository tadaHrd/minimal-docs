# Compiler

The compiler contains several parts, each documented in its own subchapter.

## The difference between the lexer and the tokenizer

The tokenizer turns text into basic tokens that include whitespaces.

The lexer connects the tokens from the tokenizer to form bigger tokens (e.g. `+` & `=` connect to `+=`), these don't include whitespaces.