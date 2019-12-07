
# Content

![pic](/source/lutece/expected-score/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMTEvMjMvZkJaWEhSM1FvVjZMU2VKLmpwZw==.jpg)

Fatdog is playing a game with sequence $a_1 ,a_2,...,a_n$. On each turn, he needs to choose a position $i$ ($1 \le i < n$) uniformly at random, replaces the element $a_i$ with $a_i - a_{i+1}$, and then removes the element $a_{i+1}$ from the sequence. This continues until there is only one element left, which is the score he gets in this round.

Since he will play plenty of rounds with the same sequence, he wants to know the **EXPECTED SCORE** he will get. But he is too poor at math. Could you help him to calculate it?

**EXPECTED SCORE** means the mathematical expectation of the score.

# Standard Input

The first line of input contains a single integer $n$ ($2 \leq n \leq 100$).

The second line of input contains $n$ integers $a_1 ,a_2 ,\ldots ,a_n$ ($1 \leq a_i \leq 100$).

# Standard Output

Print the **EXPECTED SCORE**. The answer should be rounded to 2 decimal places.

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
1 1 1 1</td><td>0.00</td></tr><tr><td>3
1 2 3</td><td>-1.00</td></tr></table>


# Constraints



# Note

In the second test case, the sequence is $\{ 1,2,3 \}$. You have only two ways to operate on the sequence.

1. Firstly, replace $1$ with $-1$ ($1-2=-1$) and delete the second element, so the sequence becomes $\{ -1,3 \}$. Secondly, replace $-1$ with $-4$ ($-1-3=-4$) and delete the second element. So there's only one element $-4$ left. 
2. Firstly, replace $2$ with $-1$ ($2-3=-1$) and delete the second element, so the sequence becomes $\{ 1,-1 \}$. Secondly, replace $1$ with $2$ ($1-(-1)=2$) and delete the second element. So there's only one element $2$ left. 

Since he choose elements at random, the two situation will happen with same probability $\frac{1}{2}$. The mathematical expectation is $(-4+2) \cdot \frac{1}{2}=-1.00$.

Please note that if the answer is $0$, the output should be $0.00$ rather than $-0.00$.

# Source


