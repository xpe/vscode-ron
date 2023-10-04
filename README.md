# RON (Rusty Object Notation) for VS Code

This VS Code extension provides support for [RON (Rusty Object Notation)][1].

[1]: https://github.com/ron-rs/ron

## About RON

> RON is a simple readable data serialization format that looks similar to Rust
> syntax. It's designed to support all of Serde's data model, so structs, enums,
> tuples, arrays, generic maps, and primitive values.
>
> — <https://github.com/ron-rs/ron#readme>

## Provenance

- This extension provides a [TextMate 2 grammar][TM2G] called `ron.tmLanguage.json`.
- ... which is based upon [VS Code's built-in Rust grammar][vscode-rust].
- ... which is based on [Dusty Pomerleau's rust-syntax][rust-syntax].

[rust-syntax]: https://github.com/dustypomerleau/rust-syntax

## TextMate Grammar History

- [TextMate 2 grammars][TM2G] use the `.tmLanguage.json` format.
- [TextMate 1 grammars][TM1G] use the `.tmGrammar.json` format.

[vscode-rust]: https://github.com/microsoft/vscode/blob/main/extensions/rust/syntaxes/rust.tmLanguage.json

[TM2G]: https://macromates.com/textmate/manual/

[TM1G]: https://macromates.com/manual/en/language_grammars

## Extension Development

Press `F5` to open a new window with this extension loaded.
