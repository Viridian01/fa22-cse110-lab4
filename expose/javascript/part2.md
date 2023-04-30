# Part 2 Answers
1. Line 12 will output 3, given `i` has function-level scope.
2. Line 13 will output 150, given `discountedPrice` has function-level scope and was last reassigned the value of `prices[2] * (1 - 0.5)` or 150.
3. Line 14 will output 150, given `finalPrice` was last assigned the value of `Math.round(150 * 100) / 100` on line 9.
4. 