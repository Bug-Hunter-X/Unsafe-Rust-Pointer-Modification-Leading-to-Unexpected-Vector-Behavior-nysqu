# Unsafe Rust Pointer Modification Example

This repository demonstrates a potential issue with using raw pointers to modify vectors in Rust.  Modifying a vector's elements through a raw pointer outside the bounds of the vector's memory or in ways that disrupt its internal structure can lead to unexpected behavior, including panics and incorrect results. This example illustrates this risk and how to avoid it.

**bug.rs**: Contains the buggy code.
**bugSolution.rs**: Shows how to fix the problem by using safe Rust methods.

This example highlights the importance of using safe memory management practices in Rust to prevent such issues.