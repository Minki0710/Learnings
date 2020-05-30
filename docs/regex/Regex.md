---
layout: page
title: RegEx
permalink: /regex/
---

#Notes about Regex files

**/text/** --> Literal text match

**/text/i** --> adding 'i' ignores case of letters

**/text/g** --> adding 'g' matches the word text as many times as it is in the data

**/te.t/** --> adding wildcard '.' will match with any letter in place of dot eg:tent, text, test

**/[a-z0-9]/** --> adding hyphen '-' creates range and matches all numbers and letters in the range

**/[^aeiou]/** --> adding caret '^' removes text you don't want to match, this example matches all characters that are not a vowel

**/^text/** --> adding caret '^' outside [] will match if the text is at the beginning

**/text$/** --> adding dollar '$'  will match if the text is at the end

**/\s/** --> adding '\s' matches whitespaces

**/\S/** --> adding '\S' matches non-whitespaces


**/[A-Za-z0-9_]+/** === **/\w+/** --> It will match all letters and numbers

**[^0-9]** === **/\D/** --> matches non-numbers
