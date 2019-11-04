# 

 
 # 题目描述 
<p>
桌上有一张边界平行于坐标轴的正方形纸片，左下角的坐标为(0,0)，右上角的坐标为(100,100)。接下来执行n条折纸命令。每条命令用两个不同点P1(x1,y1)和P2(x2,y2)来表示，执行时把当前的折纸作品沿着P1P2所在直线折叠，并把有向线段P1P2的右边折向左边（左边的部分保持不变）。

 
 # 输入格式 
<p>
输入第一行为一个整数n，即折纸的次数。以下n行每行四个实数x1,y1,x2,y2，表示每次折纸时对应的有向线段。下一行包含一个正整数m，即候选位置的个数，以下每行包含两个实数x,y，表示一个候选位置。

 
 # 输出格式 
<p>
每个候选位置输出一行，包含一个整数，即该位置打孔时穿过的层数。

 
 # 提示 
<p>
样例说明
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
-0.5 -0.5 1 1
1 75 0 75
6
10 60
80 60
30 40
10 10
50 50
20 50

</td><td>4
2
2
0
0
2
 
