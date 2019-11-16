
# Content

Today, Alice and Bob decide to go for a tour. Before they start, they find that they have to take a lot of things and neither of them wants to do it. So they plan to play a game and the loser takes things. The game as followings:
* **First step** : they write down $n$ integers together. The n integers form a sequence $S$.
* **Second step** : Alice writes down an integer $A$($1\leq A\leq n$）, and Bob writes down an integer $B$($1\leq B\leq n$)
* **Third step** : Alice randomly choose a consecutive subsequece from $S$. Any subsequence containing at least $A$ numbers could be chosen. Name the $A\_{th}$ smallest number of this subsequence as $SA$. Bob does the same thing and the $B\_{th}$ smallest number of his subsequence is named $SB$.

Alice wins the game if $SA$ is larger than $SB$. Bob wins if $SB$ is larger. If $SA$ equals $SB$, Alice and Bob would toss a coin to decide who wins. In this case, the probability for each of them to win is $0.5$.

Now, they have written down $n$ integers. Alice gets the number $A$ and Bob gets the number $B$. Alice wonders the probability for him to win the game.

# Standard Input

There are multiple test cases. The first line of the input will be an integer $T$ ($T \leq 10$) indicating the number of test cases.

For each case, the first line is an integer $N$ ($1 \leq N \leq 3000$) - the number of integers. The second line contains $N$ integers wrote down in the first step. The absolute value of those integers are all less than $2^{31}$. The third line are two integers $A$ and $B$.

# Standard Output

For each test case, print `Case #t: r` in a single line, in which t is the number of the test case starting from $1$, and $r$ is a single real number (rounded to six decimal place), which represents the win probability of Alice.

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
3
2 2 3
3 2
3
1 2 3
2 1</td><td>Case #1: 0.833333
Case #2: 0.750000</td></tr></table>


# Constraints



# Note

In the first case, the segment Alice chooses is $[1,3]$.The segments Bob may choose are $[1,2]$, $[1,3]$, $[2,3]$ with the same probability of $\frac{1}{3}$ and their second number if sorted are $2,2,3$. So the answer is $\frac{1}{3}+\frac{1}{3}+\frac{1}{3}\times\frac{1}{2}=\frac{5}{6}$.

# Source


