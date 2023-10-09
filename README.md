# Regex Tutorial!

This is a tutorial on Regular Exressions (Regex).

Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.
## Table of Contents

   * [Anchors](##Anchors)
   * [Quantifiers]()
   * [OR Operator]()
   * [Character Classes]()
   * [Flags]()
   * [Grouping and Capturing]()
   * [Bracket Expressions]()
   * [Greedy and Lazy Match]()
   * [Boundaries]()
   * [Back-references]()
   * [Look-ahead and Look-behind]()

# Regex Components
## Anchors
Anchors assert the position of a string or the matching process. A Caret `^` helps us denote the beginning of a string or line and a Dollar `$` helps us denote the end.
`ing$` matches anything ending in "ing" and `^0` will match anything start with "0".

## Quantifiers
Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found. For instace, the `+` quantifier specifies that the preceding character class should appear one or more times.

If the `*`, `+`, `?`, `{`, and `}` characters are encountered in a regular expression pattern, the regular expression engine interprets them as quantifiers unless they are included in a character class.

## OR Operator
The OR operator `|` allows us to match expressions on either side. For instance, the regex `two | 2 ` accepts strings "two" or "2".

## Character Classes
A list of characters enclosed by `[ ]`. It matches ANY ONE character in the list unless there is a `^` in which case it matches any one NOT in the list. Eg. `[02468]` matches ANY single digit while `[^02468]` matches any single character not including the ones enclosed.

## Flags
## Grouping and Capturing
## Bracket Expressions
## Greedy and Lazy Match
## Boundaries
## Back-references
## Look-ahead and Look-behind

# Author
Ayush Sharma

https://github.com/AyushManiSharma
