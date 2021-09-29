# Week 3 Paper

By Chris Blount

9/29/2021

## The WHERE clause

### Equality Comparisons
Using `=`

Example: 
` WHERE amount = 99.99;`

Equality conditions equate one expression to another.

### Inequality Comparisons
Using `<>` or `!=`

Examples: 
`WHERE amount <> 100;`
`WHERE amount != 100;`

Ineqality conditions assert that two expressions are not equal.

### Range Comparisons
Using `>`, `>=`, `<`, `<=`, and `BETWEEN`

Examples: 
`WHERE amount < 100;` 
`WHERE amount BETWEEN 90 AND 100;`

With range conditions you can check whether an expression falls within a certain range.
(For the `BETWEEN` operator, you must specify the lower limit first.)

### Lookup Operators
Using `IN`, `NOT IN`, and `LIKE`

Examples: 
`WHERE rating IN ('G', 'PG');`
`WHERE rating NOT IN ('PG-13','R', 'NC-17');`
`WHERE last_name LIKE '__O%T';`

For the `IN` operator, you can write a single condition regardless of how many expressions are in the set.
For `NOT IN`, it helps when you want to find expressions that do not exist within the set.
For the `LIKE` operator in the example above, it compares `last_name` to a string with `__` (each underscore represents a wildcard for one character), `O` (The letter 'O' in the third position), `%` (Any number of characters, including 0), and ending with the letter `T`. In this case, my last name, Blount, would return in the result set.

#### Reference:
*Learning SQL, 3rd Edition* - By Alan Beaulieu