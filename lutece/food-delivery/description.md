
# Content

When we are focusing on solving problems, we usually prefer to stay in front of computers rather than go out for lunch. At this time, we may call for food delivery.

Suppose there are $N$ people living in a straight street that is just lies on an $X$-coordinate axis. The $i\_{th}$ person's coordinate is $X\_i$ meters. And in the street there is a take-out restaurant which has coordinates $X$ meters. One day at lunchtime, each person takes an order from the restaurant at the same time. As a worker in the restaurant, you need to start from the restaurant, send food to the $N$ people, and then come back to the restaurant. Your speed is $V-1$ meters per minute.

You know that the $N$ people have different personal characters; therefore they have different feeling on the time their food arrives. Their feelings are measured by Displeasure Index. At the beginning, the Displeasure Index for each person is $0$. When waiting for the food, the $i\_{th}$ person will gain $B\_i$ Displeasure Index per minute.

If one's Displeasure Index goes too high, he will not buy your food any more. So you need to keep the sum of all people's Displeasure Index as low as possible in order to maximize your income. Your task is to find the minimal sum of Displeasure Index.

# Standard Input

The first line of the input is a positive integer $T$ ($T\leq 15$) which is the number of cases that follow. Each case is started with three integers $N$ ($1\leq N\leq 1000$), $V$ ($V > 0$), $X$ ($X\geq 0$ ), then $N$ lines followed. Each line contains two integers $X\_i$ ($X\_i \geq 0$), $B\_i$ ($B\_i \geq 0$), which are described above.

You can safely assume that all numbers in the input and output will be less than $2^{31} - 1$.

# Standard Output

For each test case please output a single number, which is the minimal sum of Displeasure Index. One test case per line.

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
5 1 0
1 1
2 2
3 3
4 4
5 5</td><td>55</td></tr></table>


# Constraints



# Note



# Source


