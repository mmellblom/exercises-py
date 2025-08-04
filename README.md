1. Hello and Name

Goal: Write a script that asks the user for their name and then greets them.
Practices: input(), string formatting.
Example:
Input: Alice
Output: Hello, Alice! Welcome back to Python.
Extension: Ask for their favorite hobby and include it in the greeting.


2. Simple Calculator

Goal: Prompt the user for two numbers and print their sum, difference, product, and quotient.
Practices: Type conversion, arithmetic, handling division by zero.
Example:
Input: 8, 2
Output:

Sum: 10  
Difference: 6  
Product: 16  
Quotient: 4.0

Hint: Use float() to allow decimals.


3. Odd or Even Detector

Goal: Ask the user for an integer and print whether it’s odd or even.
Practices: Modulo operator, conditionals.
Example:
Input: 7
Output: 7 is odd.
Extension: Validate that the input is an integer (handle bad input gracefully).


4. List Statistics

Goal: Given a list of numbers (hardcode or parse from input), compute and print the min, max, sum, and average.
Practices: Lists, built-in functions, loops or comprehension.
Example:
Input: [2, 5, 9, 3]
Output:

Min: 2  
Max: 9  
Sum: 19  
Average: 4.75

Extension: Allow the user to enter the list as comma-separated values.


5. Fibonacci Sequence (First N)

Goal: Print the first n numbers of the Fibonacci sequence, where n is given by the user.
Practices: Loops, sequence generation.
Example:
Input: 5
Output: 0, 1, 1, 2, 3
Extension: Implement recursively (and compare performance with iterative).


6. Word Counter

Goal: Ask the user to input a sentence and output how many words there are.
Practices: String methods, splitting.
Example:
Input: Python is fun to learn.
Output: 5 words.
Extension: Output frequency of each word (case-insensitive, strip punctuation).


7. Palindrome Checker

Goal: Check whether a given string is a palindrome (reads the same backward and forward), ignoring spaces and case.
Practices: String manipulation, slicing, conditionals.
Example:
Input: A man a plan a canal Panama
Output: It's a palindrome.
Extension: Ignore punctuation too.


8. Guess the Number

Goal: Computer picks a random number between 1 and 100; user tries to guess it, and the program gives “too high” / “too low” feedback until correct.
Practices: random module, loops, input validation.
Extension: Count number of attempts and report at the end.


9. Simple To-Do List (in-memory)

Goal: Let the user add, view, and remove tasks from a list via a text menu until they choose to exit.
Practices: Lists, loops, basic menu-driven CLI.
Extension: Save and load the list from a file (persistent to-do).


10. Character Frequency in a String

Goal: Given a string, output how many times each character appears (excluding spaces).
Practices: Dictionaries, iteration.
Example:
Input: hello
Output: h:1 e:1 l:2 o:1
Extension: Show the characters sorted by frequency descending.


11. CSV Reader (basic)

Goal: Read a simple CSV file (you can create a small one manually) and print each row as a dictionary (headers to values).
Practices: File I/O, csv module, exception handling.
Extension: Allow filtering rows by a column value.


12. Prime Number Tester

Goal: Ask the user for a number and determine if it’s prime.
Practices: Loops, mathematical logic, optimization (e.g., checking up to sqrt).
Example:
Input: 17
Output: 17 is prime.
Extension: List all primes up to n.


13. Simple Text-Based Hangman (limited)

Goal: Implement a simplified version of Hangman: choose a secret word, show underscores, let the user guess letters, reveal them if correct, and limit wrong guesses.
Practices: Strings, lists, loops, conditionals.
Extension: Load secret words from a file; show used letters.


14. Email Validator

Goal: Ask the user for an email address and perform basic validation: contains exactly one @, has a domain portion with a ., etc.
Practices: String parsing, functions, boolean logic.
Extension: Use regular expressions (re module) for more robust checking.


15. Simple Expense Tracker

Goal: Let the user input expenses with categories (e.g., food 12.50, transport 3.40), store them, and then print total spent per category and overall.
Practices: Parsing input, dictionaries, aggregation, formatting output.
Extension: Export summary to a text or CSV file; allow date tagging and filtering by date ranges.