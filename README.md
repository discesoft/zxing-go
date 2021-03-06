zxing-go
==========

[![Travis](https://img.shields.io/travis/discesoft/zxing-go.svg?style=flat-square)](https://travis-ci.org/discesoft/zxing-go)
[![Codecov](https://img.shields.io/codecov/c/github/discesoft/zxing-go.svg?style=flat-square)](https://codecov.io/gh/discesoft/zxing-go)
[![Codacy grade](https://img.shields.io/codacy/grade/b9ba456130484ec2838e06dfd7337cf8.svg?style=flat-square)](https://www.codacy.com/app/CalmBit/zxing-go)
[![GitHub release](https://img.shields.io/github/release/discesoft/zxing-go.svg?style=flat-square)](https://github.com/discesoft/zxing-go/releases)

This is a direct port of the Java version of [zxing](https://github.com/zxing/zxing/) into Go.

Most of the logic is 1-1, apart from some idiomatic or 
language-specific conversions, such as exceptions being 
replaced by errors as return types.

Other than that, this should be functionally equivalent,
at least where it counts. It's not yet complete, but I'm
hoping to have most of the grunt work done in a couple of
weeks (manually translating statements into idiomatic Go
can be tough).

Additionally, it should be noted that functionally, _none_
of this is code that I've written - I'm simply porting the
code over into a different language. Therefore, you can
yell at me for mistakes, but all praise should be directed
to the wonderful people who wrote this library. Also,
all copyrights are retained by them under the Apache
License 2.0, as described in COPYING.

