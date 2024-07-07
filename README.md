ogórek
======
[![GoDoc](https://godoc.org/github.com/kisielk/og-rek?status.svg)](https://godoc.org/github.com/kisielk/og-rek)
[![Build Status](https://github.com/kisielk/og-rek/actions/workflows/ci.yml/badge.svg)](https://github.com/kisielk/og-rek/actions/workflows/ci.yml)

ogórek is a Go library for encoding and decoding pickles.

Fuzz Testing
------------
Fuzz testing has been implemented for decoder and encoder. To run fuzz tests do the following:

```
go get github.com/dvyukov/go-fuzz/go-fuzz
go get github.com/dvyukov/go-fuzz/go-fuzz-build
go-fuzz-build github.com/kisielk/og-rek
go-fuzz -bin=./ogórek-fuzz.zip -workdir=./fuzz
```
