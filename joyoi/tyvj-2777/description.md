# 

 
 # 题目描述 
<p>
我们经常听到说计算机是一项伟大的发明。但事实上，它只是一个工具，是一台能帮助人类高效率地处理许多任务的机器。<br>一台普通计算机有一个中央处理器(CPU:Central Processing Unit),CPU有时是空闲的，有时正在处理一项任务。任务的到来使随机的，并且在完成之前被存放在内存中。CPU处理任务是按照某一策略来进行的。正在处理的任务可以被中止并保存起来，这样CPU可以去处理其他任务。<br>每个任务都有到达时间和处理时间。假设我们知道所有任务的安排表，请你写一个程序通过适当的分配和中止使得所有任务完成时刻的总和最小。<br>例如，假设现在有两个任务要完成。任务1的到达时间是1，需要4个单位时间来处理。任务2到达时刻和处理时间分别是3，1。下图给出了三种处理方法：<br><br><center><img src="/source/joyoi/tyvj-2777/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjc3Ny9wcm9ibGVtc19pbWFnZXMvMzI5Ny9wZy5naWY=.gif"></img></center><br><br><center><img src="/source/joyoi/tyvj-2777/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjc3Ny9wcm9ibGVtc19pbWFnZXMvMzI5Ny9wZzIuZ2lm.gif"></img></center><br><br><center><img src="/source/joyoi/tyvj-2777/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjc3Ny9wcm9ibGVtc19pbWFnZXMvMzI5Ny9wZzMuZ2lm.gif"></img></center><br>图1完成时刻和为4+6=10,图2,3都是5+6=11。图1的处理方法是最优的。<br>注意所有任务的到达时刻、被中止时刻和完成时间都是整数。<br></p> 

 
 # 输入格式 
<p>
第一行是一个整数n(1<=n<=50000)表示一共有多少任务。接下来n行每行有两个整数：ri和pi(1<=ri<=109,,1<=pi<=10000),表示人任务i的到达时刻和处理所需时间。</p> 

 
 # 输出格式 
<p>
输出整数表示最小的完成时刻的总和。</p> 
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
<tr><td>2
1 4
3 1
</td><td>10</td></tr></table>
