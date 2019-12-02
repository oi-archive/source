# 

 
 # 题目描述 
<p>
画一个等边三角形，把三边的中点连接起来，得到四个三角形，把它们称为T1,T2,T3,T4，如图1。把前三个三角形也这样划分，得到12个更小的三角形：T11,T12,T13,T14,T21,T22,T23,T24,T31,T32,T33,T34，如图2。把编号以1，2，3结尾的三角形又继续划分…最后得到的分形称为Sierpinski三角形。<br><br><img border="0" src="/source/joyoi/tyvj-2203/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjIwMy9wcm9ibGVtc19pbWFnZXMvMjU1Mi8xMjU4LmpwZw==.jpg"> <br>图1.                                          图2.<br>如果B不包含A，且A的某一条完整的边是B的某条边的一部分，则我们说A靠在B的边上。例如T12靠在T24和T4上，但不靠在T32上。给出Spierpinski三角形中的一个三角形，找出它靠着的所有三角形。<br></p> 

 
 # 输入格式 
<p>
输入仅一行，即三角形的编号，以T开头，后面有n个1到4的数字。仅最后一个数字可能为4。<br><br></p> 

 
 # 输出格式 
<p>
输出每行一个三角形编号，按字典序从小到大排列。<br></p> 

 
 # 提示 
<p>
50%的数据满足：1<=n<=5<br>100%的数据满足：1<=n<=50<br></p> 
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
<tr><td>T312

</td><td>T314
T34
T4
</td></tr></table>
