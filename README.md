lush
====

The lush command shell is a non-POSIX interactive command language interpreter with an expressive scripting language.  It is a modern, discoverable environment intended for every-day command invocation, process management, and filesystem manipulation.

status
======

lush is in the early stages of initial development.  It has the framework for a shell, a lexer, and a parser; it is still missing an "evaluator" (type-checking, AST execution, program invocation).  Many core features have yet to be implemented.  All language attributes are suitable for discussion and replacement.

todo
====

1. More tests for Parser framework
1. Tests for LushParser -- specifically, blocks, commands, and statement terminators (by newline, semicolon, or end of block)
1. Whitespace tokens -- add to lexer and parser
1. Evaluator: run basic commands