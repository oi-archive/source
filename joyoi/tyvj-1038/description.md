# 

 
 # 题目描述 
<p>&nbsp;&nbsp;&nbsp;&nbsp;老管家是一个聪明能干的人。他为财主工作了整整10年，财主为了让自已账目更加清楚。要求管家每天记k次账，由于管家聪明能干，因而管家总是让财主十分满意。但是由于一些人的挑拨，财主还是对管家产生了怀疑。于是他决定用一种特别的方法来判断管家的忠诚，他把每次的账目按1，2，3&hellip;编号，然后不定时的问管家问题，问题是这样的：在a到b号账中最少的一笔是多少？为了让管家没时间作假他总是一次问多个问题。</p> 

 
 # 输入格式 
<p>输入中第一行有两个数m,n表示有m(m&lt;=100000)笔账,n表示有n个问题，n&lt;=100000。<br />
第二行为m个数,分别是账目的钱数<br />
后面n行分别是n个问题,每行有2个数字说明开始结束的账目编号。</p> 

 
 # 输出格式 
<p>输出文件中为每个问题的答案。具体查看样例。</p> 
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
<tr><td>10 3
1 2 3 4 5 6 7 8 9 10
2 7
3 9
1 10</td><td>2 3 1</td></tr></table>
