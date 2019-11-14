# 

 
 # 题目背景 
小X每天去上学都发现有某MM与其同路，慢慢的小X竟然暗恋上了这个同路的MM。经过多次尾随,小X终于找到了这个MM的家和每天要去的地方。<BR> 

 
 # 题目描述 
他所在的城市可以看成一个N个点，M条边的网络。他告诉你他的家标号X1，他的学校标号Y1，MM的家标号X2以及MM每天所到的标号Y2。在这个城市中，每条边都有Xi，Yi，Di，分别表示这条边起点，终点，路径长度。注：所有边都是无向边，即只能从Xi走向Yi，也可以从Yi走向Xi。小X与MM，都会走最短的路程以节省时间，<BR>他想尽可能长的与MM同路。但他只知道想MM了，算不出来他每天最多可以有多长路径与MM同路。所以，只好来找学OI的你来帮助他。<BR><BR> 

 
 # 输入格式 
第一行六个整数，N，M，X1，Y1，X2，Y2，分别表示点的个数，边的个数，小X的起点和终点，MM的起点和终点。<BR>以后2~M+1行，每行有三个整数Xi,Yi,Di。第i行表示第i-1条边的起点，终点，以及路径长度。<BR><BR> 

 
 # 输出格式 
一行一个整数，为小X最大与MM同路的路程。<BR> 

 
 # 提示 
【样例解释】<BR>小X走1-2-3，MM走2-3。<BR>这样，他们同路在2-3即第2条路径，长度为1。<BR><BR>【数据范围】<BR>对于30%的数据,N&lt;=100；<BR>对于60%的数据,N&lt;=1000；<BR>对于100%的数据,N&lt;=1500,M&lt;=300000<BR> 
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
<tr><td>3 3 1 3 2 3
1 2 2
2 3 1
1 3 4

</td><td>1
</td></tr></table>
