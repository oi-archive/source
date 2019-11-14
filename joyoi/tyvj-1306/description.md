# 

 
 # 题目背景 
兵败NOI2010后，&nbsp;yuan0818被老师请回到了班里学习文化课。但是，机房的魅力依然存在，yuan0818总想方设法回到机房。<BR> 

 
 # 题目描述 
yuan0818只有课间才可以逃向机房,逃向机房的同时yuan0818可以在途经的路程中做一些其余事情。课间只有T个单位时间。我们把学校看成一个N个点M条边构成的网络。每个点都有一个一定的权值Val[i]，每条边都有起点X[i]，结束点Y[i]以及一个一定的消耗单位时间Tim[i]。yuan818的教室在S点，学校的机房在E点。现在，yuan818想在T单位时间内，从S点逃亡到E点，每个点都可重复经过，要求经过所有点的权值和最大。由于yuan0818很忙，只能请到你了。<BR> 

 
 # 输入格式 
第一行五个整数,N,M,T,S,E，分别表示点数，边数，拥有的时间长度，以及教室序号，和机房序号。<BR>以后M行，每行三个整数，第i+1行为X[i],Y[i],Tim[i]分别表示第i条边的起点，终点，以及所消耗的时间。注：每条边都是单向的，即只能从X[i]通向Y[i]，而不能从Y[i]通向X[i]。<BR>最后一行为N个整数，第i个整数Val[i]表示第i点的权值。<BR><BR> 

 
 # 输出格式 
一行，如果在T时间长度内，能够从S点到达E点，则输出最大所有点权值和。否则输出"It's&nbsp;impossible."。<BR> 

 
 # 提示 
【数据规模】<BR>对于30%的数据,N&lt;=100,M&lt;=10000；<BR>对于100%的数据,N&lt;=10000,M&lt;=1000000,T&lt;=100000。<BR><BR> 
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
<tr><td>【输入样例1】
2 2 3 2 1
1 2 3
2 1 5


【输入样例2】
3 3 3 1 3
1 3 2
1 2 1
2 3 2
1 2 3



</td><td>【输出样例1】
It's impossible.

【输出样例2】
6

</td></tr></table>
