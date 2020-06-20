
# Content

小兔子是坏小兔子，因为他总会在上课的时候选择摸鱼。

今天上课，小兔子又发现了一款神奇的游戏，这次它想跟认真上课的小马一起玩。

这款游戏属于扑克类型，不过这款游戏没有大小王，一共只有 $52$ 张牌（A 2 3 4 5 6 7 8 9 10 J Q K 各 4 张）。

本游戏的牌点由大到小排列为：2、A、K、Q、J、10、9、8、7、6、5、4、3。

有如下几种出牌方式：
1. 单张，可以是手中的任意一张牌， 如 3，4，J，K；
2. 对子，两张牌点相同的牌，如 33，44，JJ，KK；
3. 连对，两对或两对以上相连的牌，如：33 44，99 88。
*注意：A 和 2 在构成连对时可以：AA 22 33 44，JJ QQ KK AA，但不能 QQ KK AA 22，更不能 QQ KK AA 22 33；
4. 三同张，三张牌点相同的牌；
5. 连三同张，两个或两个以上相连的三同张牌，如：333 444，JJJ QQQ。
*注意： A 和 2 在构成连三同张时可以：AAA 222 333 444，JJJ QQQ KKK AAA，但不能 QQQ KKK AAA 222，更不能 QQQ KKK AAA 222 333；
6. 顺子，五张或五张以上牌点连续的牌，如：3456789(10)JQK 等。注意：A、2在构成顺子时，可以 A2345 或 9(10)JQKA，而不能组成 JQKA2 这样的顺子，更不能组成 JQKA23 这样的顺子；
7. 炸弹，四张牌点相同的牌，如：4444，7777，JJJJ；

小马现在还剩 $n$ 张牌，请你帮助小马计算小马最少出几次，能出完这些牌。

# Standard Input

第一行一个数 $T$，表示接下来有 $T$ 组测试数据。

每一组测试数据有两行：

1. 第一行是一个整数 $n$，代表手中有 $n$ 张牌；
2. 第二行是 $n$ 张牌，表示方法见样例。

# Standard Output

输出 $T$ 行，每一行一个整数，代表答案。

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
13
A 2 3 4 5 6 7 8 9 10 J Q K
5
A 2 3 4 5
5
10 J Q K A
5
J Q K A 2</td><td>1
1
1
5</td></tr></table>


# Constraints

$1 \leq T\leq 100$
$1\leq n\leq 20$

# Note



# Source


