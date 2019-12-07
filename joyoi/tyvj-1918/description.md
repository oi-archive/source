# 

 
 # 题目背景 
[noip2007P2]纪念品分组 

 
 # 题目描述 
元旦快到了，校学生会让乐乐负责新年晚会的纪念品发放工作。为使得参加晚会的同学所获得的纪念品价值相对均衡，他要把购来的纪念品根据价格进行分组，但每组最多只能包括两件纪念品，并且每组纪念品的价格之和不能超过一个给定的整数。为了保证在尽量短的时间内发完所有纪念品，乐乐希望分组的数目最少。<BR>你的任务是写一个程序，找出所有分组方案中分组数最少的一种，输出最少的分组数目。<BR><BR> 

 
 # 输入格式 
包含n+2行：<BR>&nbsp;&nbsp;&nbsp;&nbsp;第1行包括一个整数w，为每组纪念品价格之和的上限。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第2行为一个整数n，表示购来的纪念品的总件数。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第3~n+2行每行包含一个正整数pi&nbsp;(5&nbsp;&lt;=&nbsp;pi&nbsp;&lt;=&nbsp;w)，表示所对应纪念品的价格。<BR> 

 
 # 输出格式 
仅一行，包含一个整数，即最少的分组数目。 

 
 # 提示 
&nbsp;&nbsp;&nbsp;&nbsp;50%的数据满足：1&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;15<BR>&nbsp;&nbsp;&nbsp;&nbsp;100%的数据满足：1&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;30000,&nbsp;80&nbsp;&lt;=&nbsp;w&nbsp;&lt;=&nbsp;200<BR> 
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
<tr><td>100
9
90
20
20
30
50
60
70
80
90
</td><td>6</td></tr></table>
