# Regular Expressions(Regex) Guide

This is a guide to understand what Regex is and how to understand it.

## Summary

Regex is a search pattern defined by a series of special characters. As developers we don't know what users may input but we want to be able to validate an input, such as a password or username.

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
`/.../` all regex notation must be wrapped in slashes.

### Anchors
Anchors signify either the start or end.
`^` The caret indicates the beginning of a string.

`$` The dollar sign indicates the end of a string.

You can search for an exact match by wrapping desired text in these anchors: `^...$`

### Quantifiers
Quantifiers define how many of a specified element to look for.
`{n}` The curly brackets with a number indicate the desired quantity of given field.

`+` Indicates one or more.

`*` Indicates zero or more.

`?` Indicates zero or one.

### Grouping Constructs
Grouping constructs allows the ability to check multiple parts of a string.
`(...):(...)` each expression is nested within parentheses 

### Bracket Expressions
`[...]` Square brackets will return any items that match

`{...}` Curly brackets return the exact  
Curly braces are used to specify an exact amount of things to match.

`(...)` 

### Character Classes
Defines a set of characters that will return a match.

### The OR Operator
`|` OR operator will return an item if any condition is met.

### Flags
Flags are placed at the end of a regex statement.
`g` Global search

`i` Case sensitive 

`m` Multi line search

### Character Escapes
`\` Placed before character to escape base functionality defined withing regex.

## Author
Matt Thomsen - current student learning software development.
[GitHub](https://github.com/mthomsn)