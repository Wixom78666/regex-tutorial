# Regex

RegEx stands for 'regular expression'. It allows for you to search for patterns in text in code.

## Summary

This tutorial will cover differnet components of a regular expression and what each stand for. By the end of this tutorial you will be able toexplain how regular expressions work and implement them into your own code.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

There are two anchor symbols in Regex: '^' and '$'. The '^' anchor begins a strirng and the '$' anchor ends the string.

### Quantifiers

Quatifiers are represented bby curly braces ({}). It tells us how many characters it is looking for. It will contain a two numbers separated by a comma to represent the max and min amount of characters beieng looked for.

### OR Operator

OR operator is the '|' symbol. It gives criteria to two differnt parts of a string.

### Character Classes

Two examples of character classes are the '/w' and '/d'. These will match either all leters in an expression (/w) or will match the digits of an expression.

### Flags

Flags are optional characters put at the end of an expression. They set a rule for the statement. The 'g' for example is used for global searches.

### Grouping and Capturing

Grouping and capturing are signified by the '@' symbol. It states what sort of pattern is allowed for user input when dealing with a string. For example it counld indicate whether the user could input a mix of numbers, letters, and/or special characters. It is ended with the '.' symbol.

### Bracket Expressions

Bracket expressions give the user a set of characters to match. For example: lower/upper casing, numbers, and special characters.

### Greedy and Lazy Match

Greedy matching tells the computer to continue the expression for as long as it needs it to be as where lazy matching looks for the shortest possible match.

### Boundaries

This is signified by '/b'. It is like am anchor that sets a boundary on a word.

### Back-references

This is signified by a '/' followed by a digit. It looks for the exact text of a previous match. It looks back at another reference.

## Author

Jacob Wixom. Coding hopeful. 
