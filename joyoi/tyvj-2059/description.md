# 

 
 # 题目描述 
神探狄仁杰电影版首映这天，狄仁杰、李元芳和狄如燕去看电影。由于人实在是太多了，入场的队伍变得十分不整齐，一个人的前面可能会出现并排的好多人。<br>“元芳，这队伍你怎么看？”<br>“大人，卑职看不出这队伍是怎么排的！但是卑职看出了一些两个人之间的前后关系！”<br>“那么我们可以写个程序计算出来一定没有和其它人并排的人数。”<br>“大人/叔父真乃神人也！” 

 
 # 输入格式 
第一行两个数N、M，表示队伍一共有N个人，元芳看出了M对关系。<br>接下来M行每行两个数a、b，表示a在b的前面（不一定正好在b的前面，ab之间可能有其他人）。 

 
 # 输出格式 
有多少个人一定没有和其他人并排。 

 
 # 提示 
对于100%的数据，1&lt;=N&lt;=100，0&lt;=M&lt;=4500。数据保证M对关系不出现矛盾。sjynoi 
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
<tr><td>3 2
1 2
1 3</td><td>1</td></tr></table>
