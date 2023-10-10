# Palindrome

## Due: Mon 10/16 at 11:59 PM

- Create a program called `Palindrome.java`
- Create a recursive static method called isPalindrome that returns true if the String passed to it is a palindrome
  - A palindrome is a String that is the same forwards and backwards
    - ex. racecar
- Add another method called isPalindromeIgnoreSpaces that returns true if the String passed to it is a palindrome, ignoring whitespace
  - Ex. `taco cat` would return true
- In the main method:
  - Prompt the user for a word/phrase
  - Prompt the user for another word/phrase
  - Call the isPalindrome method with the first word/phrase as a parameter
  - Call the isPalindromeIgnoreSpaces method with the second word/phrase as a parameter
  - Print the results

***Example Input:***\
taco cat\
taco cat\
***Example Output:***\
taco cat is not a palindrome\
taco cat is a palindrome (ignoring spaces)
