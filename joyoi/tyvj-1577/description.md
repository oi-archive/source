# 

 
 # 题目描述 
公园中有n个景点，编号1~n，并由m条双向道路相连。由于昨天下雨，导致公园中的马路泥泞不堪，每条道路都有一个泥泞程度w。现有Q个游客依次向你求助，想从景点X走到景点Y，他希望找到一条道路，使得经过道路泥泞程度的最大值尽量小。你能设计一个在线算法，帮他们找到方案吗？ 

 
 # 输入格式 
第一行两个正整数n和m，表示景点数和道路数。<BR>随后m行每行三个正整数x、y、w，用来描述一条道路，它连接x和y景点并且泥泞程度为w。<BR>随后Q行，每行四个参数p1、p2、q1、q2，含义如下：<BR>设数列Si表示你求得的第i个询问的结果（s0=1），则对于第i个询问：<BR>X=(Si-1+p1)*p2&nbsp;mod&nbsp;n&nbsp;+&nbsp;1;<BR>Y=(si-1+q1)*q2&nbsp;mod&nbsp;n&nbsp;+&nbsp;1;<BR> 

 
 # 输出格式 
请对于每个询问，输出结果，即Si。 

 
 # 提示 
对于30%的数据，n&lt;=1000，m&lt;=3000，Q&lt;=1000；<BR>对于100%的数据，n&lt;=100000，m&lt;=300000，Q&lt;=100000；<BR>对于100%的数据，0&lt;=p1、p2、q1、q2&lt;n，w&lt;300000。<BR> 
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
<tr><td>4 4
1 2 2
2 3 1
1 3 3
3 4 5
2
3 1 0 2
1 1 2 1
</td><td>2
5
说明：第一个询问是{x=1，y=3}，第二个询问是{x=4，y=1}。
</td></tr></table>
