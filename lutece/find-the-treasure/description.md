
# Content

Under the guide of CC, flower fairies have successfully passed through the weird world and they left $M$ considerable treasures in it.

Hongshu, an excellent treasure hunter, unexpectedly obtained the treasure map of the world which describes each treasure in detail. The $i\_{th}$ treasure contains a wealth of $B\_i$. To obtain the $i\_{th}$ treasure, Hongshu have to collect $K\_i$ different keys to unlock the treasure box. However, keys needed are very special and collect the $i\_{th}$ key cost him $A\_i$. A key can be used more than once. Now Hongshu is wondering how to make his strategy in order to make his profit maximized.

# Standard Input

The first line of the input is $T$ (no more than $100$), which stands for the number of test cases you need to solve. 

Each test case begins with $N$, $M$ representing the number of keys and treasures. $N$ and $M$ are integers no more than $100$. The next line contains $N$ integers, the $i\_{th}$ integer $A\_i$ ($A\_i \leq 100000$) represents the cost to collect the $i\_{th}$ key. Then follows a line contains $M$ integers, the $i\_{th}$ integer $B\_i$ ($B\_i \leq 100000$) represents the wealth of the $i\_{th}$ treasure. Then $M$ lines followed. Each describes a treasure. Each line begins with an integer $K$ ($K \leq N$), which is the number of different keys you need to unlock the treasure box. Then K integers followed represents the index of each key (index numbered from $1$).

# Standard Output

For each case, print the maximum profit in the first line. Then print the number of keys to collect and the indices of them in ascending order separated by space in the second line. It is guaranteed that the answer is unique.

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
4 4
7 4 2 7
7 9 0 0
1 2
1 4
1 3
1 1</td><td>5
2 2 4</td></tr></table>


# Constraints



# Note



# Source


