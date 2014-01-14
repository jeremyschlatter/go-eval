go-eval
=======

This is the new home for the ``exp/eval`` package: the beginning of an interpreter for Go.

## Installation

```sh
$ go get github.com/sbinet/go-eval/...
```

## Usage

```sh
$ go-eval
:: welcome to go-eval...
(hit ^D to exit)
> hello := "world"
> println(hello)
world
>
```

## Documentation

  http://godoc.org/github.com/sbinet/go-eval


## Interpreter

The ``go-eval`` command is rather barebone.
But there is [igo](http://github.com/sbinet/igo) which is built on top of the ``eval`` package and provides some additional refinements.
