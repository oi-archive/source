# 

 
 # 题目背景 
此题为taophee专辑中的第二题。<BR> 

 
 # 题目描述 
Taophee的学校有T棵梧桐树，这些梧桐树横着排成一列，依次编号为1....N<BR>Taophee为了为学习做一些好事，所以Taophee决定在N棵梧桐树的间隙中栽种一些银杏树。<BR>Taophee把这个任务分给了同学，让他们来负责规划栽树方案……<BR>YH提出了t1条如&nbsp;a&nbsp;b&nbsp;c&nbsp;(a&lt;b)的方案，即a&nbsp;b两棵梧桐之间的银杏不能少于c<BR>SL提出了t2条如&nbsp;b&nbsp;a&nbsp;-c&nbsp;(a&lt;b)的方案，即a&nbsp;b两棵梧桐之间的银杏不能多于c<BR>Taophee请你设计出一个方案，满足所有YH和SL的建议，并且使需要的银杏树最少。 

 
 # 输入格式 
第一行3个整数n,t1,t2用空格隔开<BR>以下t1行，每行3个数，表示YH的一条方案<BR>以下t2行，每行3个数，表示SL的一条方案 

 
 # 输出格式 
输出N行<BR>第一行是总共需要种植多少棵银杏树。<BR>第i+1行有一个非负整数表示第i棵和第i+1棵梧桐之间种了多少棵银杏<BR>只输出一组解<BR>如果无解，输出"No&nbsp;solution." 

 
 # 提示 
数据范围：<BR>2&nbsp;≤&nbsp;N（T)&nbsp;≤&nbsp;1000<BR>t1+t2&nbsp;≤&nbsp;5000<BR><BR>**注意这道题的第六个测试点有大问题，大家可以无视。** 
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
<tr><td>example1:
3 1 1
1 3 2
3 2 -1

example2:
2 1 1
1 2 2
2 1 -1
</td><td>example1:
2
1
1

example2:
No solution.
</td></tr></table>
