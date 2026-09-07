# fleur README

This is the README for your extension "fleur". After writing up a brief description, we recommend including the following sections.

## About fleur

Fleur is a minimalistic programming language designed for simplicity and educational purposes while remaining useful for real-world scripting.
It features a full compiler pipeline, including a lexer, parser, and tree-walking interpreter, along with a growing standard library.

## Features

.Educational & Practical: Designed to be easy to learn and understand, yet powerful enough for useful scripts.
.Control Flow: if/else, when (pattern matching), for, and while loops
.Functions & Procedures: Differentiate between pure functions (func) and side-effecting procedures (proc).
.Data Structures: Support for structs, arrays, and maps.
.Error Handling: Built-in try/catch mechanisms.
.Module System: Organize code with import and pub keywords.
.REPL: Interactive shell for quick prototyping.
.Standard Library: Built-in modules for IO, Time, Types, and more.

## Getting started

Installation
Building from source
To build Fleur from source, you need to have Bun installed on your system.

Clone the repository:

git clone https://github.com/WooperLUA/fleur-lang
cd fleur-lang
Install dependencies:

bun install
Build Fleur for your platform: Check package.json for available build scripts (e.g., build-windows-x64, build-linux-x64, build-darwin-arm64).

bun run build-<your_platform>
Access the runtime: The compiled binary will be located in the ./out directory. You can optionally add this directory to your PATH to use the fleur command globally.

Getting the runtime from Releases
Alternatively, you can download the pre-built runtime binaries from the Releases page.


## Usage
 If you have added the Fleur binary to your PATH, you can use the fleur command directly.

Running a Script
To execute a .flr file:

fleur run path/to/your/script.flr
Interactive REPL
Start the interactive shell:

fleur repl
Help
Display available commands:

fleur help
Example Code
Here is the proof fleur is a real language :

io::print("Hello, Fleur (and also the world)");
Check the exemple/ directory for more comprehensive examples of the language features and standard library usage.

## Documentation

Check the [Documentation] (https://github.com/INEEDTOHAVETHELINK)

## License

This project is licensed under the [LICENSE] (https://github.com/WooperLUA/fleur-lang/blob/master/LICENSE) file included in the repository.

**Enjoy!**
