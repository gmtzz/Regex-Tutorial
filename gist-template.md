# Regex Tutorial

Regex (regular expression) is an optimally working search tool used in programming. It allows programmers to change, find, or check if strings follow a specific pattern. Regex is in the form of characters and they define a search pattern. Examples of using regex include, checking if an email address is correct, finding words, or changing parts of text.  


## Summary
A common example of regex is one used for email validation: 
 `/^\w+([\.-]?\w+)*@\w+([\.-]?\w+)*(\.\w{2,3})+$/`
The above regular expression is used to validate email addresses and checks for email format such as the "@" and the email is divided into a local and domain part and the top level domain. 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
+ Anchors show where the matching starts and ends in the text
+ Using the email validation regex below, you will find the anchors highlighted below:
+ `/^`\w+([\.-]?\w+)*@\w+([\.-]?\w+)*(\.\w{2,3})+`$/`

### Quantifiers
+ Quantifiers indicates x times an element or group in the regex should be matched 
+ Using the email validation regex, you will find  the quantifiers listed  below:
+ +, *, and ?
+ Email validation regex: /^\w+([\.-]?\w+)*@\w+([\.-]?\w+)*(\.\w{2,3})+$/
+ These quanitifiers allow email addresses with different patterns are matches. An example is that it can match emails like giselle@gmail.com and gigi@us.co.google.com while still following the standard format regulations.
### Grouping Constructs


### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
