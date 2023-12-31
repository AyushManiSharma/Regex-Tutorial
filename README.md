# Regex Tutorial!

This is a tutorial on Regular Exressions (Regex).

Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.
## Table of Contents

   * [Anchors](#anchors)
   * [Quantifiers](#quantifiers)
   * [OR Operator](#OR-Operator)
   * [Flags](#Flags)
   * [Grouping and Capturing](#Grouping-and-Capturing)
   * [Bracket Expressions](#Bracket-Expressions)
   * [Greedy and Lazy Match](#Greedy-and-Lazy-Match)
   * [Boundaries](#Boundaries)
   * [Back-references](#Back-references)
   * [Look-ahead and Look-behind](#Look-ahead-and-Look-behind)

# Regex Components
## Anchors
Anchors assert the position of a string or the matching process. A Caret `^` helps us denote the beginning of a string or line and a Dollar `$` helps us denote the end.
`ing$` matches anything ending in "ing" and `^0` will match anything start with "0".

## Quantifiers
Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found. For instace, the `+` quantifier specifies that the preceding character class should appear one or more times.

If the `*`, `+`, `?`, `{`, and `}` characters are encountered in a regular expression pattern, the regular expression engine interprets them as quantifiers unless they are included in a character class.

## OR Operator
The OR operator `|` allows us to match expressions on either side. For instance, the regex `two | 2 ` accepts strings "two" or "2".

## Flags
A regular expression consists of a pattern and optional flags. They can change how the matching is performed, like making case-insensitive with the `i` flag.

## Grouping and Capturing
Parentheses `( )` are used to group in regex. Grouping allows us to group together multiple characters and apply expressions to the whole group.

## Bracket Expressions
A list of characters enclosed by `[ ]`. It matches ANY ONE character in the list unless there is a `^` in which case it matches any one NOT in the list. Eg. `[02468]` matches ANY single digit while `[^02468]` matches any single character not including the ones enclosed.

## Greedy and Lazy Match
Greedy Match: The repetition operators are "greedy operators", and grasp as many characters as possible for a match. The regex `ab{2,4}` will try to match for "abbbb", then "abbb", and then "abb".
Lazy Quantifiers: We can put an extra `?` after the repetition operators to curb its greediness

## Boundaries
`\b`: boundary of word. i.e., start-of-word or end-of-word. E.g., \bcat\b matches the word "cat" in the input string.
`\B`: Inverse of \b, i.e., non-start-of-word or non-end-of-word.

## Back-references
Use parentheses `( )` to create a back references. Used to extract the matched substring from the input string.

## Look-ahead and Look-behind
The `?=` is known as a lookahead. It provides only the result: "match" or "no match"

# Author
Ayush Sharma

https://github.com/AyushManiSharma
