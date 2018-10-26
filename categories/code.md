# Code Arcanum

Regex formulae for matching common patterns in programming languages.

## Top-level Bracket Match

**Description**: This formula matches a target string and continues matching all characters until
it encounters a line containing only a right bracket (}) preceded by no indentation.

```regex
TARGET.*(^[^}])*(^})?\n
```

[source](regexes/top-level-bracket.regex)

---
