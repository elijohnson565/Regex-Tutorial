# Regex-Email-Tutorial

## Summary
This is the regular expression for an email an email (`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`). This short tutorial will explain how it works. 

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
`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

### Anchors
^ and $ signify the beginning and end of the expression. Everything in between them is checked for.

### Quantifiers
"+" adds adds values in the parenthesis 
{2,6} this determines the length of the string to check.

### OR Operator
this regex doesnt have an OR operator

### Character Classes
\d Matches any digit character that is within (0-9). This is found in the second group of the expression.

### Flags
There are no flags in this expression.

### Grouping and Capturing
() captures the grouping of characters, character classes, and quantifiers. In this expression, it is specifically capturing the information within the [], the "+" which adds the groups together, and in the last group there is a quantifier {}. There is also an @ sign that is sandwiched between the first to group to signify the seperation of the two.

### Bracket Expressions
[] chooses any of the characters within the brackets. In the first group it is any letter in the alphabet, any digit, with special characters (_\.-).

### Greedy and Lazy Match
There are no greedy or lazy matches

### Boundaries
There are no boundaries stated in this expression.

### Back-references
There are no back references.

### Look-ahead and Look-behind
This expression has no look-ahead or look-behind components.

## Author
My name is Elijah Johnson, I live in the California and love to code!

Github: https://github.com/elijohnson565
