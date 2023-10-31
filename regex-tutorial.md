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
+ Using the email validation regex below, you will find the anchors highlighted:
 `/^`\w+([\.-]?\w+)*@\w+([\.-]?\w+)*(\.\w{2,3})+`$/`

### Quantifiers
+ Quantifiers indicates x times an element or group in the regex should be matched.
+ Using the email validation regex, you will find  the following quantifiers:  +, *, and ?
+ Email validation regex: /^\w+([\.-]?\w+)*@\w+([\.-]?\w+)*(\.\w{2,3})+$/
+ These quanitifiers allow email addresses with different patterns are matches. An example is that it can match emails like giselle@gmail.com and gigi@us.co.google.com while still following the standard format regulations.
### Grouping Constructs
+ Grouping with ( ) allow programmers to use a portion of the pattern as a unit.
+ Capturing allows programmers to retrieve the content stored inside the parentheses (grouping) at a later time for their code if needed. 
+ Below is an example of grouping from the email validation regex: (\.\w{2,3})+

### Bracket Expressions
+ Bracket expressions allow programmers to specify a set of  characters to match while also allowing variations.
+  For example: in the email validation regex we have, `[.-]` in these brackets is a dot and hyphen. This allows programmers to allow
email addresses with . and -. Emails like giselle-m@gmail.com or giselle.m@gmail.com would be allowed. 

### Character Classes
+ Character classes allow programmers to match specific sets of characters without the tedious work of listing each character individually. In this example, the `\w` matches word characters (letters, digits, and underscores) 
/^`\w`+([\.-]?`\w`+)*@`\w`+([\.-]?`\w`+)*(\.`\w`{2,3})+$/

### The OR Operator
+ `|` The OR operator allows multiple alternatives to match. a|b can match either a or b.
+ [\.-]? in the email validation regex represents an OR operation between a dot . and a hyphen -.
This part allows for matching either a dot or a hyphen, although not mandatory. The ? after the character class makes it optional.


### Flags
+ Flags is an optional feature for different matching behaviors.
+ an example of a flag is `i`, in `/number/i` matches number, Number, and NUMBER.

### Character Escapes
+ character escapes allow programmers to match specific characters. 
+ using a backslash `\`
+  `\(email\)` would match (email) in the text.

## Author

Giselle Martinez, to see my work please go to https://github.com/gmtzz 
