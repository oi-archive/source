
# Content

Cao Cao made up a big army and was going to invade the whole South China. Yu Zhou was worried about it. He thought the only way to beat Cao Cao is to have a spy in Cao Cao's army.
But all generals and soldiers of Cao Cao were loyal, it's impossible to convince any of them to betray Cao Cao.

So there is only one way left for Yu Zhou, send someone to fake surrender Cao Cao. Gai Huang was selected for this important mission. However, Cao Cao was not easy to believe others,
so Gai Huang must leak some important information to Cao Cao before surrendering.

Yu Zhou discussed with Gai Huang and worked out $N$ information to be leaked, in happening order. Each of the information was estimated to has $a\_i$ value in Cao Cao's opinion.

Actually, if you leak information with strict increasing value could accelerate making Cao Cao believe you. So Gai Huang decided to leak exact $M$ information with strict increasing
value in happening order. In other words, Gai Huang will not change the order of the $N$ information and just select $M$ of them. Find out how many ways Gai Huang could do this.

# Standard Input

The first line of the input gives the number of test cases, $T$($1\leq 100$). $T$ test cases follow.

Each test case begins with two numbers $N$($1\leq N\leq 10^3$) and $M$($1\leq M\leq N$), indicating the number of information and number of information Gai Huang will select.
Then $N$ numbers in a line, the $i\_{th}$ number $a\_i$($1\leq a\_i\leq 10^9$) indicates the value in Cao Cao's opinion of the $i\_{th}$ information in happening order.

# Standard Output

For each test case, output one line containing `Case #x: y`, where $x$ is the test case number (starting from $1$) and $y$ is the ways Gai Huang can select the information.

The result is too large, and you need to output the result mod by $1000000007$($10^9+7$).

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
3 2
1 2 3
3 2
3 2 1</td><td>Case #1: 3
Case #2: 0</td></tr></table>


# Constraints



# Note

In the first cases, Gai Huang need to leak $2$ information out of $3$. He could leak any $2$ information as all the information value are in increasing order. In the second cases,
Gai Huang has no choice as selecting any $2$ information is not in increasing order.

# Source


