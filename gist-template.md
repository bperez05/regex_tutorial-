# Matching a ReGex to an Email!

This Tutorial was made to demomtstrate how a regular expression works. Regular expresssions can be used to identify a phone number, email, address, ex

## Summary



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
Regex has multiple components that have differnet meanings for characters. Here an example of an email if to match the regular expression I have provided you with. 

^\w+@[a-zA-Z_]+?\.[a-zA-Z]{2,3}$ (joe@aol.com)

### Anchors
Anchors belong to the family of regex tokens that don't match any characters, but that assert something about the string or the matching process. Anchors assert that the engine's current position in the string matches a well-determined location: for instance, the beginning of the string, or the end of a line.
Anchors have special meaning in regular expressions. They do not match any character. Instead, they match a position before or after characters:
 ^ – The caret anchor matches the beginning of the text.
 $ – The dollar anchor matches the end of the text.

### Quantifiers
Quantifiers match a number of instances of a character, group, or character class in a string.
A number in curly braces {n}is the simplest quantifier. When you append it to a character or character class, it specifies how many characters or character classes you want to match.
For example, the regular expression /\d{4}/ matches a four-digit number. It is the same as /\d\d\d\

### Grouping Constructs
A character class allows you to match any symbol from a certain character set. A character class is also called a character set

### Bracket Expressions
 Bracket expression is either a matching list expression or a non-matching list expression. It consists of one or more expressions: ordinary characters, collating elements, collating symbols, equivalence classes, character classes, or range expressions.^[A-Za-z]+$ matches any string that contains only upper or lowercase characters.\[[0-9 ]*\] matches an opening square bracket, followed by any digits or spaces, followed by a closed bracket.

### Character Classes
Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits.
 "\w" Matches any alphanumeric character from the basic Latin alphabet, including the underscore. Equivalent to [A-Za-z0-9_]. For example, /\w/ matches "a" in "apple", "5" in "$5.28", "3" in "3D" and "m" in "Émanuel".

### The OR Operator
You can use the | operator (logical OR) to match characters or expression of either the left or right of the | operator. For example the (t|T) will match either t or T from the input string.
### Flags
A flag is an optional parameter to a regex that modifies its behavior of searching. A flag changes the default searching behaviour of a regular expression. It makes a regex search in a different way. A flag is denoted using a single lowercase alphabetic character.
### Character Escapes
The character that follows it is a special character, as shown in the table in the following section. For example, \b is an anchor that indicates that a regular expression match should begin on a word boundary, \t represents a tab, and \x020 represents a space.

## Author

Brandon Perez is the Author of this gist and is a beginer Devloper (https://github.com/bperez05)
