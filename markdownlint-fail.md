This file intentionally violates markdownlint rules so the `markdownlint` job fails.
It does NOT start with a top-level heading (H1) which should trigger MD041.
##SubheadingWithoutBlankLine
This heading above has no blank line before it which may trigger MD022.

Unordered list with mixed markers:

- first item
* second item
 - nested with space and dash

AnotherParagraphWithNoBlankLineBeforeHeading
###AnotherHeadingNoSpace

Multiple    spaces	and	tabs	in a line may also trigger style rules.

```
Fenced code with no language info (allowed) but could be flagged depending on rules.
```

> Blockquote without blank line above

End of intentionally bad file.

