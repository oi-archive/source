
# Content

Alice and Bob like playing games. On the first day, they randomly get two different integers from ${1, 2, \cdots, N}$, which means each pair of different integers have the same probility to be chosen. 
We call the smaller one $x$, and the larger one $y$. 
$x$ and $y$ keep unchanged all the time. 
On each of the following days, Alice will choose an integer $d\_x$ from ${0, 1, \cdots, x}$ and Bob will choose an integer $d\_y$ from ${0, 1, \cdots, y}$ simultaneously. 
After then, Alice will get a score $S\_x$ of that day, which is either $x+d\_x$ or $x-d\_x$ with equal probability. 
And similarly, Bob will get a score $S\_y$, which is either $y+d\_y$ or $y-d\_y$ with equal probability. 
If $S\_x$ is no less than $S\_y$, Alice will be the winner of that day. 
Otherwise Bob is.

The strategy of a player on a specific day is the way of choosing $d\_x$ or $d\_y$ on that day. 
On the second day, Alice's strategy is to randomly choose $d\_x$ from ${0, 1, \cdots, x}$. 
And Bob's strategy is to randomly choose $d\_y$ from ${0, 1, \cdots, y}$. 
We also know both players' strategies on the $K\_{th}$ ($K > 2$) day.  

If $K$ is odd, Bob's strategy keeps the same as the previous day, which means different $d\_ys$ have the same probabilities with the previous day to be chosen by Bob. However, Alice's strategy changes. She knows Bob's strategy on this day and she will choose a $d\_x$ from ${0, 1, \cdots, x}$ to maximize her winning probability. 
If there are several $d\_xes$ leading to her maximum winning probability, her strategy is to randomly choose one.


If $K$ is even, Alice will do what Bob do and Bob will do what Alice do when $K$ is odd, which means Alice's strategy keeps the same as the previous day and Bob's strategy is to choose a $d\_y$ from ${0, 1, \cdots, y}$ to maximize his winning probability. 
Similarly, if there are several $d\_ys$ leading to Bob's maximum winning probability, his strategy is to randomly choose one.

You are given an int $N$ and an int $K$. Answer Alice's winning probability on the $K\_{th}$ day.

# Standard Input

The input contains $2$ integers $N, K$ ($2\leq N, K\leq 10^6$), as mentioned above.

# Standard Output

Output Alice's winning probability on the $K\_{th}$ day, rounded to $4$ digits after decimal point.

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
<tr><td>2 2</td><td>0.3750</td></tr><tr><td>2 3</td><td>0.4167</td></tr><tr><td>99999 99</td><td>0.2500</td></tr></table>


# Constraints



# Note

Alice knows Bob's strategy on a specific day means that Alice knows the probabilities of different $d\_ys$ to be chosen by Bob, but she may not know which $d\_y$ Bob will choose on that day, and vice versa.

When you calculate Alice's winning probability on the $K\_{th}$ day, $x$ and $y$ haven't been chosen yet.

# Source


