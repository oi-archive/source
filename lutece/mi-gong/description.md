
# Content

有一天`QWsin`梦到了一个巨型迷宫，迷宫有$n$个房间，$m$条有向边，一条有向边$(u,v)$表示可以从房间$u$出发走到房间$v$，迷宫的出口是那些无法再往其他任何房间走的房间，到达了出口`QWsin`才能醒来。由于QWsin菜的不清醒，也不知道整个迷宫的样子，他只能`随机`走，他怀疑自己可能会碰到最坏的情况然后在迷宫永远无法醒来。所以他找到了你，一个梦境外的人，在他开始走迷宫之前帮他翻转一些边的方向(注：若一条边翻转之前是$(u,v)$，那么翻转之后变成$(v,u)$)，使得无论他采取何种方法，从哪个点出发，足够长时间之后都能够走到迷宫的出口（你可能会改变出口房间，但无论何时，出口房间都是那些无法再往其他任何房间走的房间）。同时翻转一条边是需要一定时间的，但由于你在梦境外，你可以同时翻转任意多条边，并且QWsin希望你用最短的时间使得迷宫符合之前所述条件。  
如果这是不可能的，请输出`"Sleep forever!"`（不含引号）  
数据保证不会有一条有向边的起点和终点是同一个点。

# Standard Input

第一行两个数$n,m$表示迷宫的房间数和边数$(0\leq n,m\leq 200000)$。  
下面$m$行每行3个数$u,v,w$，表示一条从$u$到$v$的边，翻转这条边需要$w$的时间。$(0\leq w\leq 2 \times 10^9)$$(1\leq u,v\leq n)$。

# Standard Output

如果有可行方案，输出 一行一个数，表示达成目标条件需要的最短时间。  
否则输出一行一个字符串 `"Sleep forever!"`（不含引号）。

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
<tr><td>4 7
1 2 1
2 3 2
3 4 3
4 1 4
1 3 5
1 3 5
4 2 6 </td><td>3</td></tr></table>


# Constraints



# Note

对于所给的样例,将边$(2,3)$和$(3,4)$同时翻转即可。

# Source


