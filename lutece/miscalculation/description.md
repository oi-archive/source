
# Content

$Bob$ is an elementary schoolboy, not so good at mathematics. He found Father’s calculator and tried cheating on his homework using it. His homework was calculating given expressions containing multiplications and additions. Multiplications should be done prior to additions, of course, but the calculator evaluates the expression from left to right, neglecting the operator precedence. So his answers may be the result of either of the following two calculation rules.

* Doing multiplication before addition

* Doing calculation from left to right neglecting the operator precedence

Write a program that tells which of the rules is applied from an expression and his answer.

An expression consists of integers and operators. All the integers have only one digit, from $0$ to $9$. There are two kinds of operators $+$ and $*$, which represent addition and multiplication, respectively.

The following is an example expression.

$1+2*3+4$

Calculating this expression with the multiplication-first rule, the answer is $11$, as in Sample Input $1$. With the left-to-right rule, however, the answer will be $13$ as shown in Sample Input $2$.

There may be cases in which both rules lead to the same result and you cannot tell which of the rules is applied. Moreover, $Bob$ sometimes commits miscalculations. When neither rules would result in $Bob$’s answer, it is clear that he actually did.

# Standard Input

The input consists of a single test case specified with two lines. The first line contains the expression to be calculated. The number of characters of the expression is always odd and less than or equal to $17$. Each of the odd-numbered characters in the expression is a digit from ‘$0$’ to ‘$9$’. Each of the even-numbered characters is an operator ‘$+$’ or ‘$*$’. The second line contains an integer which ranges from $0$ to $999999999$, inclusive. This integer represents $Bob$’s answer for the expression given in the first line.

# Standard Output

Output one of the following four characters:

* $M\   $ When only the multiplication-first rule results $Bob$’s answer.
* $L\   $ When only the left-to-right rule results $Bob$’s answer.
* $U\   $ When both of the rules result $Bob$’s answer.
* $I\   $ When neither of the rules results $Bob$’s answer.

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
<tr><td>1+2*3+4
11</td><td>M</td></tr><tr><td>1+2*3+4
13</td><td>L</td></tr><tr><td>3
3</td><td>U</td></tr><tr><td>1+2*3+4
9</td><td>I</td></tr></table>


# Constraints



# Note



# Source


