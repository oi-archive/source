# 

 
 # 题目描述 
<p>
格斗俱乐部是格斗爱好者的一个组织，在这里，格斗者们能通过与别的成员进行格斗来释放自己的压力与轻松自己的情绪。最近俱乐部举行了一场比赛，该比赛有N位选手参加，他们将围成一个圆圈，每一场比赛圈内任意的两位相邻的选手均可进行相互的格斗，胜利者将留在圈内进入下轮比赛而失败者则直接被送往医院（没有平局）。比赛是残酷的，最后圈内将只剩下一位选手，他将是总冠军。

 
 # 输入格式 
<p>
数据第一行是一个整数N，(1 <= N <= 40)，表示比赛的选手数量。接下来给出一个 N*N 的“0”、“1”矩阵A（行内用空格隔开），第i行第j列为 1表示选手i能战胜选手j，否则选手j能战胜选手i。你可以假定Aij与Aji（i≠j）均是不同的且Aii=0。

 
 # 输出格式 
<p>
输出包含N行，每行为一个整数“0”或“1”，“1”表示第i号选手有可能成为冠军，“0”表示不可能。</p> 
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
<tr><td>3
0 1 1
0 0 1
0 0 0
</td><td>1
0
0