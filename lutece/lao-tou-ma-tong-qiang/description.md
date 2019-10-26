
# Content

众所周知，集训队的题目是非常困难的。因此，队员们在挂机AK之后，常常会玩一些游戏。

这次，率先AK的周大爷想出了一个叫老头马桶枪的游戏。

在一个小岛上，有三个物种，一共N个生物生活在一起，他们分别是老头、马桶和枪。他们之间的关系是相互克制的，就像包剪锤一样。老头克制马桶，马桶克制枪，枪又克制老头。

现在，集训队的三名成员，小周，小钱和小胡按次序(周、钱、胡)轮流给出信息，信息有两种形式：

第一种记录方式是$1\ X\ Y$，表示$X$和$Y$是同类。

第二种记录方式是$2\ X\ Y$，表示$X$对$Y$有攻击性行为（$X$克制$Y$）。

当其中一人给出的信息和之前的人给出的信息矛盾时，他便输了，要请吃晚饭。那么，聪明的你能帮助他们看出谁会输呢？(最多只会有一个人输，当多条信息矛盾时，最先给出矛盾信息的人输)

# Standard Input

第一行包含两个整数$N$和$M$，$N$是生物总个数，$M$是三个队员给出的信息总个数。

以下$M$行，每行包含一句队员的话。(依次是小周、小钱、小胡所说的话，三人轮流给出信息)。形式有$1\ x\ y$或$2\ x\ y$。

# Standard Output

输出一行，表示最先给出矛盾信息的人是谁。

若是小周，输出`1`；

若是小钱，输出`2`；

若是小胡，输出`3`；

若没有人给出矛盾信息，输出`-1`。

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
<tr><td>100 7
1 100 1 
2 1 2
2 2 3 
2 3 3 
1 1 3 
2 3 1 
1 5 5</td><td>1</td></tr></table>


# Constraints

$1 \leq N \leq 100000$ 

$1 \le M \le 100000$

$1 \le X, Y \le N$

# Note

For the first sample, the answer is easy to calculate.

# Source


