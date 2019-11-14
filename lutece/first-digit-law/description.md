
# Content

In the probability theory the following paradox called Benford's law is known: "In many lists of random numbers taken from real sources, numbers starting with digit $1$ occur much more often than numbers starting with any other digit" (that's the simplest form of the law).

Having read about it on the book, Fish got intrigued by the statement and wishes to thoroughly explore it. He finds the following similar problem interesting in particular: there are $N$ random variables, the $i\_{th}$ of which can take any integer value from some segment $[L\_i, R\_i]$ (all numbers from this segment are equiprobable). It means that the value of the $i\_{th}$ quantity can be equal to any integer number from a given interval $[L\_i, R\_i]$ with probability $\frac{1}{R\_i - L\_i + 1}$.

Fish wants to know the probability of the event that the first digits of at least $K\%$ of those values will be equal to one. In other words, let us consider some set of fixed values of these random variables and leave only the first digit (the MSD — most significant digit) of each value. Then let's count how many times the digit $1$ is encountered and if it is encountered in at least $K$ per cent of those $N$ values, than such set of values will be called a good one. You have to find the probability that a set of values of the given random variables will be a good one.

# Standard Input

There are multi-cases. The first line of each case contains number $N$ which is the number of random variables ($1\leq  N \leq  1000$). Then follow $N$ lines containing pairs of numbers $L\_i, R\_i$, each of whom is a description of a random variable. It is guaranteed that $1\leq  L\_i \leq  R\_i \leq  10^{18}$.

The last line contains an integer $K$ ($0\leq  K \leq 100$).

All the numbers in the input file are integers.

# Standard Output

For each case print the required probability. Print the fractional number rounded $6$ digits.

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
1 2
50
2
1 2
9 11
50</td><td>0.500000
0.833333</td></tr></table>


# Constraints



# Note



# Source


