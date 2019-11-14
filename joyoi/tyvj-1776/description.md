# 

 
 # 题目描述 
windy在有向图中迷路了。<BR>该有向图有&nbsp;N&nbsp;个节点，windy从节点&nbsp;0&nbsp;出发，他必须恰好在&nbsp;T&nbsp;时刻到达节点&nbsp;N-1。<BR>现在给出该有向图，你能告诉windy总共有多少种不同的路径吗？<BR>注意：windy不能在某个节点逗留，且通过某有向边的时间严格为给定的时间。<BR> 

 
 # 输入格式 
第一行包含两个整数，N&nbsp;T。<BR>接下来有&nbsp;N&nbsp;行，每行一个长度为&nbsp;N&nbsp;的字符串。<BR>第i行第j列为'0'表示从节点i到节点j没有边。<BR>为'1'到'9'表示从节点i到节点j需要耗费的时间。<BR> 

 
 # 输出格式 
一个整数，可能的路径数，这个数可能很大，只需输出这个数除以2009的余数。<BR> 

 
 # 提示 
样例1解释：<BR>0-&gt;0-&gt;1<BR><BR><BR>30%的数据，满足&nbsp;2&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;5&nbsp;；&nbsp;1&nbsp;&lt;=&nbsp;T&nbsp;&lt;=&nbsp;30&nbsp;。<BR>100%的数据，满足&nbsp;2&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;10&nbsp;；&nbsp;1&nbsp;&lt;=&nbsp;T&nbsp;&lt;=&nbsp;1000000000&nbsp;。四川SCOI2009一试&nbsp;Day2&nbsp;第三题 
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
<tr><td>样例1：

2 2
11
00

样例2：

5 30
12045
07105
47805
12024
12345
</td><td>样例1：

1

样例2：

852
</td></tr></table>
