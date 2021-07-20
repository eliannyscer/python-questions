# Write a program in Python to check if a sequence is a Palindrome

A string is said to be palindrome if the reverse of the string is the same string.

`Example:`

```text
Input: Malayalam
Output: Yes

Input: Radar
Output: Yes

Input: Ellie
Output: No
```

## Program

`Example:` - Method using one extra variable

```python
word = "Ellie"
 
result = ""
for w in word:
    result = w + result
 
if (word == result):
    print(f 'The word "{word}" is palindrome')
else:
    print(f 'The word "{word}" is not palindrome')

# Output:
The word "Ellie" is not palindrome
```

In this method user take a character of string one by one and store in an empty variable. After storing all the character user will compare both, the string and check it is palindrome or not.

## Reference

[Examples](https://www.geeksforgeeks.org/python-program-check-string-palindrome-not/)

[Palindrome words](https://www.rd.com/list/palindromes-list/)
