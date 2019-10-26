
# Content

Name PK is a funny game on the Internet. The game will calculate a person's characteristic according to his name.

Now we're simulating a simple Name PK game. Each person has a parameter `attacking` which represents his ability to attack others.

For a name with length $N$, $name[i]$ is the $i$-th letter of the name.

We define $F(c)$. Suppose $c$ is a lowercase letter, and $F(c)$ is the ordinal rank of $c$ in the alphabet. For example $F($`a`$) = 1$ , $F($`b`$) = 2$, and so on…

![title](/source/lutece/name-pk/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjI4LzIwMTQwMzE4MTMzNDA1MDAxMy5naWY=.gif)

Now you will be given two names, your task is to calculate their attacking ability and tell me who will win.

# Standard Input

The input consists of several test cases. The first line is an integer $T (T \leq 1000)$, indicating the number of test cases. Each test case is on a separate line, including two strings separated by a whitespace, indicating the name of each person.

Each name contains only lowercase letters in English with the length between $1$ and $20$.

# Standard Output

For each case, output two lines. In the first line, please report the attacking ability of each person respectively, remaining the same order as the input. In the second line, output the result of the first person:`1win`, `lose` or `tie`.

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
<tr><td>1
dalong chiara</td><td>14 46
lose</td></tr></table>


# Constraints



# Note



# Source


