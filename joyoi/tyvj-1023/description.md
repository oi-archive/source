# 

 
 # 题目背景 
USACO<BR> 

 
 # 题目描述 
奶牛Bessie有N分钟时间跑步，每分钟她可以跑步或者休息。若她在第i分钟跑步，可以跑出D_i米，同时疲倦程度增加1（初始为0）。若她在第i分钟休息，则疲倦程度减少1。无论何时，疲倦程度都不能超过M。另外，一旦她开始休息，只有当疲惫程度减为0时才能重新开始跑步。在第N分钟后，她的疲倦程度必须为0。<BR> 

 
 # 输入格式 
第一行，两个整数，代表N和M。<BR>接下来N行，每行一个整数，代表D_i。 

 
 # 输出格式 
Bessie想知道，她最多能跑的距离。<BR> 

 
 # 提示 
N&nbsp;&lt;=&nbsp;2000&nbsp;,&nbsp;M&nbsp;&lt;=&nbsp;500&nbsp;,&nbsp;D_i&nbsp;&lt;=&nbsp;1000<BR>Vivian&nbsp;Snow<BR>广东汕头聿怀初级中学NOIp第一次训练用题 
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
<tr><td>5 2
5
3
4
2
10
</td><td>9
</td></tr></table>
