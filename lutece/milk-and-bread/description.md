
# Content

XiaoA and XiaoB are eating breakfast and they are brothers. Strangely, XiaoA has only some kinds of milk while XiaoB has only some kinds of bread originally. They decide to share their breakfast together.As we all know, bread with milk leads to the best taste.
 
XiaoA has $N$ kinds of milk, and XiaoB has $M$ kinds of bread.Based on their preferences, each milk has a enjoyed value $X\_i$, and each bread has a enjoyed value $Y\_i$. Because of hating some kinds of these, $X\_i$ or $Y\_i$ may be negative.

What's more, they should enjoy their milk and bread until there is nothing according to the rules below:

When both of milk and bread left, they choose one kind of milk and one kind of bread to make a pair and enjoy it. They will get the enjoyed value $(X\_i + Y\_j)^2$ for this pair.

And, if there is some milk left only, they will get the enjoyed value $X\_i^2$ for the $i\_{th}$ kind of milk.

Also, if there is for some left bread only, the enjoyed value is $Y\_j^2$ for the $j\_{th}$ kind of bread.

Now they ask you to calculate the maximum sum of the enjoyed value they will get.

# Standard Input

The first line of the input is the number of test cases $T$($1\leq T\leq 10$).

For each case, in the first line there are two integers $N$ , $M$($0\leq N, M\leq 1000$), the number of kinds of milk and bread.The second line has $N$ integers $X\_i$($-100\leq X\_i\leq 100$), the third line has $M$ integers $Y\_i$($-100\leq Y\_i\leq 100$).

# Standard Output

For each test case, output one line. First, output `Case #C: `, where $C$ is the number of test case, from $1$ to $T$. Then,output the maximum sum of the enjoyed value they will get for this case.

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
2 2
1 2
3 4
3 1
2 4 5
7</td><td>Case #1: 52
Case #2: 164</td></tr></table>


# Constraints



# Note

For the second case, firstly they choose the pair of the $3\_{rd}$ milk and the $1\_{st}$ bread get enjoyed value $(5 + 7)^2 = 144$, then they eat the $1\_{st}$ and $2\_{nd}$ milk get $2^2 + 4^2 = 20$, so the total enjoyed value is $164$.

# Source


