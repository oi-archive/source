# 

 
 # 题目描述 
windy有一块矩形土地，被分为&nbsp;N*M&nbsp;块&nbsp;1*1&nbsp;的小格子。<BR>有的格子含有障碍物。<BR>如果从格子A可以走到格子B，那么两个格子的距离就为两个格子中心的欧几里德距离。<BR>如果从格子A不可以走到格子B，就没有距离。<BR>如果格子X和格子Y有公共边，并且X和Y均不含有障碍物，就可以从X走到Y。<BR>如果windy可以移走T块障碍物，求所有格子间的最大距离。<BR>保证移走T块障碍物以后，至少有一个格子不含有障碍物。<BR> 

 
 # 输入格式 
第一行包含三个整数，N&nbsp;M&nbsp;T。<BR>接下来有N行，每行一个长度为M的字符串，'0'表示空格子，'1'表示该格子含有障碍物。<BR> 

 
 # 输出格式 
一个浮点数，保留6位小数。<BR> 

 
 # 提示 
20%的数据，满足&nbsp;1&nbsp;&lt;=&nbsp;N,M&nbsp;&lt;=&nbsp;30&nbsp;；&nbsp;0&nbsp;&lt;=&nbsp;T&nbsp;&lt;=&nbsp;0&nbsp;。<BR>40%的数据，满足&nbsp;1&nbsp;&lt;=&nbsp;N,M&nbsp;&lt;=&nbsp;30&nbsp;；&nbsp;0&nbsp;&lt;=&nbsp;T&nbsp;&lt;=&nbsp;2&nbsp;。<BR>100%的数据，满足&nbsp;1&nbsp;&lt;=&nbsp;N,M&nbsp;&lt;=&nbsp;30&nbsp;；&nbsp;0&nbsp;&lt;=&nbsp;T&nbsp;&lt;=&nbsp;30&nbsp;。四川SCOI2009一试&nbsp;Day2&nbsp;第一题 
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

3 3 0
001
001
110

样例2：

4 3 0
001
001
011
000

样例3：

3 3 1
001
001
001
</td><td>样例1：

1.414214

样例2：

3.605551

样例3：

2.828427
</td></tr></table>
