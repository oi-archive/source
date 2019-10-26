
# Content

Lukas is to hold a presentation on useful mathematical tricks. E.g., to take the square root of a number you just need to remove the first half of the number. To convince his audience he uses the well tested method of proof by example: $\sqrt{25} = 5$ and $\sqrt{5776} = 76$ so the method obviously works. To multiply a number by $X = 2.6$ all you have to do is move the first digit to the end of the number, $135 \times 2.6 = 351$ and $270270 \times 2.6 = 702702$.

Lukas wants to demonstrate that this last method works for any $X$. To do this he will ask his audience for values of $X$ and then show them example multiplications for which the method works. Lukas has noticed that he can not just pick arbitrary numbers for his examples, so now he wants your help. Can you write a program that given $X$ gives a list of integers for which multiplying by $X$ is equivalent to moving the first digit to the end of the number? Lukas does not like very large numbers so do not list any numbers with more than $8$ digits.

# Standard Input

The input is a single decimal number $X(1 \leq X < 1000)$ with at most $4$ digits after the decimal point.

# Standard Output

Output a list of all positive integers less than $10^8$ for which Lukas' second trick works. Write the numbers in ascending order, one number per line. If the list is empty, output instead `No solution`.

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
<tr><td>2.6</td><td>135
270
135135
270270</td></tr><tr><td>3.1416</td><td>No solution</td></tr></table>


# Constraints



# Note



# Source


