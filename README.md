# Regex Tutorial

Welcome to the Regex tutorial for web development students.
In this tutorial, 
we'll be shedding light on each component 
to help you comprehend the search pattern it defines.

## Summary
We will be analazying the following regex
----- ^([a-zA-Z0-9_\-\.]+)@([a-zA-Z0-9_\-\.]+)\.([a-zA-Z]{2,5})$ -----
This regex is designed to validate the correct format of email addresses. 
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
Anchors mark the start and end of the regex. they ensure the email pattern is matched from the beggining to the end of the string. 
Example:   ^([a-zA-Z0-9_\-\.]+)$

In this example ^ is beggining anchor and $ is ending anchor.
### Quantifiers
Quantifiers define the quantity of characters or groups to match.  + after a character class means one or more occurences of that class.
Example : ^([a-zA-Z0-9_\-\.]+)$

### OR Operator
The OR operator, represented by |, allows for alternative matching. It helps define choices within the regex.
example: ^(black|orange|blue|red)$ this means it matches black, orange, blue, or red

### Character Classes
Character classes are denoted by square brackets [ ], and they define a set of characters to match. 
In this regex they specify [a-zA-Z0-9_\-\.] as valid characters
Example: ^[a-zA-Z0-9_\-\.]+$

### Grouping and Capturing
Groups, enclosed in parentheses, are used for capturing and grouping. 
They help in treating multiple characters as a single unit.

### Bracket Expressions
Bracket expressions are another way to define character sets. 
They are used to match a single character out of a group of characters
### Greedy and Lazy Match
Greedy matching is the default behavior, attempting to match as much as possible. 
Lazy matching, denoted by '?', matches as little as possible.
### Boundaries
Boundaries, '\b', assert the position at the beginning or end of a word.
### Back-references
Back-references, denoted by '\1', refer to a previously captured group.
### Look-ahead and Look-behind
Look-ahead and look-behind assertions assert whether a certain pattern is ahead or behind the current position without including it in the match.
## Author

This tutorial was crafted by Joshua Bradshaw. Connect with me on GitHub @ github/Jbradu2 for more projects in the coding world.
