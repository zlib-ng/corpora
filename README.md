## Corpora

This repository contains common corpora used for lossless compression testing and benchmarking.

### Sources

Detailed descriptions of the files found in each of the corpus can be found below.

|Corpus|URL|Notes|
|:-|:-|:-|
|Canterbury|https://corpus.canterbury.ac.nz/|Includes artificial, calgary, canterbury, large, and miscellaneous corpus.|
|Silesia|http://sun.aei.polsl.pl/~sdeor/index.php?page=silesia||
|Snappy|https://github.com/google/snappy|Test data with some duplicates removed that were present in other corpus.|
|Neuro|https://github.com/neurolabusc/zlib-bench|NIfTI format brain images.|

### Profiles

Statistical profiles of each corpus: byte-value distribution, order-0 and
order-1 entropy beside deflate reference rates, byte coverage by match
distance and matched bytes by match length from a greedy 4-byte parse over
sampled 32K-history windows, and per-file size, printable share, and most
common byte share.

#### artificial

![artificial corpus profile](https://raw.githubusercontent.com/nmoinvaz/codecbench/main/profiles/artificial.svg)

#### calgary

![calgary corpus profile](https://raw.githubusercontent.com/nmoinvaz/codecbench/main/profiles/calgary.svg)

#### canterbury

![canterbury corpus profile](https://raw.githubusercontent.com/nmoinvaz/codecbench/main/profiles/canterbury.svg)

#### large

![large corpus profile](https://raw.githubusercontent.com/nmoinvaz/codecbench/main/profiles/large.svg)

#### miscellaneous

![miscellaneous corpus profile](https://raw.githubusercontent.com/nmoinvaz/codecbench/main/profiles/miscellaneous.svg)

#### neuro

![neuro corpus profile](https://raw.githubusercontent.com/nmoinvaz/codecbench/main/profiles/neuro.svg)

#### silesia

![silesia corpus profile](https://raw.githubusercontent.com/nmoinvaz/codecbench/main/profiles/silesia.svg)

#### snappy

![snappy corpus profile](https://raw.githubusercontent.com/nmoinvaz/codecbench/main/profiles/snappy.svg)

### License

All files are the works of their respective authors. Please see the sources above for any licensing information.