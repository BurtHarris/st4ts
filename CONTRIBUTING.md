# Contributing to the StringTemplate 4 TypeScript Target

## Contributor agreement

The StringTemplate 4 TypeScript target is a satellite project of StringTemplate 4. Contributions to the project in the form of code can
only be considered when sent from users who have signed the
[ANTLR 4 contributor agreement](https://github.com/antlr/antlr4/blob/master/contributors.txt).

## Building from Source

### Prerequisites

Building this repository from source requires several tools:

* Node.js 6.7.x

### Building the code

The code is built through a sequence of several steps which is automated through the following `npm` command.

```
npm install
```

### Running tests

This project includes two separate test suites. The first set of tests is included in the **tests** folder, and is
written in TypeScript using the mocha unit test framework. These tests execute quickly, but only cover a very limited
subset of the TypeScript runtime's functionality.

```
npm test
```

> ### Java Reference code
> To view the Java code this project was derived from, use the following commands in the project root directory.   This *isn't* strictly needed for building the project, and the reference implementation is expected to be fairly stable.
>
> ```
> git submodule init
> git submodule update
> ```
