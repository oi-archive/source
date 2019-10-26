
# Content

Freddy practices various kinds of alternative medicine, such as homeopathy. This practice is based on the belief that successively diluting some substances in water or alcohol while shaking them thoroughly produces remedies for many diseases.

This year, Freddy's vegetables appear to have caught some disease and he decided to experiment a little bit and investigate whether homeopathy works for vegetables too. As Freddy is also a big fan of mathematics, he does not strictly insist that the substances have small concentrations,but he instead requires the concentrations to be reciprocals of integers ($\frac{1}{n}$). In experiments,some of the vegetables really got much better.

Seeing Freddy's successes, a fellow gardener also wants to try one of these potions and asks fora flask. Freddy has one flask of the potion in concentration $\frac{1}{n}$ and does not want to give it all out. Your task is to find out in how many ways the potion can be split into two flasks and diluted so that the resulting potions both have the same volume as the original one and the resulting concentrations also are reciprocals of integers -- we do not want to end up with useless fluid, do we?

# Standard Input

Each line of the input describes one test case. The line contains the expression `1/n` representing the original concentration. You are guaranteed that $1\leq n\leq 10,000$. There are no spaces on the line.

# Standard Output

For each test case, output a single line with the total number of distinct pairs $\{x, y\}$ of positive integers satisfying $\frac{1}{x} + \frac{1}{y} = \frac{1}{n}$. Pairs differing only in the order of the two numbers are not considered different.

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
<tr><td>1/2
1/4
1/1
1/5000</td><td>2
3
1
32</td></tr></table>


# Constraints



# Note

Inspired by Project Euler Problem 108

# Source


