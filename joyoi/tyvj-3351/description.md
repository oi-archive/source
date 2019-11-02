# 

 
 # 题目描述 
<p>
布线问题（wiring.pas\c\cpp） <br><br>【题目描述】 <br>　　在一块电路板上下两端分别有n个接线柱，自左至右分别以1，2，...,n 编号，根据情况，要求用导线(i,w)将下端接线柱i 与上端接线柱w 相连，其中1<=i,w<=n，导线（i,w）称为电路板上的第i根连线。满足条件1<=i<j<=n的2条线 (i,w),(j,u)相交的充分必要条件是 w>u. 出于布线的实际需要，布线常常是分层的——在同一层的导线不能相交。为了减少布线的层数，在第一层上应布尽可能多的导线。布线问题要解决的是，在这个电路板上不相交的连线最多有多少条？<br><br><center><img src="/source/joyoi/tyvj-3351/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzM1MS9wcm9ibGVtc19pbWFnZXMvMjEyOS8xLmpwZw==.jpg"></img></center><br>如图所示，第1根导线为（1,6),它与第2根线(2,4)是相交的，该布线问题的答案是4，即最大不相交边数为4（注：最大不相交边可以不唯一，如图中的第2、5、9、10和第4、5、9、10都是最大不相交边，但最大不相交边数是唯一的，你的任务是计算最大不相交边数）。</p> 

 
 # 输入格式 
<p>
　　输入文件（wiring.in）：<br>　　包含n+1个整数，第一个数是n（n<10000），表示接线柱数，接下来是n个整数（范围为1～n），分别表示下端接线柱号按升序排列时对应的上端接线柱编号，数与数之间用空格隔开。如在文件wiring1.in中，数据为10  6  4  8  3  5  10  2  1  7  9，则表示共有10个接线柱，其中下接线柱——上接线柱的连接情况为1——6，2——4，3——8，4——3，5——5，6——10，7——2，8——1，9——7，10——9<br></p> 

 
 # 输出格式 
<p>
　　输出文件（wiring.out）：<br>　　只包含1个整数，表示最大不相交边数。<br></p> 
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
<tr><td>10  6  4  8  3  5  10  2  1  7  9</td><td>4</td></tr></table>
