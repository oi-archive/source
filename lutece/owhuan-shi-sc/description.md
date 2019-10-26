
# Content

UESTC的暴雪集训队有$N$条咸鱼

每条咸鱼都会打OW（守望屁股）和SC（盲人星际），但是每个人对于两个游戏的喜好程度不一样

对于第$i$条咸鱼，它打OW会得到$A\_i$的喜悦值，它打SC会得到$B\_i$的喜悦值

然后这$N$条咸鱼之间有$M$对朋友关系

但是很不幸的是，朋友关系并不传递

对于一对朋友$i,j$，如果它们都打OW，那么它们会共同分享$X(i,j)$的喜悦值

对于一对朋友$i,j$，如果它们都打SC，那么它们会共同分享$Y(i,j)$的喜悦值

现在请你来安排方案，使得总喜悦值最大，输出最大值

# Standard Input

一个整数$N$，表示咸鱼数，$1\le N \le 1000$

第二行一个整数$M$，表示关系数，$0\le M \le min(3000, N * (N - 1) / 2)$

接下来$M$行，表示关系，每行$u,v,x,y$，表示$u$和$v$是朋友，一起打OW的共享喜悦值是$x$，一起打SC的共享喜悦值是$y$

接下来一行有$N$个正整数，表示数组$A$

最后的一行有$N$个正整数，表示数组$B$

$0\le A\_i, B\_i, x, y \le 1000$

# Standard Output

输出最大的总喜悦值

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
1
1 2 1 2
4 4
1 2</td><td>9</td></tr></table>


# Constraints



# Note

样例里面柱爷会选择玩逃兵76，银牌爷会选择玩滑稽dj，（然后被干成马），这样他们能获得$⑨$点机油值

# Source


