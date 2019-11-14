# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;小k在遗迹探险时遇到了n个按钮，刚开始所有按钮都处于开状态，小k的经验告诉他把所有按钮都关上会有“好事”发生，可是有些按钮按下时会让其他一些已经闭合的按钮弹开。经过研究，每个按钮都对应着一个固定的弹开集合，这个按钮按下时，弹开集合中所有的按钮都会变为开状态。现在小k想知道是否能让所有的按钮变为闭状态。如果能，打印最少步数以及方案。否则，打“no&nbsp;solution"。<br> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行一个整数n，表示n个按钮<br>&nbsp;&nbsp;&nbsp;&nbsp;接下来n行，表示编号为l到n个按钮&nbsp;的弹开集合<br>&nbsp;&nbsp;&nbsp;&nbsp;格式为mi，B1B2&nbsp;B3…Bmi。<br>&nbsp;&nbsp;&nbsp;&nbsp;表示编号为i的按钮按下，会让编号为B1B2&nbsp;B3…Bmi&nbsp;的按钮弹开(注：其中不会出现重&nbsp;&nbsp;复)<br><br> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;如果无解，输出"no&nbsp;solution"．<br>&nbsp;&nbsp;&nbsp;&nbsp;否则，第一行输出最少步数ans，第二行输出用空格分开的ans个数，表示按顺序按下<br>编号为这些数的按钮就可以解决。<br>&nbsp;&nbsp;&nbsp;&nbsp;如果有多种方案，输出字典序最小的方案。<br> 

 
 # 提示 
&nbsp;&nbsp;&nbsp;&nbsp;l≤n≤30000<br>&nbsp;&nbsp;&nbsp;&nbsp;令M=m1+m2+…+mn<br>&nbsp;&nbsp;&nbsp;&nbsp;0≤M≤1000000<br><br><br> 
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
<tr><td>6
2 2 3
0
2 4 5
0
0
0

</td><td>6
l 2 3 4 5 6


</td></tr></table>
