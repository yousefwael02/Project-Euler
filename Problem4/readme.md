# Largest Palindrome Product
A palindromic number reads the same from both ways, example 906609<br/>
An example of the largest palindromic number generated by the product of two-digits numbers is 9009 which is $99 \times 91$

## Steps
1. The function isPalindrome takes a number, converts it to a string and uses python indexing property in reversing which is str[::-1].
2. If the string is equal to its reverse, the function returns true, else returns false.
3. The function largestPalindrome takes the number of digits of the twow numbers that will compute the palindrome.
4. The function creates the boundaries of the numbers to loop through by raising 10 to the power of the number passed.
5. Two decrementing for loops are used to multiply two numbers together and the product is passed to the function isPalindrome.
6. If true is returned, the result is appended to an array.
7. The function largestPalindrome returns the largest value in the array.

## Disclaimer
Three test cases are provided at the end of the code.