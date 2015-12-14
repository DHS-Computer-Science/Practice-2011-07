# Practice 2011 - 07: Integer Flipping

## Background
Aliens have finally visited Earth. They are in fact, similar to us in every
single way except in the way that they represent integers in binary. We
represent an integer in a computer as a 32-bit binary. These aliens represent
numbers completely differently, but still as a 32-bit number. Given an unsigned
32-bit number in our representation, determine how the aliens would represent
it. To determine how the aliens would represent it:
1. Convert the number to its binary representation
2. Reverse the order of the bits
Finally, take the reversed order number and convert it back to a positive,
unsigned decimal as we would represent it.

For example, if they were 4-bit numbers and you were given the value 4,
you would convert it to binary and get 0100(base 2). Then flip it and get
0010(base 2). Finally convert it back to decimal to get the final answer of 2.

## Description

### Input
Each line will contain a single integer on which to perform the integer flipping
algorithm. The number will be in Earth's representation. A line starting with -1
will mark the end of the test cases.

### Output
For each integer in Earth's integer representation, you should calculate the
value of the aliens' "flipped" integer and print its value in decimal format.
More specifically, take the input number, convert it into a 32-bit integer,
flip this integer into the aliens' format, and then evaluate the 32- bit binary
number as if it were still in earth's representation. Print this value in
decimal format.

## Sample
### Input
```
2
1
536870912
-1
```

### Output
```
1073741824
2147483648
4
```
