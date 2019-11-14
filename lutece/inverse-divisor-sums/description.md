
# Content

Your friend Odd Even is obsessed with number theory. He likes to learn new operations to perform on numbers, and to spend endless hours applying his newly acquired knowledge to numbers. For instance, last year he learned about Euler's totient function $\phi(n)$, which counts the number of positive integers less than or equal to $n$ that are relatively prime to $n$. Shortly after that, he went on a spree and calculated $\phi(n)$ for all integers $n$ from $1$ up to one million by hand.Recently, he learned that the sum of all divisors of a number $N$ could be calculated by the following formula:

$$sum\ of\ divisors(N)=\prod\_{i=1}^{r}\frac{p\_i^{(a\_i+1)}-1}{p\_i-1} $$

Here, $p\_1^{a\_1}p\_2^{a\_2}\cdots p\_r^{a\_r}$ is the factorization of $N$ into prime factors where each $p\_i$ is different and $a\_i$ is the maximum power of $p\_i$ such that $p\_i^{a\_i}$ that divides $N$.

Odd Even wants to calculate the function in reverse; given a positive integer $N$ he wants to nd all positive integers $M$ having $N$ as its sum of divisors, and he wants them written out nicely in increasing order. You think this will take too long, so you have decided to intervene and offer computer assistance.

Write a computer program that does the following: given a positive integer $N$, output a list of all the integers $M$ having $N$ as its sum of divisors, in increasing order, or inform Odd Even that no such numbers exists.

# Standard Input

The first line of the input consists of a single integer $T$, the number of test cases. The $T$ following lines each contain a single integer $N$.

# Standard Output

For each test case, output all such numbers on one line, in increasing order, with a single space between each number. If no numbers exist, output `none! `(without quotes).

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
<tr><td>4
7
2
126
1524</td><td>4
none!
68 82
704 1083 1523</td></tr></table>


# Constraints



# Note

$0 < N \leq 10^9$

The output can be large. For Java, it is advisable to buer the output using StringBuilder.

# Source


