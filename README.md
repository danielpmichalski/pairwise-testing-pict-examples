# Pairwise Testing examples
This repo holds several examples of automated test cases generation using the Pairwise testing method using the [Microsoft's PICT tool](https://github.com/microsoft/pict).

## Running examples
- generating pairwise test cases (example1.model gives 24 test cases with pairwise approach):
```
$> pict.exe example1.model > example1.csv
```
- generating a comprehensive suite of test cases (example2.model gives 288 test cases):
```
$> pict.exe example2.model /o:4 > example2.csv
```
