# 

 
 # 题目背景 
<p>noip2013day2</p>

<p>&nbsp;</p> 

 
 # 题目描述 
<p>&nbsp;</p>

<p>小&nbsp;B&nbsp;最近迷上了华容道，&nbsp;可是他总是要花很长的时间才能完成一次。于是，他想到用<br />
编程来完成华容道：给定一种局面，&nbsp;华容道是否根本就无法完成，如果能完成，&nbsp;最少需要多少时间。<br />
小&nbsp;B&nbsp;玩的华容道与经典的华容道游戏略有不同，游戏规则是这样的：<br />
1.&nbsp;在一个&nbsp;n*m&nbsp;棋盘上有&nbsp;n*m&nbsp;个格子，其中有且只有一个格子是空白的，其余&nbsp;n*m-1<br />
个格子上每个格子上有一个棋子，&nbsp;每个棋子的大小都是&nbsp;1*1&nbsp;的；<br />
2.&nbsp;有些棋子是固定的，有些棋子则是可以移动的；<br />
3.&nbsp;任何与空白的格子相邻（有公共的边）&nbsp;的格子上的棋子都可以移动到空白格子上。<br />
游戏的目的是把某个指定位置可以活动的棋子移动到目标位置。<br />
给定一个棋盘，游戏可以玩&nbsp;q&nbsp;次，当然，每次棋盘上固定的格子是不会变的，&nbsp;但是棋盘<br />
上空白的格子的初始位置、&nbsp;指定的可移动的棋子的初始位置和目标位置却可能不同。第&nbsp;i&nbsp;次玩的时候，&nbsp;空白的格子在第&nbsp;EXi&nbsp;行第&nbsp;EYi列，指定的可移动棋子的初始位置为第&nbsp;SXi行第&nbsp;SYi列，&nbsp;目标位置为第&nbsp;TXi&nbsp;行第&nbsp;TYi列。<br />
假设小&nbsp;B&nbsp;每秒钟能进行一次移动棋子的操作，&nbsp;而其他操作的时间都可以忽略不计。&nbsp;请<br />
你告诉小&nbsp;B&nbsp;每一次游戏所需要的最少时间，或者告诉他不可能完成游戏。</p> 

 
 # 输入格式 
<p>第一行有&nbsp;3&nbsp;个整数，每两个整数之间用一个空格隔开，依次表示&nbsp;n、&nbsp;m&nbsp;和&nbsp;q；<br />
接下来的&nbsp;n&nbsp;行描述一个&nbsp;n*m&nbsp;的棋盘，每行有&nbsp;m&nbsp;个整数，每两个整数之间用一个空格隔<br />
开，每个整数描述棋盘上一个格子的状态，&nbsp;0&nbsp;表示该格子上的棋子是固定的，&nbsp;1&nbsp;表示该格子<br />
上的棋子可以移动或者该格子是空白的。<br />
接下来的&nbsp;q&nbsp;行，每行包含&nbsp;6&nbsp;个整数依次是&nbsp;EXi、&nbsp;EYi、&nbsp;SXi、&nbsp;SYi、&nbsp;TXi、&nbsp;TYi，&nbsp;每两个整数之间用一个空格隔开，表示每次游戏空白格子的位置，&nbsp;指定棋子的初始位置和目标位置。</p> 

 
 # 输出格式 
<p>输出有&nbsp;q&nbsp;行，每行包含&nbsp;1&nbsp;个整数，表示每次游戏所需要的最少时间，如果某次游戏无法<br />
完成目标则输出&minus;1。</p> 

 
 # 提示 
<p>对于&nbsp;30%的数据，&nbsp;1&nbsp;&le;&nbsp;n,&nbsp;m&nbsp;&le;&nbsp;10，&nbsp;q&nbsp;=&nbsp;1；<br />
对于&nbsp;60%的数据，&nbsp;1&nbsp;&le;&nbsp;n,&nbsp;m&nbsp;&le;&nbsp;30，&nbsp;q&nbsp;&le;&nbsp;10；<br />
对于&nbsp;100%的数据，&nbsp;1&nbsp;&le;&nbsp;n,&nbsp;m&nbsp;&le;&nbsp;30，&nbsp;q&nbsp;&le;&nbsp;500。</p>

<p>by&nbsp;460289052</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>3 4 2
0 1 1 1
0 1 1 0
0 1 0 0
3 2 1 2 2 2
1 2 2 2 3 2</td><td>2
-1</td></tr></table>
