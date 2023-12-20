# Regex Tutorial

Welcome to the Regex tutorial for web development students.
In this tutorial, 
we'll be shedding light on each component 
to help you comprehend the search pattern it defines.

## Summary
We will be analazying the following regex
----- ^([a-zA-Z0-9_\-\.]+)@([a-zA-Z0-9_\-\.]+)\.([a-zA-Z]{2,5})$ -----
This regex is designed to validate email addresses. 
Throughout this tutorial, we'll break down each component, 
explaining its role in ensuring the correct format of an email address.


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
Represented by ^ and $, Anchors encapsulate a line. In our email regex, ^ ensures the email starts with a valid sequence, 
and $ ensures it ends appropriately.
### Quantifiers
Quantifiers define the quantity of characters or groups to match.  + after a character class means one or more occuyrences of that class.
### OR Operator
The OR operator, represented by |, allows for alternative matching. It helps define choices within the regex.
example: ^(black|orange|blue|red)$ this means it matches black, orange, blue, or red

### Character Classes
Character classes are denoted by square brackets [ ], and they define a set of characters to match. 
In this regex they specify [a-zA-Z0-9_\-\.] as valid characters
### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
