
# Content

*17 张牌你能秒我，你能秒杀我，你今天能 17 张牌把卢本伟秒了，我当场就把这个电脑屏幕吃掉。*

打脸之后，开哥很不服气，于是他又参与了一场游戏，来决定自己是否真的吃掉电脑屏幕。

游戏中有 $n$ 个正实数 $a_1,a_2,\dots,a_n$，一开始所有人都不知道这些数是多少，参与游戏的 $m$ 个人各自做出一个预测，格式为 `o x y k`，含义如下：

- 若 $o=1$，则 $a_x \ge ka_y$。
- 若 $o=2$，则 $a_x \le ka_y$。
- 若 $o=3$，则 $a_x = ka_y$。

公布这些数分别是多少之后，预测错误的人将当场把电脑屏幕吃掉。不过在公布结果之前，开哥想知道，是否存在一种情况使得所有人都不用吃掉电脑屏幕。

# Standard Input

第一行两个整数 $n$ 和 $m$ ($2 \le n,m \le 5000$)，表示数的个数与人数。

接下来 $m$ 行为每个人做出的预测，每行四个数 $o,x,y,k$ ($1 \le o \le 3, 1 \le x,y \le n,x \neq y,0 < k \le 10$)，其中 $o,x,y$ 为整数，$k$ 为两位小数的浮点数。含义见题目描述。

# Standard Output

如果存在一种情况使得所有人都不用吃掉电脑屏幕，输出 `DEDEDEDEDEDEDEDEDEDEDEDE`。如果没有，输出 `Delicious`。

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
<tr><td>3 2
2 1 2 0.50
1 3 2 1.50</td><td>DEDEDEDEDEDEDEDEDEDEDEDE</td></tr><tr><td>2 2
1 1 2 2.00
2 1 2 0.50</td><td>Delicious</td></tr></table>


# Constraints



# Note

第一个样例中，两个人预测分别为 $a_1 \le 0.50a_2$ 和 $a_3 \ge 1.50 a_2$，一种可行情况为 $a_1=0.114514,a_2=2.33,a_3=1551$。

# Source


