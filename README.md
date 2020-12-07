# Regular Expression Tutorial - Matching a Hex Value

Regular expression (Regex) is a set of characters that define a search pattern. 

## Summary

This tutorial will cover Regex used to match Hex values:

`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`



## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping and Capturing](#grouping-and-capturing)
- [Character Classes](#character-classes)

### Anchors

The `^` character matches the beginning of the string

The `$` character matches the end of the string

The `#` character matches a "#" character

### Quantifiers

The `?` character in the Regex match between 0 and 1 of the previous tokens. 

The `{6}` quantifier matches 6 of the next token.

The `|` is an alternation that acts like a boolean or matches the expression before of after the `|`.

The `{3}` matches 3 of the previous token. 

### Grouping and Capturing

Capturing group #1

`([a-f0-9]{6}|[a-f0-9]{3})`

In the Regex, capturing groups may have many tokens together.  

### Character Classes

`[a-f0-9]`

This character set matches `a-f` lower-case letter range and its case sensitive.

The character set also matches `0-9` number range and its also case sensitive.


## References

- [Regex tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)

- [Introduction to Regular Expressions Video](https://www.youtube.com/watch?v=7DG3kCDx53c&feature=youtu.be)

- [Regexr](https://regexr.com/)

- [dferrandizmont/regex-cheatsheet.md](https://gist.github.com/dferrandizmont/f7b3534b9a5b58ebf8a49de2feffdd3e)

## Author

You can visit my GitHub profile to view more on going projects.

GitHub: https://github.com/yalitzab