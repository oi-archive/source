
# Content

Diophantus of Alexandria was an Egypt mathematician living in Alexandria. He was one of the first mathematicians to study equations where variables were restricted to integral values. In honor of him, these equations are commonly called Diophantine equations. One of the most famous Diophantine equation is $x\_n + y\_n = z\_n$. Fermat suggested that for $n > 2$, there are no solutions with positive integral values for $x, y$ and $z$. A proof of this theorem (called Fermat’s last theorem) was found only recently by Andrew Wiles.

Consider the following Diophantine equation:

![title](/source/lutece/diophantus/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjc2LzIwMTQwMzE5MDAxMzE3MjQ4MS5naWY=.gif)

Diophantus is interested in the following question: for a given $n$, how many distinct solutions (i. e., solutions satisfying $x \leq y$) does equation $(1)$ have? For example, for $n = 4$, there are exactly three distinct solutions:

![title](/source/lutece/diophantus/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjc2LzIwMTQwMzE5MDAxMzQ4NzY4Mi5naWY=.gif)

Clearly, enumerating these solutions can become tedious for bigger values of $n$. Can you help Diophantus compute the number of distinct solutions for big values of $n$ quickly?

# Standard Input

The first line contains the number of scenarios. Each scenario consists of one line containing a single number $n (1 \leq n \leq 10^9)$.

# Standard Output

The output for every scenario begins with a line containing `Scenario #i:`, where $i$ is the number of the scenario starting at $1$. Next, print a single line with the number of distinct solutions of equation $(1)$ for the given value of $n$. Terminate each scenario with a blank line.

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
4
1260</td><td>Scenario #1:
3

Scenario #2:
113</td></tr></table>


# Constraints



# Note

The data used in this problem is unofficial data prepared by OrangeWall. So any mistake here does not imply mistake in the offcial judge data.

# Source


