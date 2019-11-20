
# Content

You may heard of the Joseph Problem, which comes from a Jewish historian living in $1\_{st}$ century. He and his $40$ comrade soldiers were trapped in a cave, the exit of which was blocked by Romans. They chose suicide over capture and decided that they would form a circle and start killing themselves using a step of three. Josephus stated that by luck or maybe by the hand of God, he and another man remained the last and gave up to the Romans.

Now the problem is much easier: we have $N$ men standing in a line and labeled from $1$ to $N$. In each round, we choose the first man, the $(k+1)\_{th}$ one, the $(2\times k+1)\_{th}$ one and so on, until the end of line. These poor guys will be kicked out of the line and we will execute them immediately (may be head chop, or just shoot them, whatever).And then we start the next round with the remaining guys. The little difference between the Romans and us is, that in our version of story, NO ONE SURVIVES. Your task is to answer some queries, which ask for the $m\_{th}$ one to be executed.

For example, we have $N= 7$ prisoners, and we decided to kill every $k= 2$ people in the queue. At the beginning, it looks like this:
`1 2 3 4 5 6 7`

After the first round, `1 3 5 7` will be executed, and we have
`2 4 6`

And then, we will kill `2 6` in the second round. At last `4` will be executed. So the executedsequence should be
`1 3 5 7 2 6 4`

When $m= 7$ is given in the query for the $7\_{th}$ one kicked out, you just need to answer:
`4`

Easy, right?

Told you.

# Standard Input

Multiple cases, ended by EOF. For every case, there will be three integers $N$ ($1\le N\le 3\times 10^6$),$k$ ($1\le k\le 2\times N$) and $Q$ ($0\le Q\le 10^5$), which respectively indicate the number of prisoners, the step length of killing and the number of queries. The following $Q$ lines describe all the queries, each with an integer $m$ ($1\le m\le N$).

# Standard Output

In each test case, output the answers of all the queries, one in a line.

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
<tr><td>7 2 2
4 7
3 1 1
2</td><td>7
4
2</td></tr></table>


# Constraints



# Note



# Source


