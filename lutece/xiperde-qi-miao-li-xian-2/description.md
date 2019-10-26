
# Content

转眼间，已经过了10年。

$Xiper$和日天都以优异的成绩，从UESTC毕业了。

毕业之后，$Xiper$每天勤奋地写代码。然而不知为何，$Xiper$总觉得自己的智商越来越低了。

久而久之，$Xiper$对日天产生了怀疑。经过的一番调查，$Xiper$发现日天竟然在程序里下毒！

日天面对$Xiper$和前来拘留他的潘警察，假意痛哭流涕，并要求$Xiper$亲手给他带上手铐。

然而就在$Xiper$准备给日天带上手铐时，日天微微一笑，竟从背后掏出了一条咸鱼！

 

“我不做人啦，$Xiper$！”

![title](/source/lutece/xiperde-qi-miao-li-xian-2/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTM3OS8yMDE2MDUwODAwMDk1Mjk2ODM0LmpwZw==.jpg)
 

潘警官赶忙掏出光剑，向日天砍去。不料成为咸鱼王的日天已然是刀枪不入，毫发无损。

面对强大的日天，$Xiper$丝毫不慌，他示意潘警官在豪宅外守候，自己只身迎战。

在$Xiper$的智商碾压之下，日天被诱入火海之中。被火焰包围的日天发出一阵阵的惨叫声，怕是药丸。

现在，已经打败了日天的$Xiper$要尽快逃出这间在熊熊燃烧的祖传豪宅。

为了简化问题，我们将房子简化成一个$N$层楼，每层楼对应一个$L$行$R$列的网格图，并用不同的字符表示每个格点的状态。

* $.$ —— 表示该位置为空。

* $x$ —— 表示该位置上有障碍，不能移动。

* $U$ —— 表示上楼的楼梯入口。

* $D$ —— 表示下楼的楼梯入口。

* $X$ —— 表示$Xiper$现在所在的位置。

* $Y$ —— 表示$Xiper$要到达的出口的位置，保证在第一层楼的边界上。


每秒$Xiper$可以向前后左右移动一格，或者从楼梯的入口到对应的出口。$Xiper$不能移动到边界外的地方，也不能移动到障碍上。

保证顶楼没有上楼入口，底层没有下楼入口，每个下楼入口对应的出口只会是上楼入口或者障碍，反之亦然。

一个上楼入口只会对应一个下楼入口，且所在层数相邻，所处的行和列一致，反之亦然。

注意，同一层楼可能存在多个楼梯；当楼梯入口对应的出口被障碍堵住时，$Xiper$就无法到达出口的位置了。

现在$Xiper$想知道，他最少要用多少时间能逃出来？

# Standard Input

第一行三个数字$N$，$L$，$R(1 <= N,L,R <= 50)$，表示豪宅的大小。

接下来从第$1$层开始依次输入；对于每一层，用$L$行个长度为$R$的字符串表示该层的状态。

# Standard Output

如果可以到达，输出一个数$STEP$，表示所需最少的步数。否则输出$“-1”$。

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
<tr><td>1 1 2
XY</td><td>1</td></tr><tr><td>2 2 2
YU
..

XD
xx</td><td>3</td></tr></table>


# Constraints



# Note



# Source


