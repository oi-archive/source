
# Content

夜空中最亮的星 是否知道
曾与我同行的身影 如今在哪里
夜空中最亮的星 是否在意
是等太阳升起 还是意外先来临

我宁愿所有痛苦都留在心里
也不愿忘记你的眼睛
给我再去相信的勇气
越过谎言去拥抱你
每当我找不到存在的意义
每当我迷失在黑夜里
夜空中最亮的星 请照亮我前行

——《[夜空中最亮的星](https://music.163.com/song?id=25706282)》

---

暑假合宿期间，地学部开展了一次星座观察活动。

在某个晴朗的夜晚，Mira 和 Ao 架好了望远镜，通过望远镜，她们观察到了 $n$ 颗恒星。这 $n$ 颗恒星可以看做在二维平面上的点，坐标为 $(x_i,y_i)$。

Mira 想要给 Ao 组建一个星座——Ao 座，以弥补没有 Ao 星的遗憾。这个星座应该是小而美的，她想要这个星座的星星数量最少，并且是一个凸多边形。容易知道 Ao 座的三颗恒星构成了一个非平凡三角形。

定义一个星座占据的面积为构成这个星座的恒星所组成的三角形的面积。Mira 想知道这 $n$ 颗恒星组成的所有可能的 Ao 座占据的面积总和。

如果不存在这样的 Ao 座，请输出 `QAQ`。

# Standard Input

第一行，一个正整数 $n$，意义如题目描述。

第二到第 $n+1$ 行，每行三个整数 $x,y$。第 $i$ 行描述第 $i-1$ 颗星星的信息，其中 $x,y$ 分别为恒星位置的横、纵坐标。

# Standard Output

若存在 Ao 座，则输出一行一个实数，表示所求的面积和，保留一位小数输出。否则输出一行一个字符串 `QAQ`。

只有输出实数与标准答案完全相同才认为该测试点通过。

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
<tr><td>4
1 1
4 5
1 4
1 9</td><td>24.0</td></tr><tr><td>8
3 1
-5 3
-1 1
-2 1
2 -4
2 1
7 7
0 3</td><td>551.0</td></tr><tr><td>3
1 1
2 2
3 3</td><td>QAQ</td></tr></table>


# Constraints

$3\le n\le 6\times 10^3,|x|,|y|\le 10^4$，保证任意两颗星不会位于同一位置。

# Note

样例一中，输入各点位置如下图：

![](/source/lutece/di-xue-bu-nobu-huo/img/aHR0cHM6Ly9oZXJhbm8uY29kaW5nLm5ldC9wL1BpY1BsYWNlL2QvUGljUGxhY2UvZ2l0L3Jhdy9tYXN0ZXIvaG9zaGlfMS5wbmc=.png)

形成的所有 Ao 座即为 $\triangle \text{ABC},\triangle \text{ABD},\triangle \text{BCD}$。

![](/source/lutece/di-xue-bu-nobu-huo/img/aHR0cHM6Ly9oZXJhbm8uY29kaW5nLm5ldC9wL1BpY1BsYWNlL2QvUGljUGxhY2UvZ2l0L3Jhdy9tYXN0ZXIvaG9zaGlfMi5wbmc=.png)

可知面积总和为 $24$。

# Source


