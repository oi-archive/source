
# Content

清明节是农历二十四节气之一，在仲春与暮春之交，也就是冬至后的$108$天。众所周知，清明节的习俗扫墓和踏青，以此追忆先辈和展望未来。

beap在外念书，不能回家扫墓，但他却十分想去踏青，无奈他被一个简单题困扰，不解决掉就没有心思做出游计划。
于是苦痛的他向你请教。额，如果你不能帮他搞定这题，那beap做鬼也不会放过你的。

问题如下：在一个无向图中，给你图中的一个节点，要你判断图中所有的环是否都包含该顶点。

# Standard Input

多组测试数据

每组测试数据的第一行是三个整数$N,M,S$.（$0<N\leq 10000$, $M<100000$, $0<S\leq N$）

$N$表示图的节点数，$M$表示边数，$S$表示你需要判断的节点.

接下来$M$行

每行有两个整数$a,b$。表示顶点$a$和顶点$b$($0<a,b\leq N$)之间有直接相连的边。

# Standard Output

对于每组输入。如果$S$在所有的环中，输出`I won't let you go`.否则输出`Don’t worry.Be happy`。

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
<tr><td>5 6 1
1 2
1 5
2 5
2 3
2 4
4 5
5 6 2
1 2
1 5
2 5
2 3
2 4
4 5</td><td>Don't worry.Be happy 
I won't let you go</td></tr></table>


# Constraints



# Note



# Source


