
# Content

Moose Mod has just learned about the mod operator.Given two positive integers x and y, the mod operator returns the remainder when x is divided by y.For example, 17 mod 5 = 2 because 17 = 3*5 + 2.

Moose Mod has just defined a function that applies a sequence of N mod operators to its input.
Formally, the function looks as follows:
f(x) = (((x mod m[0]) mod m[1]) ... mod m[N-1]).
For example, m = { 10, 3 } corresponds to the function f(x) = (x mod 10) mod 3.
For this function we have f(18) = (18 mod 10) mod 3 = 8 mod 3 = 2.

You are given $m$ integers.You are also given a int $R$.Moose Mod is interested in finding the sum f(1) + f(2) + ... + f(R).Compute and output its value.

# Standard Input

The first line of the input contains two integers $m(1\leq m\leq5000)$ and $R(1\leq R\leq10^9)$,$R$ means the integer describe above and $m$ means the number of mods.

The second line of the input contains $m$ integers.The ith integer $mod_i$ means the ith mod.$(1\leq mod_i\leq 10^9)$

# Standard Output

Print the answer in a single line

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
<tr><td>3 10
5 3 2</td><td>4</td></tr></table>


# Constraints



# Note



# Source


