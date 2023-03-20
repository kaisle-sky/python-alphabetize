# Alphabetize - Python
A script that alphabetizes the contents of a list, set, or tuple.

Initial notes:
Goal - Create a script that alphabetizes whatever is passed to it. It should be able to handle multiple data types and output a single list of unique, alphabetized items. 

Notes prior to starting:
- How to alphabetize?
-   Build a dictionary made up of lower and uppercase letters, each with an associated integer or "point" value. 
Ex.
alphabetize = {
  "A" : 999;
  "a" : 999:
  "B:: : 998;
  .
  .
  .
  "z" : 974;
  }
  
-   Iterate through two words to compare letters, using boolean operaters to determine which letter is closer to the beginning of the alphabet.
-   Keep in mind that string comparisons are case-sensetive, so caps and lowercase both need to be checked
-   Need to develop method for calling non-indexed items
-     For example, comparing "apple" and "apples" would lead to comparing "s" to a non-index
-   Use .insert() to add items to specific indexes in a list.
