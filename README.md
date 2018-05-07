# compilers
Graphics compiler assignment.

1. Lexer (input is source code): performs lexical analysis
- Knows valid keywords, literal formats, and identifier formats.
- It does not interpret anything; it only looks for invalid code.
2. Syntactic analyzer: structure, grammar of code
- The lexer's token list is given to the syntactic analyzer, which determines if the order makes sense
3. Semantic analyzer: meaning (e.g. types)
4. Optimizer (optional)
5. Code generator: receives output of semantic analyzer and generates an executable or image (or multiple images).
