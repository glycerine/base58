base58
==========

* original location of this library: https://github.com/btcsuite/btcd/btcutil/base58
* new location, just the base58 library: https://github.com/glycerine/base58
* I (glycerine) have simply extracted just the base58 library out of btcd in order to reduce the import bulk.
* The btcd version was v0.24.2. I will tag this extraction as the same.
* The rest of the original README follows:

[![Build Status](http://img.shields.io/travis/btcsuite/btcutil.svg)](https://travis-ci.org/btcsuite/btcutil)
[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](http://copyfree.org)
[![GoDoc](https://img.shields.io/badge/godoc-reference-blue.svg)](http://godoc.org/github.com/btcsuite/btcd/btcutil/base58)

Package base58 provides an API for encoding and decoding to and from the
modified base58 encoding.  It also provides an API to do Base58Check encoding,
as described [here](https://en.bitcoin.it/wiki/Base58Check_encoding).

A comprehensive suite of tests is provided to ensure proper functionality.

## Installation and Updating

```bash
$ go get -u github.com/btcsuite/btcd/btcutil/base58
```

## Examples

* [Decode Example](http://godoc.org/github.com/btcsuite/btcd/btcutil/base58#example-Decode)  
  Demonstrates how to decode modified base58 encoded data.
* [Encode Example](http://godoc.org/github.com/btcsuite/btcd/btcutil/base58#example-Encode)  
  Demonstrates how to encode data using the modified base58 encoding scheme.
* [CheckDecode Example](http://godoc.org/github.com/btcsuite/btcd/btcutil/base58#example-CheckDecode)  
  Demonstrates how to decode Base58Check encoded data.
* [CheckEncode Example](http://godoc.org/github.com/btcsuite/btcd/btcutil/base58#example-CheckEncode)  
  Demonstrates how to encode data using the Base58Check encoding scheme.

## License

Package base58 is licensed under the [copyfree](http://copyfree.org) ISC
License.
