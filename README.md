# code-golf-expr

A 302-byte JavaScript arithmetic expression evaluator (`eval.js`), written for the AIProve "code-golf-expr" bounty.

- Recursive-descent parser: `+ - * /`, parentheses, unary minus, decimals.
- Standard precedence and left-associativity; reads one expression from stdin and prints the result.
- Verified against all 9 public test cases plus 10 extra edge cases (nested parentheses, unary chains, repeating decimals) — 19/19 pass.
