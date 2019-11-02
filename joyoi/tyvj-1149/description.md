# 

 
 # 题目背景 
NOIP2009，TSOI大爆发，创造了历史，书写了传奇。于是，在SRC的提议下，大家一起去南湖公园探险。 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;南湖地区的地形错综复杂。这里有茂密的原始森林，有一望无际的湖水，有大自然一切钟灵毓秀的景物。孩子们一旦走散，彼此就再也看不见了，除非彼此选择的道路在前方的某个地方汇合。<BR>&nbsp;&nbsp;&nbsp;&nbsp;在TSOI光环的感召下，大家的审美和价值观趋于一致，对于相同景物感到的愉悦程度可以看做一样的。这种愉悦程度可以在斐波那契奥斯特洛夫斯基参考系（Universal&nbsp;Fibonacci&nbsp;Ostrovsky参考系，以下简称UFO系）下用一个不大于500000的正整数表示出来。而景物都是在道路的交点处出现的。这些道路都是单向的，而且路网中不存在圈。我们从起点开始，无论选择哪条路，都要一直走下去，并且一定能走到终点。<BR>&nbsp;&nbsp;&nbsp;&nbsp;这时，喜欢思考的芥末和擅长分析的大隋与低调的板砖和强悍的Kib找到了实力派的畅牛和博学的DMK，商量着要刁难一下经常打Dota却在NOIP2009中拔得河北省头筹的Zjoe。他们的问题是这样的，假设TSOI小组共有K个人，那么他们在探险中能欣赏到的景物集合的并所包含的愉悦程度的和最大是多少；如果我们想要游览所有的道路交点，那TSOI小组至少要有多少人。<BR>&nbsp;&nbsp;&nbsp;&nbsp;Zjoe很纠结地囧在那里，等待你的帮助。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行是三个数N、M、K，N表示道路交点个数，M表示道路条数，K表示TSOI小组人数。起始点为1号点，终止点为N号点。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第2到M+1行每行为两个整数U、V，表述U到V号交点之间有一条单向道路。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第M+2到M+N+1行每行一个非负整数P，表示该交点有一个愉悦程度为P的景物。如果该点没有景物，则P为0。<BR>&nbsp;&nbsp;&nbsp;&nbsp;数据保证起点和终点没有景物。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;两个数，中间用空格隔开。第一个数是K个人在探险中能欣赏到的景物集合的并包含的愉悦程度的和最大值，第二个数是游览所有的交点需要的最少人数。 

 
 # 提示 
N≤100,M≤2000,K≤100<BR>P≤500000由SRC原创 
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
<tr><td>7 8 2
1 2
1 4
2 3
4 5
4 6
5 3
6 7
3 7
0
2
3
4
5
6
0
</td><td>18 3
</td></tr></table>
