# Week 1
## Overview
1. Validation
2. Verification
3. Validation
4. Verification
5. ```It checks the whole system``` and ```It documents system behavior```

## On the difficulty of software testing
1. Continuous systems are simpler to test because you can often extrapolate test results from one point to points 'nearby'.
2. ```A  = 5, X = 5, N = 5``` and ```A  = 1, X = 10, N = 1```
3. Optimistic
4. No

## What is a Test?
1. A program that automatically matches the actual program output to the expected output of the test case.
2. True
3. ```Remove data you added after testing is done``` and ```Close connection after testing is done```
4. Software output is checked by an oracle.

## Automation: Using a Test Framework
1. ```They allow automated``` and ```They run all test cases``` and ```They allow programmers```
2. all
3. ```In a separate class```

## Automation: Writing JUnit Tests
1. all
2. The main method.
3. False.
4. A good idea. Test cases should be built based on the expected output and should not be influenced by the implementation.
5. All test cases need to be run including the new one.

# Week 2
## Dependability Quiz
1. 2,1,3
2. error removal
3. False
4. False
5. True
6. False
7. False

## Testing Principles: Where
1.
- [x] Arithmetic on floating point numbers is often approximate, so it can introduce errors
- [x] Floating point numbers have values that are not actually numbers, such as infinity and NaN (not a number), that can cause computations to behave strangely.
- [x] As floating point computations are approximate, equality comparisons fail after computations that would succeed when using real numbers
2.
- [x] Programmers often make 'off-by-one' errors
- [x] Determining strict limits on ranges is difficult in requirements engineering
- [x] Relational boundaries define points of discontinuity for programs
3.
- [x] When converting an integer to a smaller bit length (e.g. long to int), the value may be truncated.
- [x] When converting to a larger bit length (e.g., int to long), the value may change from positive to negative.
- [x] When converting from signed to unsigned types (e.g., int to byte), negative numbers can't be represented.
- [x] When converting from a double to int, the value is truncated to a whole number.
