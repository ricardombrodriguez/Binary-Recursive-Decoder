# Binary Recursive Decoder

This is our third and final project of the *Algorithms and Data Structure* class, written in C language.

## Introduction

In order to carry out this work, it was proposed to decode an encrypted message presented in non-instantaneous binary code. Each decoded symbol of the alphabet can be represented in binary by a specific sequence of bits we call *binary codeword*. This list of symbols, as well as their respective encoding, can be visualized when executing the program *./A03 -s* followed by two parameters: the number of symbols desired and the seed we want to use.

That being said, the main objective is to develop a recursive function *recursive_decoder* in C language that can translate the encoded message, returning the number of possible solutions to the same problem, as well as the largest number of badly encoded bits in sequence.

## How to compile and run

First, we need to compile the program by following this step:

```
make A03
```

Now, in order to execute the main program, we write *./A03 -t* followed by three arguments: the number of symbols, the size of the original decoded message and, finally, the seed.

## Authors

- Alexandre Serras
- [João Reis](https://github.com/joaoreis16)
- [Ricardo Rodriguez](https://github.com/ricardombrodriguez)
