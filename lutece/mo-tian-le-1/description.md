
# Content

有一栋摩天楼共有$n$层楼，每层有$m$个房间，可以把它简单看作一个$n$行$m$列的矩阵。房间从左到右编号为$1$到$m$。由于经费限制，大楼建造时楼梯只有在$1-L$列$\left(1,2,3...,L\right)$和$R-m$列$\left(R, R+1, ..., m\right)$，其中$\left(1 \leq L \leq R \leq m\right)$才有，只有沿着楼梯才能上下楼层，每次往上或往下走一层楼都会花费一个单位时间。在同一层每次朝相邻的房间移动时也需要花费$1$个单位时间。现在欧阳大爷在第$a$层第$b$个房间，由于他有个朋友把自己的外套忘在了第$c$层第$d$个房间，所以欧阳大爷需要去帮他朋友把衣服拿回来，但是欧阳大爷今天仍然是处于$No honor$的状态，所以他希望能以最快的速度把衣服拿回来然后继续为了荣耀而战。你能帮帮欧阳大爷吗？

# Standard Input

​	第一行输入测试数据组数$T\left(1 \leq T \leq 100\right)$

​	输入一行八个整数$n, m, L, R, a, b, c, d$，以空格隔开。所有数的范围都在$\left[1, 1000000\right]$内。

# Standard Output

对每组数据输出一行一个整数表示欧阳大爷最快取得衣服所需时间。

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
5 5 1 5 5 2 4 3</td><td>4</td></tr></table>


# Constraints



# Note

欧阳大爷当前在第5层的第二个房间，它要到第4层的第三个房间，而电梯在$[1,1]$和$[5,5]$列才有，所以欧阳大爷应该选择向左走一个房间，然后花费一个单位时间下到第四层，再向右走两步，总共花费$4$个单位时间

# Source


