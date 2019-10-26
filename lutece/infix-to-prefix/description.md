
# Content

Jaap wrote a solution to a lab assignment. The task was quite simple: convert an arithmetic expression in infix notation to an expression in Polish (prefix) notation. In infix notation operators are written between the operands (e.g. $12$ + $5$) while prefix notation places operators to the left of their operands (e.g. $+$ $12$ $5$).

This is the syntax of the expression Jaap had to convert:

<table>
<thead>
<tr>
<th style="text-align:left"></th>
<th style="text-align:center"></th>
<th style="text-align:left"></th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left"><em>Expression</em></td>
<td style="text-align:center">::=</td>
<td style="text-align:left"><em>Number</em></td>
</tr>
<tr>
<td style="text-align:left"></td>
<td style="text-align:center">|</td>
<td style="text-align:left"><code>(</code><em>Expression Op Expression</em><code>)</code></td>
</tr>
<tr>
<td style="text-align:left"></td>
<td style="text-align:center">|</td>
<td style="text-align:left"><code>(-</code><em>Expression</em><code>)</code></td>
</tr>
<tr>
<td style="text-align:left"><em>Op</em></td>
<td style="text-align:center">::=</td>
<td style="text-align:left"><code>+</code>|<code>-</code></td>
</tr>
<tr>
<td style="text-align:left"><em>Number</em></td>
<td style="text-align:center">::=</td>
<td style="text-align:left"><em>Digit</em>|<em>Number Digit</em></td>
</tr>
<tr>
<td style="text-align:left"><em>Digit</em></td>
<td style="text-align:center">::=</td>
<td style="text-align:left"><code>0</code>|<code>1</code>|<code>2</code>|<code>3</code>|<code>4</code>|<code>5</code>|<code>6</code>|<code>7</code>|<code>8</code>|<code>9</code></td>
</tr>
</tbody>
</table>

<br/>
If a *Number* has more than one digit, it will not start with a `0`. 

A *Number* has no more than $9$ digits.

At this point we have to admit that the assignment was not very well specified. More specific, the syntax of the resulting expression was not given. So Jaap had to make some decisions himself --- and he made the wrong decisions.  

This was his first mistake: he believed that in prefix notation spaces are superfluous.
This is true in infix notation, as there will always be an operator between two numbers.
In prefix notation, however, numbers must be separated from one another. Omitting spaces in prefix notation, as Jaap did,  gives rise to expressions like `+1234`, which has three different interpretations. (Exercise: draw the three different syntax trees.)

This was Jaap's second mistake: he believed that in prefix notation parentheses are superfluous.
Prefix notation without parentheses is unambiguous only if the arity of the operators is fixed. Ambiguity occurs, for example, in the presence of both a unary and a binary minus. The expression:
`--34`, can be read as `(- (- 3 4))`, evaluating to $1$, or as `(- (- 3) 4)`, evaluating to $-7$, and even as `(- (- 34))`, evaluating to $34$.

We do not ask you to reconstruct Jaap's program. We ask you to find out how ambiguous his output is.

# Standard Input

Each test case consists of a single line with a nonempty string of length $\leq 1000$. The string contains only the characters `+` and `-` and digits `0` through `9`. This string is the output of Jaap's program.

# Standard Output

For each test case, print one line containing two numbers: the smallest and largest value that can be obtained by different interpretations of the input expression.

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>--34
+1234
--09
+111111111111
--0071</td><td>-7 34
46 235
-9 9
222222 111111222
-71 -71</td></tr></table>


# Constraints



# Note



# Source


