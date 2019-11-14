# 

 
 # 题目描述 
<p>Bessie驾驶她的飞船通过一个危险的小行星领域。该领域是N&times;N（1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;500）的网格形状。网格包含K颗小行星（1&nbsp;&lt;=&nbsp;K&nbsp;&lt;=&nbsp;10,000），每颗小行星占据一格。幸运的是，贝西有一个强大的武器，每次射出直线能量波蒸发某一行或某一列的所有小行星。这个武器的子弹相当昂贵，所以，她希望使用尽量少的子弹清空网格内的所有行星。一颗子弹发射一次直线能量波。</p> 

 
 # 输入格式 
<p>第1行：两个整数N和K，用一个空格隔开。<br />
第2至K&nbsp;+1行：每行包含两个用空格分开的整数ŗ和C（1&nbsp;&lt;=&nbsp;R，C&nbsp;&lt;=&nbsp;N）分别表示小行星的行坐标和列坐标。</p> 

 
 # 输出格式 
<p>输出一行，表示Bessie最少需要多少子弹。</p> 

 
 # 提示 
<p>样例细节：<br />
下图表示样例中的网格，其中&ldquo;X&rdquo;表示小行星，&ldquo;.&rdquo;表示空白格子。<br />
X.X<br />
.X.<br />
.X.<br />
Bessie可以朝第1行射击，消灭(1,1)和(1,3)位置的小行星，然后朝第2列射击，消灭(2,2)和(3,2)位置的小行星。</p> 
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
<tr><td>3 4
1 1
1 3
2 2
3 2
</td><td>2</td></tr></table>
