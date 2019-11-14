
# Content

![](/source/lutece/li-zhi-de-hou-zi/img/bb5b042783f444a12b32e71ca4bce7d4.jpg)

上图是2013南京亚青会吉祥物圆圆。自从它诞生以来，它就被吐槽为最丑吉祥物。即使如此，它仍然坚强的活着，并且……它还学会了人类的坐标系、画画和数学，成为了猴界的全才。看到它这么努力，你还有理由不努力吗！

虽然如此努力，圆圆受限于猴子的脑容量，还是差了一点——它只能掌握一维坐标系，画画只能分辨两种颜色，数学上只会不等式，只能认识整数。这一天，圆圆很无聊，于是它拿起一维坐标纸，想在纸上画n条线段，第i条线段从坐标轴的xi延伸到yi（包括端点）。

励志的圆圆想要展示一下自己的智商，它用红蓝彩笔画下这n条线段，并且希望对于坐标轴上任意一个点，经过它的红线和蓝线数量的绝对值之差小于等于1.如果某个点是线段的端点，则这条线段也算作经过该点。

不过这时，圆圆发现自己的算数能力还是有点差，于是它找到了你，希望你确定每条线段的颜色，来满足它的奇思妙想。

# Standard Input

第一行一个整数n(1 ≤ n ≤ 100000), 表示圆圆画的线段的数量。

接下来n行，每行两个整数x,y( 0≤ x ≤ y ≤ $10^{9}$ ),表示一条线段从x延伸到y。

# Standard Output

输出n个数，用空格隔开，如果第i条线段是蓝色，则输出0，否则输出1.

如果有多组解，输出一组即可。

如果找不到答案，输出一个数-1.

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
<tr><td>2
1 2
2 3</td><td>0 1</td></tr><tr><td>6
1 5
1 3
3 5
2 10
11 11
12 12</td><td>0 1 1 0 0 1</td></tr></table>


# Constraints



# Note

样例1: 第一条线段是蓝色，第二条线段是红色。

两组样例都可能有其他正确答案。

# Source


