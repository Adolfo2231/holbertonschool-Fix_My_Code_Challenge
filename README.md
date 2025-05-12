# Fix My Code Challenge

## FizzBuzz Challenge

This repository contains solutions for the "Fix My Code Challenge" series. The first challenge is implementing the FizzBuzz algorithm.

### FizzBuzz Implementation

The FizzBuzz program prints numbers from 1 to n, where:
- For multiples of three, it prints "Fizz"
- For multiples of five, it prints "Buzz"
- For numbers which are multiples of both three and five, it prints "FizzBuzz"
- For all other numbers, it prints the number itself

### Usage

```bash
./0-fizzbuzz.py <number>
```

Example:
```bash
./0-fizzbuzz.py 15
```

This will output:
```
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 FizzBuzz
```

### Fix Details

The original implementation had a logical error in the order of conditions. The fix involved:
1. Reordering the conditions to check for FizzBuzz (multiples of both 3 and 5) first
2. Then checking for Fizz (multiples of 3)
3. Finally checking for Buzz (multiples of 5)

This ensures that numbers divisible by both 3 and 5 are correctly identified as "FizzBuzz" instead of just "Fizz". 