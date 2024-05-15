My implementations for Nand2Tetris Course

### [Nand2Tetris Coursera](https://www.coursera.org/learn/build-a-compute) 

### [Nand2Tetris Website](https://www.nand2tetris.org/)

----
## Here is the 2 input Boolean Functions that may help you: 

| Function       |         | 0 0 | 0 1 | 1 0 | 1 1 |
|----------------|---------|-----|-----|-----|-----|
| Constant 0     | 0       | 0   | 0   | 0   | 0   |
| And            | x · y   | 0   | 0   | 0   | 1   |
| x And Not y   | x · ȳ  | 0   | 0   | 1   | 0   |
| x             | x       | 0   | 0   | 1   | 1   |
| Not x And y   | x̄ · y  | 0   | 1   | 0   | 0   |
| y             | y       | 0   | 1   | 0   | 1   |
| Xor            | x · ȳ + x̄ · y | 0   | 1   | 1   | 0   |
| Or             | x + y   | 0   | 1   | 1   | 1   |
| Nor            | (\frac{x+y}{x+y}) | 1   | 0   | 0   | 0   |
| Equivalence    | x · y + x̄ · ȳ | 1   | 0   | 0   | 1   |
| Not y         | ȳ       | 1   | 0   | 1   | 0   |
| If y then x   | x + ȳ  | 1   | 0   | 1   | 1   |
| Not x         | x̄       | 1   | 1   | 0   | 0   |
| If x then y   | x̄ + y  | 1   | 1   | 0   | 1   |
| Nand          | (\overline{x · y}) | 1   | 1   | 1   | 0   |
| Constant 1     | 1       | 1   | 1   | 1   | 1   |
