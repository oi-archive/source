# 

 
 # 题目描述 
<p>
	给出一个图形，判断它是一个圈还是一个叉。</p> 

 
 # 输入格式 
<p>
	第一行一个整数T(T<=5)，表示数据组数。<br>	每组数据第一行两个数X Y(3<=X,Y<=10)。<br>	下面X行给出一个图形（仅由.X组成）。<br></p> 

 
 # 输出格式 
<p>
	输出一行包含T个字符，O表示是一个圈，X表示是一个叉。</p> 

 
 # 提示 
<p>
叉和圈都是相对的，一个模糊的定义是，图形（可能不连通）大概组成的更像是什么。</p> 
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
<tr><td>5
5 5
X...X
.X.X.
..X..
.X.X.
X...X
5 5
XXXXX
X...X
X...X
X...X
XXXXX
6 6
..X...
..X...
X.XXXX
..X...
..X...
......
5 5
.XXX.
X...X
X...X
X...X
.XXX.
5 5
.XXX.
.X.X.
.XXX.
.....
.....
</td><td>XOXOO
</td></tr></table>
