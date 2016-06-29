# maximum-subsequence
Parallel maximum subsequence  in C using OpenMP

## Dependencies
* OpenMP

## How to use it

### Compilation
`gcc maximum_subsequence.c -o maximum_subsequence -Wall -lm -fopenmp`

### Execution
`./maximum_subsequence input_file`

## Code example
The following example use the classic game rules.

### Input
```
3 2 -7 11 10 -6 4 9 -6 1 -2 -3 4 -3 0 2
```

### Output
```
28 11 10 -6 4 9
```
