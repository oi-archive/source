
# Content

![](/source/lutece/bei-ji-de-hou-zi/img/aHR0cHM6Ly9zczAuYmRzdGF0aWMuY29tLzcwY0Z1SFNoX1ExWW54R2twb1dLMUhGNmhoeS9pdC91PTIyNjM0NTIzMDAsMzc4NTU5NDM5MCZmbT0yNyZncD0wLmpwZw==.jpg)

也许你不知道，在北极也有猴子，我们叫它们北极猴。北极猴们在北极一共有n个聚落，不妨叫它们1,2，…n号聚落；它们之间有m条**双向**道路(这意味着如果一条路从1号聚落到2号聚落，那么你可以过这条路从2号聚落到1号聚落)，每条道路连接2个聚落，且拥有不同的长度。

不过，由于北极没有多少土地，所以它们之间经常为了争夺领土而开战，由此也产生了许多矛盾。这一天，猴子聚落s和猴子聚落t之间便宣布势不两立，北极联合猴协会调解无效后，它们要求摧毁m条道路中的一些路，使得这两个聚落不能互相到达。

猴子们觉得在北极摧毁道路是一件非常费力的事情，于是它们不希望摧毁两条以上的道路。不过，道路长短不一，所以猴子们希望摧毁的道路的总长度最小。

猴子毕竟只是猴子，它们不会算数，所以它们把选择道路的任务交给了你。

# Standard Input

第一行两个整数n,m(2≤ n ≤ 5000, 3 ≤ m ≤5000) 表示北极猴聚落的数量和双向道路的数量。

第二行两个不同的整数s,t ( 1≤ s,t ≤ n),表示势不两立的猴子聚落的编号。

接下来m行，每行三个整数x,y,z,( 1≤ x,y ≤ n,  1 ≤ z ≤ $10^{9}$  )表示从x到y有一条距离为z的双向道路。

# Standard Output

输出一个或两个整数，表示你选择的道路的编号。如果没有需要删除的道路，则输出0.

道路的编号按照输入顺序，记为1,2,…m.

如果输出两个整数，则它们应该不同，且较小的数在前。

如果有多组满足条件的答案，则输出字典序最小的答案。这意味着，如果答案是a,b,则优先选择a最小的答案；若还是有多组，选择b最小的答案。

如果找不到答案，输出-1.

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
<tr><td>5 4
1 5
1 2 3
2 3 1
3 4 4
4 5 2</td><td>2</td></tr><tr><td>5 3
1 5
1 2 3
2 3 1
4 5 2</td><td>0</td></tr><tr><td>6 7
1 6
2 1 6
2 3 5
3 4 9
4 6 4
4 6 5
4 5 1
3 1 3</td><td>2 7</td></tr></table>


# Constraints



# Note

样例1：第二条道路的长度为1，且摧毁之后1号聚落和5号聚落不能互相到达。

# Source


