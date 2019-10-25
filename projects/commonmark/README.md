# Commonmark
Write a [Commonmark](https://commonmark.org/) implementation for your chosen language. At a bare minimum, your implementation should:

1. Convert a valid Commonmark document to an [AST](https://en.wikipedia.org/wiki/Abstract_syntax_tree).
2. Convert the AST to HTML.

Bonus points for each of the following:

1. Implement support for converting the AST to ReStructuredText (or Textile, or PDF, or whatever else takes your fancy).
2. Implement support for footnotes, which are not part of the official spec. Hint: try adding "extension hooks" to your parser and renderer.