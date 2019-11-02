# 

 
 # 题目描述 
<p>农民John的农场里有很多牧区。有的路径连接一些特定的牧区。一片所有连通的牧区称为一个牧场。但是就目前而言，你能看到至少有两个牧区通过任何路径都不连通。这样，农民John就有多个牧场了。&nbsp;<br />
<br />
John想在农场里添加一条路径(注意，恰好一条)。对这条路径有以下限制：&nbsp;<br />
<br />
一个牧场的直径就是牧场中最远的两个牧区的距离(本题中所提到的所有距离指的都是最短的距离)。考虑如下的有5个牧区的牧场，牧区用&ldquo;*&rdquo;表示，路径用直线表示。每一个牧区都有自己的坐标：&nbsp;<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;15,15&nbsp;&nbsp;&nbsp;20,15<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;D&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;E<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*-------*<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;_/|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;_/&nbsp;&nbsp;|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;_/&nbsp;&nbsp;&nbsp;&nbsp;|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*--------*-------*<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;C<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;10,10&nbsp;&nbsp;&nbsp;15,10&nbsp;&nbsp;&nbsp;20,10<br />
这个牧场的直径大约是12.07106,&nbsp;最远的两个牧区是A和E，它们之间的最短路径是A-B-E。&nbsp;<br />
<br />
这里是另一个牧场：&nbsp;<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*F&nbsp;30,15<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;/&nbsp;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;_/&nbsp;&nbsp;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;_/&nbsp;&nbsp;&nbsp;&nbsp;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*------*&nbsp;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;G&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;H<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;25,10&nbsp;&nbsp;&nbsp;30,10<br />
这两个牧场都在John的农场上。John将会在两个牧场中各选一个牧区，然后用一条路径连起来，使得连通后这个新的更大的牧场有最小的直径。&nbsp;<br />
<br />
注意，如果两条路径中途相交，我们不认为它们是连通的。只有两条路径在同一个牧区相交，我们才认为它们是连通的。&nbsp;<br />
<br />
输入文件包括牧区、它们各自的坐标，还有一个如下的对称邻接矩阵：&nbsp;<br />
<br />
　　&nbsp;A&nbsp;&nbsp;B&nbsp;&nbsp;C&nbsp;&nbsp;D&nbsp;&nbsp;E&nbsp;&nbsp;F&nbsp;&nbsp;G&nbsp;&nbsp;H&nbsp;<br />
A&nbsp;&nbsp;0&nbsp;&nbsp;1&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0<br />
B&nbsp;&nbsp;1&nbsp;&nbsp;0&nbsp;&nbsp;1&nbsp;&nbsp;1&nbsp;&nbsp;1&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0<br />
C&nbsp;&nbsp;0&nbsp;&nbsp;1&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;1&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0<br />
D&nbsp;&nbsp;0&nbsp;&nbsp;1&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;1&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0<br />
E&nbsp;&nbsp;0&nbsp;&nbsp;1&nbsp;&nbsp;1&nbsp;&nbsp;1&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0<br />
F&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;1&nbsp;&nbsp;0<br />
G&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;1&nbsp;&nbsp;0&nbsp;&nbsp;1<br />
H&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;0&nbsp;&nbsp;1&nbsp;&nbsp;0<br />
输入文件至少包括两个不连通的牧区。&nbsp;<br />
<br />
请编程找出一条连接两个不同牧场的路径，使得连上这条路径后，这个更大的新牧场有最小的直径。&nbsp;<br />
&nbsp;</p> 

 
 # 输入格式 
<p>第1行:&nbsp;一个整数N&nbsp;(1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;150),&nbsp;表示牧区数&nbsp;<br />
<br />
第2到N+1行:&nbsp;每行两个整数X,Y&nbsp;(0&nbsp;&lt;=&nbsp;X&nbsp;,Y&lt;=&nbsp;100000),&nbsp;表示N个牧区的坐标。注意每个&nbsp;牧区的坐标都是不一样的。&nbsp;<br />
<br />
第N+2行到第2*N+1行:&nbsp;每行包括N个数字(0或1)&nbsp;表示如上文描述的对称邻接矩阵。&nbsp;<br />
&nbsp;</p> 

 
 # 输出格式 
<p>只有一行，包括一个实数，表示所求直径。数字保留六位小数。&nbsp;</p> 

 
 # 提示 
<p>USACO&nbsp;2.4.3</p> 
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
<tr><td>8
10 10
15 10
20 10
15 15
20 15
30 15
25 10
30 10
01000000
10111000
01001000
01001000
01110000
00000010
00000101
00000010
</td><td>22.071068
</td></tr></table>
