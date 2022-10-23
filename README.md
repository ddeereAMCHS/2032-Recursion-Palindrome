# Palindrome

## Due: Wed 10/26 at 11:59 PM

### Part 1

- Create a program called `Palindrome.java`
- Create a recursive static method called isPalindrome that returns true if the String passed to it is a palindrome
  - A palindrome is a String that is the same forwards and backwards
    - ex. racecar
- In the main method:
  - Prompt the user for a word
  - Call the isPalindrome method with that word as a parameter
  - Print the result

### Part 2

- Add another method called isPalindromeIgnoreSpaces that returns true if the String passed to it is a palindrome, ignoring whitespace
  - Ex. `taco cat` would return true
- In the main method:
  - Prompt the user for a phrase that may or may not contain spaces
    - Make sure you prompt the user for this phrase before you print the result of the call to isPalindrome
  - Call the isPalindromeIgnoreSpaces method with that word as a parameter
  - Print the result

***Example Input:***\
taco cat\
taco cat\
***Example Output:***\
taco cat is not a palindrome\
taco cat is a palindrome (ignoring spaces)
