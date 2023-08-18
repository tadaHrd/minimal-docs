# Recommended development environment

The recommended code editor is Visual Studio Code with some extensions (listed below).

## Recommended VSCode extensions

### [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

A neccesity.

Rust language support for Visual Studio Code.

Also set the `Rust-analyzer > Check: Command` setting to `clippy`, if you don't have Clippy run `rustup component add clippy`.

### [GitHub Markdown Preview](https://marketplace.visualstudio.com/items?itemName=bierner.github-markdown-preview)

Very useful when documenting with Markdown.

Changes VS Code's built-in markdown preview to match GitHub.

### [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)

Useful for finding todo comments, almost a necessity to have.

Also set the `Todo Tree > Regex: Regex` (just search for regex) setting to
`(//|#|<!--|;|/\*|^|^[ \t]*(-|\d+.))\s*($TAGS)|todo(\s)*!(\s)*[\(|\[\{](\"[^\"]*\")?[\)|\]|}]`.

### [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb)

A necessity for debugging.

A native debugger powered by LLDB. Debug C++, Rust and other compiled languages.

### [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)

Useful when you don't want to use the mouse or the problems tab all the time.

Improve highlighting of errors, warnings and other language diagnostics.

This extension just makes errors more visible.