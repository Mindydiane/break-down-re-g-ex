# Find-it-W/-Expressions!

Using regular expressions/regex may be intimidating at first. But once learned are a lot of fun and make it easier to find and revise code.

## Summary

In this tutorial I will be discussing how to find email address with regex(regular expressions)

## Table of Contents


- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components
`[\w.]+@\w+\.(net|com|edu)`
### Greedy Quantifier
`+` Is used to find more than one word as:
`\w+` 
- refer to https://docs.microsoft.com/en-us/dotnet/standard/base-types/quantifiers-in-regular-expressions for more infomation on Quantifiers.

### OR Operator
`|` Is used to symbolize or, in the group it is used to locate this one or etc.: `(net|com|edu)` 

### Character Classes 

 A Character class is anything inside of `[]`
 It is used to include words with .(s) such as `[\w.]`
 * for more information on classes go to:
 https://www.regular-expressions.info/refcharclass.html

### Flags
`Global` and `Multi line` Flags are used as shown on this image:
![image](https://user-images.githubusercontent.com/80286982/131267473-9ed007d9-3438-4559-aca8-8ea73e431dea.png)
* refer to link to test your own expression: https://regex101.com/

### Grouping and Capturing
Is a part of a pattern that can be enclosed in parentheses (...) It is used to capture ` (net|com|edu)`

### Bracket Expressions

A bracket expression (an expression enclosed in square brackets, "[]" ) is an RE that shall match a specific set of single characters, and may match a specific set of multi-character collating elements, based on the non-empty set of list expressions contained in the bracket expression.
*  for more on bracket expressions go to: 
https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/V1_chap09.html
* refer to classes to see how they are used to find email address with regular expressions
- [Character Classes](#character-classes)

### Back-references
#### A million thanks to the coding train aka coding rainbow videos! 
https://www.youtube.com/watch?v=EfJU0Y9WAZ4&t=0s

## Author
Mindy Diane Garza

### Check out my github
https://github.com/mindydiane

### MD Repository link
https://github.com/Mindydiane/break-down-re-g-ex/blob/main/gist-template.md

### Watch walk through video in YouTube
https://youtu.be/8pd-yp2-Bm4

### Or see the same video through screencastify
https://drive.google.com/file/d/1A7pyjEPpgGVuJA26F4PTqb-wmYMdRQKa/view
