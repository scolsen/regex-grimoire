# Code Arcanum

Regex formulae for matching common patterns in programming languages.

## Top-level Bracket Match

**Description**: This formula matches a target string and continues matching all characters until
it encounters a line containing only a right bracket (}) preceded by no indentation.

```regex
TARGET.*(^[^}])*(^})?\n
```

[vim-script](regexes/code/top-level-bracket.regex)

---

## If-block

**Description**: Matches if and else blocks.

```regex
(if|else)([^}]|\n)*}(\s|\n)
```

[vim-script](regexes/code/if-block.vim)
