# Rust Mutable vs. Immutable References

This repository demonstrates a common error in Rust related to mutable and immutable references.  In Rust, you can create both mutable (`&mut`) and immutable (`&`) references to a value. However, the compiler enforces strict rules to prevent data races by only allowing one mutable reference to a value at a time. Attempting to create multiple mutable references, or a mutable and immutable reference simultaneously to the same value results in a compile-time error. The example code shows how to correctly use mutable and immutable references to avoid this error.

## Running the code

Simply clone the repo and run `cargo run` in the terminal.
The `bug.rs` file demonstrates the error and how to fix it in `bugSolution.rs`.