
# Content

As we know, Bi Luo is a magic boy, he always has some excited questions , now a new question comes.

You are given some excited strings( only including lowercase ),now Bi Luo starts writing letters.Bi Luo will keep writing until one of the given excited strings can match some substrings of his writing string.That's saying if the goal is reached, Bi Luo will immediately stop his writing.

In each time,Bi Luo will choose one letter among 'a' to 'z' with equal probability to write.

What's the excepted length will Bi Luo writing until he reaching the goal?

# Standard Input

First Line is an positive integer $T$ , ( $1 \leq T \leq 70$ ) , represents there are $T$ test cases.

For each test case: 

The first line contains one positive integers $N$.( $1 \leq N\leq 15$ ) . represents there are $N$ excited strings.

The next $N$ lines , each line will contains one excited string $S$. ( $|S| \leq 10$ )

# Standard Output

For tht $i$-$th$ test case , first output Case #i:  ,You can assume the answer can be equal to the irreducible fraction $\frac{P}{Q}$. Print the value of $P*Q^{-1}$ in the prime field of integers modulo $10^9 + 7$. It is guaranteed that this modulo does not divide Q, thus the number to be printed is well-defined.

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
<tr><td>5
1
a
1
ab
1
aa
2
a
aa
1
zhu
</td><td>Case #1: 26
Case #2: 676
Case #3: 702
Case #4: 26
Case #5: 17576
</td></tr></table>


# Constraints



# Note

You can esay to caculate the answer of the fitst sample input in following processing:

$Answer = \lim_{n\rightarrow+\infty} \sum_{i=1}^{n}{i\ast(\frac{25}{26})^{i-1}\ast\frac{1}{26}} =  26$

# Source


