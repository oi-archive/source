# 

 
 # 题目背景 
中中带领着OIer们最近迷上了看小说，但是呢，OIer们总是怕中中老师童鞋发现，于是乎就自己更改了小说的文件名以防被发现。但是呢，中中在高处安装了一个摄像头来监控同学们。这个摄像头是个近视眼，它只能够清楚的看见文件名，但是不能看清楚文件内容。<BR> 

 
 # 题目描述 
OIer们要看N部小说，每部小说都有危险值，这部小说的危险值就是小说名称的危险值&nbsp;*&nbsp;小说内容的危险值。小说名称的危险值为这个小说名称的最长上升子序列的长度，小说内容的危险值在每部小说的名称后边已给出。对于小说的名称和小说的内容可以任意组合，使得最后小说的危险值总和最小。<BR> 

 
 # 输入格式 
第一行，一个整数N，表示有N部小说。<BR>以下N行，每行有一个字符串和一个整型数字，由一个空格分割，分别表示小说名及小说内容的危险值。<BR> 

 
 # 输出格式 
一个数，N部小说最小的危险值总和。 

 
 # 提示 
对于N，40%的数据满足1≤N≤1000，100%的数据满足1≤N≤10000；危险值都为正整数。<BR>每个文件名的长度不超过255,并且保证字符串中无空格。<BR>保证结果在longint范围内。<BR>对于样例，原危险值为：1&nbsp;*&nbsp;2&nbsp;+&nbsp;4&nbsp;*&nbsp;3&nbsp;=&nbsp;14<BR>如果将第一部小说的文件名称与第二部小说调换，那么新得到的危险值为：<BR>1&nbsp;*&nbsp;3&nbsp;+&nbsp;4&nbsp;*&nbsp;2&nbsp;=&nbsp;11<BR>可证实11为最小。 
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
SPFA 2
ABCD 3</td><td>11</td></tr></table>
