# Tree-sitter parser for LC-2200 assembly

This is a [Tree-sitter](https://tree-sitter.github.io/tree-sitter/) parser for LC-2200 assembly, used in Georgia Tech's CS 2200 course.

At this time, it can parse all the syntax, but does not include necessary files for [syntax highlighting support](https://tree-sitter.github.io/tree-sitter/syntax-highlighting).

## Building locally

Install `tree-sitter-cli` with `cargo install tree-sitter-cli`, `npm install tree-sitter-cli`, or [from here](https://github.com/tree-sitter/tree-sitter/releases). Then clone this repo.

You can test with `npm test` or `tree-sitter generate && tree-sitter test`.
