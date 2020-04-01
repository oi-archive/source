# 

 
 # 题目背景 
由于SSY公布了GY的gf，GY表示非常愤怒，于是他要报复一下SSY。<BR> 

 
 # 题目描述 
SSY被关在了一个N*M的房间内，初始位置为(X,Y)(表示从上往下数第X行，从左往右数第Y列)。SSY发现，只有把房间内所有的开关都打开，他才能逃离这个房间。在每一个单位时间，SSY可以走到上下左右不是墙的地方。当SSY走到开关位置时，他就能不费时间地打开这个开关。开关被打开后，在这个开关的位置会出现一个传送门(起点位置也有一个传送门)，SSY可以通过这个传送门到达任意另外一个被打开的传送门(不消耗时间)。现在，请你编一个程序帮助SSY计算他是否能够逃出这个房间以及打开所有开关所需要的最小时间。 

 
 # 输入格式 
第一行四个整数，分别代表N,M,X,Y。<BR>以后N行，每行M个整数(只可能是0、1、2)，表示这张地图。其中0表示空地，1表示墙，2表示开关。 

 
 # 输出格式 
输出共两行。<BR>第一行，一个字符串。如果SSY能逃出房间，则输出”succeed”否则输出”suissy”。第二行，一个整数。如果SSY能逃出房间，则输出SSY打开所有开关的最小时间，否则输出SSY最多能打开的开关数。 

 
 # 提示 
对于20%的数据&nbsp;N,M&lt;8；<BR>对于50%的数据&nbsp;开关数&lt;=240；<BR>对于100%的数据&nbsp;N,M&lt;128&nbsp;开关数&lt;=1000.<BR><BR> 
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
<tr><td>样例一：
2 3 1 1
0 1 2
0 0 0
样例二：
2 3 1 1
0 1 2
2 1 2
</td><td>样例一：
succeed
4
样例二：
suissy
1
</td></tr></table>
