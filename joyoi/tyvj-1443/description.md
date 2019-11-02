# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;在一个长方形框子里，最多有N（0≤N≤6）个相异的点，在其中任何一个点上放一个很小的油滴，那么这个油滴会一直扩展，直到接触到其他油滴或者框子的边界。必须等一个油滴扩展完毕才能放置下一个油滴。那么应该按照怎样的顺序在这N个点上放置油滴，才能使放置完毕后所有油滴占据的总体积最大呢？（不同的油滴不会相互融合）<BR>注：圆的面积公式V=pi*r*r，其中r为圆的半径。<BR> 

 
 # 输入格式 
第1行一个整数N。<BR>第2行为长方形边框一个顶点及其对角顶点的坐标，x,y,x’,y’。<BR>接下去N行，每行两个整数xi,yi，表示盒子的N个点的坐标。<BR>以上所有的数据都在[-1000，1000]内。<BR> 

 
 # 输出格式 
一行，一个整数，长方形盒子剩余的最小空间（结果四舍五入输出） 

 
 # 提示 
By:space7 
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
<tr><td>2
20 0 10 10
13 3
17 7
</td><td>50</td></tr></table>
