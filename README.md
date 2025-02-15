![rust crab](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjL9Iizzd_PXCuJg4CitszBfqBaxzW0uNvCUSArO39sbXpWb7-bVY4oJgebm3toJ3j-RL6cG7txIEImFBxaYGYqr7fesUIZl8nkAmkLestTx2-Dy6S0cP_0JTR50AbDMCeb1GZ_bwll7k0/w200-h131/rust.png)
# How To Learn Rust

> This guide will follow **No Boilerplate**'s example on how to learn Rust [video](https://www.youtube.com/watch?v=2hXNd6x9sZs)
>
> This guide lists "3 pillars of recommended syllabus" and will be shown in order below.
>
> These three are very tightly bound together.

### Read the *Rust Programming Language Book*

- Based on Scott H. Young's book, called *Ultralearning*, chapter 8 of this book mentions a learning style called "Test To Learn"
- The purpose of this learning style is to be exposed to facts/information you would have liked to known, before you started the test.
- Then, when you are studying later on -- you more readily absorb the information because you are **already** looking for it.

- Reading this book will follow this style, and will require reading it's entirety twice.

1. Read the book from cover-to-cover, without stopping to do the excersies, as fast as possible.
    - If you come across something you don't understand -- mentally note it & move to the next chapter. 

2. When you have finished, go back to the start and work at your normal pace. This time, read the Brown University version with interactive quizzes
    - [Brown's book](https://rust-book.cs.brown.edu)

### Install Rustlings

- The Rust Programming Book and Rustlings are written in almost the same order. This is by design, and they are made to be consumed together. Rustlings should be started after you have read the book twice

- Run the following command to install

```bash

curl -L https://raw.githubusercontent.com/rust-lang/rustlings/main/install.sh | bash

```

- Rustlings is a code Katas-style system. You can think of this as a suite of failing unit tests that you fix in a test-driven development way.
- Each exercise is a *Katas* -- a type of Japanese martial arts where you paractice something over, and over again -- building muscle memory.
- There are 95 Rustling Katas. When you've done them all, choose your favourite to redo regularly. Recommended weekly.

### Rust by Example

- This is less linerally linked to the book, so it should be used as a supplement.

- Includes high-level tips to idomatic error handling, how to organize code into modules, and testing strategies.
- These are **all** covered in the book, but Rust by Example is more opinionated on **how** to use them.

### Learning Haskell

- At the time of writing this, I'm not sure what it really is -- but is recommended by No Boilerplate, so I'll add in the books he suggests reading.

- "Learn you a Haskell for Great Good! A Beginner's Guide - Miran Lipovaca"
- "Real World Haskell - Bryan O'Sullivan"
