
# Content

Megumin，是红魔族首屈一指的天才魔法师！她每天会找到n个二维平面上的目标进行爆裂魔法的练习。爆裂魔法覆盖的区域是一个圆形。为了节约魔力，她想要使爆裂魔法覆盖的区域完全包含所有目标的同时(目标可在圆形的边界上)，面积最小化。请你帮一下她吧！

来自Megumin的善意提醒：

1. 请尽量使用double类型存储实数，读入时可以使用%lf。

2. 输出保留k位小数的实数，可以使用%.kf。

3. 由于精度误差的原因，在比较两个实数的大小时，你可能要定义一个常数$EPS$(推荐设为10^(-8))，并参考以下内容：


$a < b \iff a-b < -EPS$

$a\leq b \iff a-b<EPS$

$a==b \iff fabs(a-b)<EPS$ //fabs(x)是math.h库中的函数，用于返回一个实数的绝对值

# Standard Input

输入的第一行包含1个整数n(1<=n<=3)，代表Megumin要摧毁的目标数。

接下来n行，每行包含两个实数x,y(-100000<=x,y<=100000)，代表一个目标的坐标。

保证n个目标两两不会重合。

# Standard Output

输出包含一行三个实数，分别是覆盖所有目标的最小圆的半径，圆心的横坐标，圆心的纵坐标。均保留4位小数。

如果输入只有一个点，最小圆的半径可能会退化为零。

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
<tr><td>3
0.0 1.0
0.0 -1.0
1.0 0.0</td><td>1.0000 0.0000 0.0000</td></tr></table>


# Constraints



# Note



# Source


