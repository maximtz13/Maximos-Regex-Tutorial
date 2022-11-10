# Maximos-Regex-Tutorial

A brief summary and example of regex.  This example of regex will be used for email requirements.

## Summary

In this tutorial, I will be explaining how to use regex to enforce requirements for an email. Regex simplifies the coding process of adding requirements to a password or email. For reference, any further information provided in this tutorial will be in regards to the following code:
```
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```

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

In my example, the anchors I am using "^" denotes the start of a string, and "$" denotes the end of a string.

### Quantifiers

In my example, there are three quantifiers. The two "+" signs, and the "{2,6}" is the third and final quantifier.
Quantifiers are used to include the token preceeding the quantifier itself between zero and unlimited times. Not all quantifiers have to be included in the code hence the 0 times.

### Character Classes

Character classes or "sets" can be used to tell the regex engine to match one character out of several. In my example code it was used in the following code snippets: "[a-z0-9_.-]","[\da-z.-]", and "[a-z]".

### Grouping and Capturing

Groups group multiple patters as a whole, and capturing groups provide extra submatch information when using a regular expression pattern to match against a string.
The first capturing group is ([a-z0-9_.-]+) which is capturing the user's name for the email. This capture group can have letters, numbers, an underscore, or a dash. The second capturing group is ([\da-z,-]+) which is capturing the email site. This capture group can have numbers, letters, or a dash. The third capturing group is ([a-z.]{2,6}), which can only be letters and a period between 2 and 6 characters long. 

### Bracket Expressions

Brackets indicate a set of caharcters to match. Any individual character between the brackets will match, and you can also use a hyphen to define a set. Anything between two brackets in my code is an example of a bracket expression.

### Greedy and Lazy Match

Any character that matches as many times as needed is "greedy" and anything that matches with as few characters as possible is "lazy". In my example there are three greedy quantifiers: the two "+" signs. and {2.6}.

## Author

Feel free to check out [my github](https://github.com/maximtz13) and please reach out for any questions! I am a future web-developer but will be glad to spread any information I have learned.
