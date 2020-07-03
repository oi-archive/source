
# Content

離れないよ    ぎゅっと誓う
曾经立下誓言    希望永不分离
小さな手    結ぶ星座
我们小小的手    连结成了星座
藍色の向こうに    約束したんだ
面向蔚蓝星空    许下这个约定

たぶん絆は    少しずつ    降り積もっていくもの
所谓的羁绊    就是一点一滴累积而成的吧

僕らが見つめる世界は    憧れに輝き変える
我们眼中的世界    因憧憬而变得光芒万丈
願いも    迷いも    照らし合えたらいいね
无论希望还是迷茫    我都想与你分享
交差してる    時の彼方    叶えたいものがあるから
因为在时空交错的彼方    还有想要去实现的愿望
焦がれよう    夜空を彩る    星みたいに
一心向往吧    如同那点缀夜空的繁星

——《[夜空](https://music.163.com/song?id=1423038384)》

---

暑假合宿期间，地学部开展了一次星座观察活动。

在某个晴朗的夜晚，Mira 和 Ao 架好了望远镜，通过望远镜，她们观察到了 $n$ 颗恒星。这 $n$ 颗恒星可以看做在二维平面上的点，坐标为 $(x_i,y_i)$。她们观察到的星星没有任意三颗在同一条直线上。

单独观察星星是比较无聊的，于是她们按照恒星的光谱分类，给这些星星分为三类：R 型星，G 型星和 B 型星。

只有 Ao 座太孤单了，Mira 也想组建一个 Mira 座。星座应该是小而美的，她们想要这个星座的星星数量最少，而且包含所有类型的星。容易知道这个星座只有三颗星，并且这三颗星的类型为 R 型，G 型和 B 型。

每个星座中的三颗星一定会构成三角形，为了美感，Ao 想要 Ao 座和 Mira 座相离。两个三角形相离是指不存在平面上任何一点同时在两个三角形的内部或边界上。所以 Mira 和 Ao 想要求出共有多少种可能的 Mira - Ao 座。

注意：如果构成三角形的 $6$ 个点一样，但是构成三角形的方式不同，算作不同的方案。

# Standard Input

第一行，一个正整数 $n$，意义如题目描述。

第二到第 $n+1$ 行，每行三个整数 $x,y,c$。第 $i$ 行描述第 $i-1$ 颗星星的信息，其中 $x,y$ 分别为恒星位置的横、纵坐标，即恒星的坐标为 $(x,y)$；$c$ 为对于恒星类型的描述，$0$ 表示星星为 B 型星，$1$ 表示为 R 型星，$2$ 表示为 G 型星。

# Standard Output

输出一行一个整数，表示她们会在多少个方案中选择。

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
<tr><td>7
-1 2 0
1 2 0
-1 -2 1
1 -2 1
-3 0 2
3 0 2
0 -1 0</td><td>5</td></tr><tr><td>20
1 -41 0
-4 0 2
-3 10 2
-2 19 1
4 -53 2
5 -55 0
1 40 2
3 49 0
5 54 0
-4 -1 0
2 45 1
-2 -20 0
0 34 0
3 -50 2
2 -46 0
-1 27 1
-1 -28 2
-3 -11 2
4 52 1
0 -35 1</td><td>7354</td></tr></table>


# Constraints

$6\le n\le 3\times 10^3,|x|,|y|\le 10^5,0\le c\le 2$，保证存在一个 Ao 座和一个 Mira 座，两颗星不会位于同一位置，且没有三颗恒星在同一直线上。

# Note

样例一如下图所示：

![](/source/lutece/di-xue-bu-nobu-huo-gai/img/aHR0cHM6Ly9oZXJhbm8uY29kaW5nLm5ldC9wL1BpY1BsYWNlL2QvUGljUGxhY2UvZ2l0L3Jhdy9tYXN0ZXIvaG9zaGkxXzEucG5n.png)

符合条件的五个 Mira - Ao 座如下：

![](/source/lutece/di-xue-bu-nobu-huo-gai/img/aHR0cHM6Ly9oZXJhbm8uY29kaW5nLm5ldC9wL1BpY1BsYWNlL2QvUGljUGxhY2UvZ2l0L3Jhdy9tYXN0ZXIvaG9zaGkxXzIucG5n.png)

# Source


