
# Content

`qhqh`正在统计宿舍集训人数以方便安排住宿。众所周知，秦皇家里有一座岛。秦皇得知此事后立马安排人在清水河修了栋楼, "我的阿房宫还蛮大的，你们随便住，训练累了就，直接睡觉，没问题的"。

秦皇的阿房宫已经修好了，同时`qhqh`拿到了暑期集训人员名单（人与人可以区分），会有包括`qhqh`在内的$k$人参加暑期集训。秦皇的楼有$n$层高，每一层有$m$个房间，每个房间都有门牌号，可以住无限人。既然秦皇说大家可以随便住，那么`qhqh`想知道，在每个人都随便住的情况下，有多少概率使得每个房间最后都有人住。

`qhqh`学习容斥定理太累脑袋已经宕机，回到他先前给自己预留的房间先睡了。于是现在轮到你来解决这个问题，请你计算**当前情况下**，最终每间房间均有人入住的概率。

# Standard Input

一组数据。

输入一行三个数n, m, k。

# Standard Output

输出一行一个数。 假设答案为$p / q$, 请输出$p * q ^{-1} mod (1e9 + 7)$, $q ^{-1}$为q在模1e9 + 7意义下的逆元。

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
<tr><td>2 1 2</td><td>500000004</td></tr><tr><td>2 1 3</td><td>750000006</td></tr></table>


# Constraints

$1\leq{nm}\leq1,000,000$

$1\leq{k}\leq1,000,000$

# Note

样例1 : 1 / 2

样例2： 3 / 4

# Source


