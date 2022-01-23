# LHA Library for Java

## Overview

Java implementation of the LHA/LHarc/LZH archive format https://en.wikipedia.org/wiki/LHA_(file_format)

Based on jLHA v0.06-5 published at http://dangan.g.dgdg.jp/Content/Program/Java/jLHA/LhaLibrary.html

## Features

* Read/write of generic LHA/LHarc header levels 0-2
* Compression and decompression of lh0-lh7, lz4, lz5, lzs
* lz5 compression compatible with https://github.com/fragglet/lhasa

## Changes since jLHA v0.06-5

* lh1-lh4 compression now compatible with other LHA implementations
* Source code encoding changed from Shift_JIS to UTF-8

## License

* 2-clause BSD
