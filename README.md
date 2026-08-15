# ARL

**Another Repository List** collects language-specific lists of popular GitHub repositories for learning and discovery.

## Project status

This repository is a fork of [kaxap/arl](https://github.com/kaxap/arl). The generated lists are snapshots and may be out of date; verify activity and maintenance on linked repositories before relying on them.

## Repository lists

### Widely used languages

- [Python](README-Python.md) · [JavaScript](README-JavaScript.md) · [TypeScript](README-TypeScript.md)
- [Java](README-Java.md) · [C](README-C.md) · [C++](README-CPP.md) · [CSharp](README-CSharp.md)
- [Go](README-Go.md) · [Rust](README-Rust.md) · [PHP](README-PHP.md) · [Ruby](README-Ruby.md)
- [Swift](README-Swift.md) · [Kotlin](README-Kotlin.md) · [Node.js](README-Node.md)

### Data, functional, and systems languages

- [SQL](README-SQL.md) · [R](README-R.md) · [MATLAB](README-MATLAB.md) · [Perl](README-Perl.md)
- [Lua](README-Lua.md) · [Clojure](README-Clojure.md) · [Elixir](README-Elixir.md) · [Erlang](README-Erlang.md)
- [Elm](README-Elm.md) · [Haskell](README-Haskell.md) · [Idris](README-Idris.md) · [PureScript](README-PureScript.md)
- [Crystal](README-Crystal.md) · [D](README-D.md) · [V](README-V.md) · [Scala](README-Scala.md)
- [Groovy](README-Groovy.md) · [Assembly](README-Assembly.md) · [Objective-C](README-ObjectiveC.md)
- [VB.NET](README-VB.net.md) · [Verilog](README-Verilog.md) · [VHDL](README-VHDL.md)

## Regenerating lists

The [make.py](make.py) script queries the GitHub API and rewrites language files. Create a local token.json (ignored by Git), install requests and humanize, then run:

    python make.py
    python make.py --langs Python,JavaScript,Go

Regeneration makes many API requests and is subject to rate limits.

## Maintenance notes

- README-JS.md is retained as a compatibility redirect.
- Generated lists remain at the repository root to preserve existing links.
- This cleanup changes navigation and documentation only; it does not alter generation behavior or list data.

## Attribution

Original project: [kaxap/arl](https://github.com/kaxap/arl). No license file is currently present in this fork; review upstream terms before redistribution.
