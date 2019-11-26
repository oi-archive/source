
# Content

We all know that in Mathematics, if $A>B$ and $B>C$, then we can easily get $A>C$, however, in actual contest, things may not turn out to be as easy as that!

For example, in the **Allelujah Championship of Mathematics** (ACM), there are three players left, the contest is a knock-out type. So they need $2$ more matches to determine the final champion!

From the previous practice results we know that gongbaoa always beats kennethsnow, and kennethsnow will get a win on elfness for sure. However, when gongbaoa meets elfness, since elfness is a beautiful girl, gongbaoa always loses to her for some strange reasons. This can lead to a serious problem: Everyone has the chance to win the Competition! 

If you are still confused, there's an easier explanation: If in the first round kennethsnow beat elfness, he will lose to gongbaoa, and the latter will be the champion. If in the first round gongbaoa beat kennethsnow, he will lose to elfness, and elfness will be the winner, still, kennethsnow has a chance to win, as long as gongbaoa loses to elfness in the first round. We call those three guys "potential champions". 

Now, if there are $N$ people competing in ACM, of course we need at most $N-1$ matches to ditermine the champion. And for each round, we randomly select two players to have a match, the winner will get to the next round. We have some information about those players, that is to say, we can know some of the match result for sure. 

To simplify the problem, we set a special rule to determion the champion for each match:

1. If we have the direct information of that match, then the champion is determined for sure.
2. If we don't have the direct information, but we can find a path from $A$ to $B$, that is to say, if $A$ can beat $A\_2$, and $A\_2$ can beat $A\_3$..., finally, there is a $A\_k$ who can beat $B$, then we say there is a path from $A$ to $B$. So, if there exists a path from $A$ to $B$, but not a path from $B$ to $A$, then we set $A$ as the champion.
3. In other cases, any one of them has the chance to win.

Your task is simple: given the match information we currently have, please determine the number of "potential champions"

# Standard Input

The first line of the input is $T$ (no more than $100$), which stands for the number of test cases you need to solve. Then $T$ data sets follow.

For each dataset, the first line contains two numbers $n$ and $m$, which stands for the number of nodes and edges. ($0 < n \leq 100000$, $0 \leq m \leq 100000$) Then $m$ lines follow, each line with $2$ numbers $u$ and $v$, ($0\leq u,v < n$, $u\neq v$) means that if $u$ meet $v$ in the match, then $u$ will win for sure.

# Standard Output

For each dataset, For each test case, first output `Case #C: `, where $C$ is the number of test case, from $1$ to $T$.Then print out a single number $n$ which is the number of "potential champions", for the next line you should output exact $n$ numbers which are the id of those people in sorted order, the numbers are seperated with a single space.

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
<tr><td>3
3 3
0 1
1 2
2 0
3 0
2 1
0 1</td><td>Case #1: 3
0 1 2
Case #2: 3
0 1 2
Case #3: 1
0</td></tr></table>


# Constraints



# Note

1. In the second case, since we have no information of those players, according to the rule above, all of them will be the champion, so the answer is $3$.
2. Don't ask me what does "Allelujah Championship of Mathematics" mean! I don't know either!

# Source


