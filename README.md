# Errorlib

[![Documentation](https://godoc.org/github.com/gigawattio/errorlib?status.svg)](https://godoc.org/github.com/gigawattio/errorlib)
[![Build Status](https://travis-ci.org/gigawattio/errorlib.svg?branch=master)](https://travis-ci.org/gigawattio/errorlib)
[![Report Card](https://goreportcard.com/badge/github.com/gigawattio/errorlib)](https://goreportcard.com/report/github.com/gigawattio/errorlib)

### About

Go (golang) library which provides convenience functions for dealing with errors.

Example use case:

Merging a slice of potential errors into either `nil` or a single concatenated error.

Created by [Jay Taylor](https://jaytaylor.com/) and used by [Gigawatt](https://gigawatt.io/).

### Requirements

* Go version 1.1 or newer

### Running the test suite

    go test ./...

#### License

Permissive MIT license, see the [LICENSE](LICENSE) file for more information.

### Related packages

See also:

* https://github.com/hashicorp/go-multierror
