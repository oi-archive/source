# 

 
 # 题目描述 
罗密欧与朱丽叶的迷宫问题<br>描述<br>罗密欧与朱丽叶的迷宫。罗密欧与朱丽叶身处一个m×n的迷宫中，如图所示。<br>[罗]&nbsp;&nbsp;[**]&nbsp;&nbsp;[&nbsp;&nbsp;]&nbsp;&nbsp;[&nbsp;&nbsp;]&nbsp;<br>[&nbsp;&nbsp;]&nbsp;&nbsp;[朱]&nbsp;&nbsp;[&nbsp;&nbsp;]&nbsp;&nbsp;[&nbsp;&nbsp;]&nbsp;<br>[&nbsp;&nbsp;]&nbsp;&nbsp;[&nbsp;&nbsp;]&nbsp;&nbsp;[&nbsp;&nbsp;]&nbsp;&nbsp;[**]<br>每一个方格表示迷宫中的一个房间。这m×n个房间中有一些房间是封闭的，不允许任何人进入。在迷宫中任何位置均可沿8&nbsp;个方向进入未封闭的房间。罗密欧位于迷宫的(p，q)方格中，他必须找出一条通向朱丽叶所在的(r，s)方格的路。在抵达朱丽叶之前，他必须走遍所有未封闭的房间各一次，而且要使到达朱丽叶的转弯次数为最少。每改变一次前进方向算作转弯一次。请设计一个算法帮助罗密欧找出这样一条道路。<br>&nbsp;<br>对于给定的罗密欧与朱丽叶的迷宫，编程计算罗密欧通向朱丽叶的所有最少转弯道路。<br><br> 

 
 # 输入格式 
输入格式:<br>&nbsp;&nbsp;第一行有3&nbsp;个正整数n，m，k，分别表示迷宫的行数，列数和封闭的房间数。接下来的k行中，每行2&nbsp;个正整数，表示被封闭的房间所在的行号和列号。最后的2&nbsp;行，每行也有2&nbsp;个正整数，分别表示罗密欧所处的方格(p，q)和朱丽叶所处的方格(r，s)。 

 
 # 输出格式 
输出格式:<br>&nbsp;&nbsp;最少转弯次数。<br>&nbsp;&nbsp;如果罗密欧无法通向朱丽叶则输出“No&nbsp;Solution!”(注意:两边无引号，中间有逗号。)。<br> 

 
 # 提示 
提示:DFS&nbsp;<br>数据规模:0&lt;=n,m&lt;=10. 
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
<tr><td>3 4 2
1 2
3 4
1 1 
2 2</td><td>6</td></tr></table>
