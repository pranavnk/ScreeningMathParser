NICE Developers - Simple Mathematical Parser Screening
===================

As part of the interview process, we require all candidates to submit a test. This test is about writing a custom mathematical parser to compute the value of a inputted string.

The parser must implement an order of precedence of left to right, brackets are used to explicitly denote precedence by grouping parts of an expression that should be evaluated first again left to right

The parser must recognise the input string and evaluate the expression.

Rules:

a = '+', b = '-', c = '*', d = '/', e = '(', f = ')'

# Acceptance criteria

```
Input: 3a2c4
Result: 20

Input: 32a2d2
Result: 17

Input: 500a10b66c32
Result: 14208

Input: 3ae4c66fb32
Result: 235

Input: 3c4d2aee2a4c41fc4f
Result: 990

```

# Instructions

* Implement a solution in the language of your choice and _prove_ that it meets the acceptance criteria.
* The supplied solution must compile (if required) and run on Windows 7.
* Submit your solutions on github (preferred) or by emailing a zip file to your agency.

