
# Content

An interstellar expedition team has recently discovered on planet Mars some multiplication equations, which are believed to be the proof that Mars has once been the home of some intellectual species. However these equations are incomplete where some digits are missing because of the eroding power of Mars' nature. Here is one example.

![.*](/source/lutece/restore-equations/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNjcvMjAxNDAxMDExMjM2MjgwOTk1LmpwZw==.jpg)

One way to restore this equation is to assume the $3$ missing digits are $3$, $5$, $3$, respectively, obtaining $123$ x $45$ = $5535$, which indicates this equation may indeed be the intellectual output of Mars' ancient habitants, rather than just some random numbers.

There has been hot debate over this, because people aren't sure whether they can restore all the equations discovered on Mars, i.e. restore the missing digits such that the multiplication equation holds. As a programmer in NASA, you are assigned the task of checking if all the equations are restorable.

# Standard Input

The first line is an integer $T$, number of equations to check. Next $T$ lines each contains three non-empty strings $A$, $B$ and $C$, separated by spaces. Each string contains digits(`0`-`9`) and/or asterisks `*` only, where an asterisk stands for a missing digit. No string begins with the digit `0`.

# Standard Output

For each test case, output `Yes`(Quotes for clarity only) on a line if one can replace the asterisks with digits such that afterwards the numbers represented by $A$, $B$ and $C$ satisfy $A$ `*` $B$ = $C$. Otherwise output `No` instead. Note that an asterisk must be replaced with exactly one digit(`0`-`9`) and the resulting numbers $A$, $B$ and $C$ can't start with zeros(See sample input/output for more clarification).

The length of string $A$ and $B$ are at most 3, and the length of $C$ is at most 6.
 
The length of each string is greater than zero.

At least one `*` will be present in each equation.

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
<tr><td>2
12* 45 *5*5
11 11 *121</td><td>Yes
No</td></tr></table>


# Constraints



# Note

The first case is the example in the problem description. In the second case, one would have been able to obtain a legal equation $11$ `*` $11$ = $0121$ if it were not forbidden to replace the starting `*` in C by a zero.

# Source


