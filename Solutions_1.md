# Problem Set 1 Solutions

## Asymptotic Practice

- Problem 1.1
  - For each group of functions, sort the functions in increasing order of asymptotic complexity:
    - (a) Group 1
      ```
      f1(n) = n^0,.999999 log(n)
      ```
      ```
      f2(n) = 10000000n
      ```
      ```
      f4(n) = n^2
      ```
      ```
      f3(n) = 1.000001^n
      ```
    - (b) Group 2
      ```
      f1(n) = 2^2^1000000
      ```
      ```
      f4(n) = n * sqrt(n)
      ```
      ```
      f3(n) = n choose 2
      ```
      ```
      f2(n) = 2^100000n
      ```
    - (c) Group 3
      ```
      f4(n) = Summation(i + 1)
      ```
      ```
      f1(n) = n^(sqrt(n))
      ```
      ```
      f3(n) = n^10 * 2^(n/2)
      ```
      ```
      f2(n) = 2^n
      ```
      
- Problem 1.2
  - For each of the following recurrence relations, pick the correct asymptotic runtime:
    - (a) Select the correct asymptotic complexity of an algorithm with runtime T(n, n) where
      ```
      T(x, c) = O(x)  for c <= 2,
      T(c, y) = O(y)  for c <= 2, &
      T(x, y) = O(x + y) + T(x/2, y/2).
      ```
      1. ```O(log(n))```
      2. ```O(n)```
