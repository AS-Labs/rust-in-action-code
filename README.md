# Rust in action code and notes

## Chapter 1 notes

### Cargo

Basically a build tool and an package manager in one.

Builds the program into an executable binary and downloads dependencies.

Cargo.toml file is for the projects metadata

src dir is where the code files are at

When using ```Cargo run``` it compiles and runs the code in debug mode

Cargo.lock file specifies the version of all the dependencies

### Rust Macros

```println!``` a macro for printing to stdout

```eprintln!``` a macro for printing to stderr

### Rust Types

Rust Strings are always UTF-8

Vec<_> is shorthand for vector which is a collection type that can expand dynamically, the _ is to infer the type of the elements


