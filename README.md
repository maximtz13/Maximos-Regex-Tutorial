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

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
