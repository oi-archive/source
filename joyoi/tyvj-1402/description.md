# 

 
 # 题目背景 
<p>NOIP2010提高组复赛第二题</p> 

 
 # 题目描述 
<p>小明过生日的时候，爸爸送给他一副乌龟棋当作礼物。<br />
乌龟棋的棋盘是一行N&nbsp;个格子，每个格子上一个分数（非负整数）。棋盘第1&nbsp;格是唯一<br />
的起点，第N&nbsp;格是终点，游戏要求玩家控制一个乌龟棋子从起点出发走到终点。<br />
1&nbsp;2&nbsp;3&nbsp;4&nbsp;5&nbsp;&hellip;&hellip;&nbsp;N<br />
乌龟棋中M&nbsp;张爬行卡片，分成4&nbsp;种不同的类型（M&nbsp;张卡片中不一定包含所有4&nbsp;种类型<br />
的卡片，见样例），每种类型的卡片上分别标有1、2、3、4&nbsp;四个数字之一，表示使用这种卡<br />
片后，乌龟棋子将向前爬行相应的格子数。游戏中，玩家每次需要从所有的爬行卡片中选择<br />
一张之前没有使用过的爬行卡片，控制乌龟棋子前进相应的格子数，每张卡片只能使用一次。<br />
游戏中，乌龟棋子自动获得起点格子的分数，并且在后续的爬行中每到达一个格子，就得到<br />
该格子相应的分数。玩家最终游戏得分就是乌龟棋子从起点到终点过程中到过的所有格子的<br />
分数总和。<br />
很明显，用不同的爬行卡片使用顺序会使得最终游戏的得分不同，小明想要找到一种卡<br />
片使用顺序使得最终游戏得分最多。<br />
现在，告诉你棋盘上每个格子的分数和所有的爬行卡片，你能告诉小明，他最多能得到<br />
多少分吗？</p> 

 
 # 输入格式 
<p>输入文件的每行中两个数之间用一个空格隔开。<br />
第1&nbsp;行2&nbsp;个正整数N和M，分别表示棋盘格子数和爬行卡片数。<br />
第2&nbsp;行N&nbsp;个非负整数，a1,a2,&hellip;&hellip;,aN，其中ai&nbsp;表示棋盘第i个格子上的分数。<br />
第3&nbsp;行M&nbsp;个整数，b1,b2,&nbsp;&hellip;&hellip;,&nbsp;bM，表示M张爬行卡片上的数字。<br />
输入数据保证到达终点时刚好用光M张爬行卡片</p> 

 
 # 输出格式 
<p>输出只有1&nbsp;行，1&nbsp;个整数，表示小明最多能得到的分数。</p> 

 
 # 提示 
<p>【数据范围】<br />
对于30%的数据有1&nbsp;&le;&nbsp;N&le;&nbsp;30，1&nbsp;&le;M&le;&nbsp;12。<br />
对于50%的数据有1&nbsp;&le;&nbsp;N&le;&nbsp;120，1&nbsp;&le;M&le;&nbsp;50，且4&nbsp;种爬行卡片，每种卡片的张数不会超<br />
过20。<br />
对于100%的数据有1&nbsp;&le;&nbsp;N&le;&nbsp;350，1&nbsp;&le;M&le;&nbsp;120，且4&nbsp;种爬行卡片，每种卡片的张数不会<br />
超过40；0&nbsp;&le;&nbsp;ai&nbsp;&le;&nbsp;100，1&nbsp;&le;&nbsp;i&nbsp;&le;&nbsp;N；1&nbsp;&le;&nbsp;bi&nbsp;&le;&nbsp;4，1&nbsp;&le;&nbsp;i&nbsp;&le;M。</p> 
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
<tr><td>输入样例1
9 5
6 10 14 2 8 8 18 5 17
1 3 1 2 1

输入样例2
13 8
4 96 10 64 55 13 94 53 5 24 89 8 30
1 1 1 1 1 2 4 1</td><td>输出样例1
73

输出样例2
455</td></tr></table>
