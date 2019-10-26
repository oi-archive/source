
# Content

In the year of $200$, two generals whose names are Cao Cao and Shao Yuan are fighting in Guandu. The battle of Guandu was a great battle and the two armies were fighting
at $M$ different battlefields whose numbers were $1$ to $M$. There were also $N$ villages nearby numbered from $1$ to $N$. Cao Cao could train some warriors from those villages
to strengthen his military. For village $i$, Cao Cao could only call for some number of warriors join the battlefield $x\_i$. However, Shao Yuan's power was extremely strong at
that time. So in order to protect themselves, village $i$ would also send equal number of warriors to battlefield $y\_i$ and join the Yuan Shao's Army. If Cao Cao had called for
one warrior from village $i$, he would have to pay $c\_i$ units of money for the village. There was no need for Cao Cao to pay for the warriors who would join Shao Yuan's army.
At the beginning, there were no warriors of both sides in every battlefield.

As one of greatest strategist at that time, Cao Cao was considering how to beat Shao Yuan. As we can image, the battlefields would have different level of importance $w\_i$.
Some of the battlefields with $w\_i = 2$ were very important, so Cao Cao had to guarantee that in these battlefields, the number of his warriors was greater than Shao Yuan's.
And some of the battlefields with $w\_i = 1$ were not as important as before, so Cao Cao had to make sure that the number of his warriors was greater or equal to Shao Yuan's.
The other battlefields with $w\_i = 0$ had no importance, so there were no restriction about the number of warriors in those battlefields. Now, given such conditions,
could you help Cao Cao find the least number of money he had to pay to win the battlefield?

# Standard Input

The first line of the input gives the number of test cases, $T$($1\leq T\leq 30$). $T$ test cases follow.

Each test case begins with two integers $N$ and $M$($1\leq N, M\leq 10^5$) in one line.

The second line contains $N$ integers separated by blanks. The $i\_{th}$ integer $x\_i$($1\leq x\_i\leq M$) means Cao Cao could call for warriors from village $i$ to battlefield $x\_i$.

The third line also contains $N$ integers separated by blanks. The $i\_{th}$ integer $y\_i$($1\leq y\_i\leq M$) means if Cao Cao called some number of warriors from village $i$,
there would be the same number of warriors join Shao Yuan's army and fight in battlefield $y\_i$.

The next line contains $N$ integers separated by blanks. The $i\_{th}$ integer $c_i$($0\leq c\_i\leq 10^5$) means the number of money Cao Cao had to pay for each warrior from
this village.

The last line contains $M$ integers separated by blanks. The $i\_{th}$ number $w\_i$($w\_i\in \\{0, 1, 2\\}$) means the importance level of $i\_{th}$ battlefield.

# Standard Output

For each test case, output one line containing `Case #x: y`, where $x$ is the test case number (starting from $1$) and $y$ is the least amount of money that Cao Cao had
to pay for all the warriors to win the battle. If he couldn't win, $y = -1$.

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
2 3
2 3
1 1
1 1
0 1 2
1 1
1
1
1
2</td><td>Case #1: 1
Case #2: -1</td></tr></table>


# Constraints



# Note



# Source


