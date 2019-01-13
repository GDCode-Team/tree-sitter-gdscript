tree-sitter-gdscript
==================

GDScript grammar for [tree-sitter][].

NOTE: Not ready for use. @see Todo.

### Todo

- [ ] Expression
  - [ ] call base class function
- [ ] Format Specifiers
- [X] Statements
  - [X] setget
  - [X] export
  - [X] const
  - [X] signal
- [X] Literals
  - [X] @"NodePath/StringName"
  - [X] $node and $"../node"
- [X] Operators
  - [X] is
  - [X] as
- [X] Keyword Statements
  - [X] breakpoint
- [X] Variable Attributes
  - [X] onready
  - These can come after 'export' or before 'var'
    - [X] remote[sync]
    - [X] master[sync]
    - [X] puppet[sync]
- [X] Function Attributes
  - [X] static
  - [X] remote[sync]
  - [X] master[sync]
  - [X] puppet[sync]
- [X] Compound Statements
  - [X] match
  - [X] enum
  - [X] inheriting class constructor

[tree-sitter]: https://github.com/tree-sitter/tree-sitter
