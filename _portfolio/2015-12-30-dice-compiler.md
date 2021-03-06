---
title: "Dice Programming Language"
excerpt: "A Java-like language that compiles to LLVM bytecode using an OCaml backend. Supports objects and inheritance."
collection: portfolio
---

# Dice [![Build Status](https://travis-ci.org/DavidWatkins/Dice.svg?branch=master)](https://travis-ci.org/DavidWatkins/Dice)
Java, but worse

## Requirements
- The test environment is Ubuntu 16.04 running within Virtualbox
- The following ubuntu packages were installed:
  m4 clang-3.8 llvm opam ocaml
- The following opam packages were installed:
  core batteries llvm yojson


## How to run the compiler
- Make sure you are running Ubuntu 16.04 or equivalent
- clone the repo:
```bash
$ git clone https://github.com/DavidWatkins/Dice.git
```
- Then install the required packages
```bash
$ sudo apt-get install ocaml ocaml-native-compilers camlp4-extra opam m4 clang-3.8 llvm
```
- Then initialize opam in your home directory
```bash
$ opam init
$ eval $(opam config env)
$ opam install core batteries llvm.3.8 yojson ocamlfind
```
- Then go into the Compiler directory and run the build script
```bash
$ cd Dice
$ make
```

- Write a small Dice program
```java
class HelloWorld {
  public void main(char[][] args) {
    print("Hello World!");
  }
}
```

- Compile the code and then run it!
```bash
$ ./dice input.dice
$ lli input.ll
Hello World!
```

## To test the compiler
- cd into tests and run tester.sh after having compiled the compiler
```bash
$ make test
```

### If you get an error: "error: expected value token" from lli
This means your version of lli is probably incorrect. Running "lli --version" should return 3.7, but if it doesn't:
- Run the following commands to remove the symlink of lli in your /usr/bin directory
```bash
$ sudo rm \usr\bin\lli
$ ln -s /usr/lib/llvm-3.8/bin/lli /usr/bin/lli
```
- Now you should be able to use lli with the outputted llvm code from dice

<div class="github-card" data-github="davidwatkins/Dice" data-width="400" data-height="150" data-theme="default"></div>
<script src="//cdn.jsdelivr.net/github-cards/latest/widget.js"></script>
