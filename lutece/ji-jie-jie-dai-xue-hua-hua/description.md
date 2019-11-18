
# Content

- 宋姐姐买了一块新的触摸板，然而宋姐姐只会用这块触摸板来打XSU。佳浩姐姐觉得这非常的浪费，于是佳浩姐姐决定教宋姐姐画画。
- 宋姐姐这块触摸板比较高端，它可以在三维平面内描绘点，于是佳浩姐姐在三维平面内画了n个点。
- 佳浩姐姐说：“现在你要用最少的线条将这些点连起来”，于是宋姐姐花了一笔曲线，“你必须使用直线来连接它们”，于是宋姐姐一条直线穿过了很多个点，“如果你画的直线覆盖了其它点的话，这并不能视作你将被覆盖的点连接起来了”，于是宋姐姐明白了，这是需要在三维空间中描绘一颗生成树，“你需要让每条线段的连接的两个点的高度差之和比上水平距离之和最小，这样才是一副优美的图”，于是宋姐姐不知道该怎么画了。
- 你能帮宋姐姐计算最优美的图的每条线段的连接的两个点的高度差之和比上水平距离之和的最小值是多少吗？

# Standard Input

- 第一行一个整数n，表示有n个点  (1 <= n <= 1000)
- 接下来n行，每行三个整数x，y，z，为每个点的坐标（0≤x,y≤10000,0≤z≤10000000）

# Standard Output

输出题目要求的数值，保留三位小数

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>5
1 1 1
2 2 2
3 3 3
4 4 4
2 3 3</td><td>0.495</td></tr></table>


# Constraints



# Note

保证不会有所有点都在z轴的情况

# Source


