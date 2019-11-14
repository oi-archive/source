# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;老管家是一个聪明能干的人。他为财主工作了整整10年，财主为了让自已账目更加清楚。要求管家每天记k次账，由于管家聪明能干，因而管家总是让财主十分满意。但是由于一些人的挑拨，财主还是对管家产生了怀疑。于是他决定用一种特别的方法来判断管家的忠诚，他把每次的账目按1，2，3…编号，然后不定时的问管家问题，问题是这样的：在a到b号账中最少的一笔是多少？为了让管家没时间作假他总是一次问多个问题。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在询问过程中账本的内容可能会被修改 

 
 # 输入格式 
输入中第一行有两个数m,n表示有m(m&lt;=100000)笔账,n表示有n个问题，n&lt;=100000。<BR>接下来每行为3个数字，第一个p为数字1或数字2，第二个数为x，第三个数为y<BR>当p=1&nbsp;则查询x,y区间<BR>当p=2&nbsp;则改变第x个数为y 

 
 # 输出格式 
输出文件中为每个问题的答案。具体查看样例。 
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
1 2 7
2 2 0
1 1 10</td><td>2 0</td></tr></table>
