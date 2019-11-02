# 

 
 # 题目背景 
JSOI2009第三轮二试 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;小AA和小YY得到了《喜羊羊和灰太狼》的电影票，都很想去观看，但是电影票只<BR>有一张，于是他们用智力游戏决定胜负，赢得游戏的人可以获得电影票。<BR>&nbsp;&nbsp;&nbsp;&nbsp;在N*M的迷宫中有一个棋子，小AA首先任意选择棋子放置的位置。然后，小YY和小AA轮流将棋子移动到相邻的格子里。游戏的规则规定，在一次游戏中，同一个格子不能进入两次，且不能将棋子移动到某些格子中去。当玩家无法继续移动棋子时，游<BR>戏结束，最后一个移动棋子的玩家赢得了游戏。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;例如下图所示的迷宫，迷宫中”.”表示棋子可以经过的格子，而”#”表示棋子不可以经过的格子：&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.##<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;...<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;#.#&nbsp;&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;若小AA将棋子放置在(1,1)，则小&nbsp;AA&nbsp;则无论如何都无法赢得游戏。<BR>&nbsp;&nbsp;&nbsp;&nbsp;而若小AA将棋子放置在(3,2)或(2,3)，则小AA能够赢得游戏。例如，小AA将棋子放置在(3,2)，小YY只能将它移动到(2,2)，此时小AA再将棋子移动到(2,3)，就赢得了游戏。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;小AA和小YY都是绝顶聪明的小朋友，且从不失误。小AA到底能不能赢得这场游戏，从而得到珍贵的电影票呢？&nbsp; 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入数据首先输入两个整数&nbsp;N,M，表示了迷宫的边长。接下来&nbsp;N&nbsp;行，每行&nbsp;M&nbsp;个字符，描述了迷宫。&nbsp; 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;若小&nbsp;AA&nbsp;能够赢得游戏，则输出一行"WIN"，然后输出所有可以赢得游戏的起始位置，按行优先顺序输出，每行一个。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;否则输出一行"LOSE"（不包含引号）。&nbsp; 

 
 # 提示 
对30%的数据，有1&lt;=n,m&lt;=5<BR>对1000%的数据，有1&lt;=n,m&lt;=100 
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
<tr><td>3 3 
.## 
... 
#.#
</td><td>WIN 
2 3 
3 2
</td></tr></table>
