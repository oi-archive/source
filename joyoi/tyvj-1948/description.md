# 

 
 # 题目描述 
给出一个大小为n行*m列的矩形位图。该位图的每一个像素点不是白色就是黑色，但是至少有一个像素点是白色。在i行j列的像素点我们称为点（i，j）。两个像素点p1=（i1，j1）和p2=（i2，j2）之间的距离定义如下：<BR>d（p1，p2）=｜i1-i2｜+｜j1-j2｜<BR>现在的任务是：对于每一个像素点，计算它到最近的白色点的距离。如果它本身是白色点，距离为0.<BR> 

 
 # 输入格式 
第1行：2个整数n，m（1≤n≤182，1≤m≤182）。<BR>接下来n行，每一行有一个长度为m的0/1的字符串，描述一行像素点。如果点（i，j）为白色，则值为1，否则值为0。<BR> 

 
 # 输出格式 
输出一个矩阵，相邻两个数之间用空格隔开，表示每个点到其最近的白色点的距离。 
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
0001
0011
0110
</td><td>3 2 1 0
2 1 0 0
1 0 0 1
</td></tr></table>
