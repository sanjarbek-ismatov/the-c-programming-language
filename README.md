# The C programming language

An online book version of "The C Programming Language, 2nd Edition" (K&R).

## Purpose

This project provides a web-based, interactive version of the classic "The C Programming Language" book. It is intended for learners and enthusiasts who want to read, navigate, and reference the book online. I found the original book hard to read with white background and black text. So I decided to make a change inspired by online version of "The Rust programming language". I will slowly make the book mature over time. Feel free to contribute if you find mistakes or want to add something. I will keep the original spirit of the book with no additional stuff.

## Building and Running

This project uses [mdBook](https://github.com/rust-lang/mdBook) to build and serve the book.

### Prerequisites

- [mdBook](https://github.com/rust-lang/mdBook) installed (`cargo install mdbook`)

### Build the Book

```sh
mdbook build
```

The generated static site will be in the `book/` directory.

### Serve Locally

```sh
mdbook serve
```

Then open [http://localhost:3000](http://localhost:3000) in your browser to view the book.

