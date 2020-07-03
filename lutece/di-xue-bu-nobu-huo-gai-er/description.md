
# Content

好きなことにはいつだって    遠慮せずに行きたいな
希望能对喜欢的事物    没有丝毫顾虑
照れ隠しも迷いも捨てたら    あとは勇気だけ
将害羞与迷惑抛之脑后    只留下勇气
どんな角度から見ても    世界は広がってるよ
不论从哪个角度观察    世界都很辽阔

見たことのないもの    見つけて行きたいな
想要去寻找    那些未曾见过的事物
輝く意志を拾い集めて
将闪耀的意志收入囊中
俯いた先にも    見上げてる先にも
无论俯视大地    还是仰望天空
きっと未来は待っているよ
未来都会在前方等候
だから歩いていこう
所以继续迈步前行吧

——《[歩いていこう!](https://music.163.com/song?id=1422767271)》

---

暑假合宿期间，地学部开展了一次星座观察活动。

在某个晴朗的夜晚，Mira 和 Ao 架好了望远镜，通过望远镜，她们观察到了 $n$ 颗恒星。这 $n$ 颗恒星可以看做在二维平面上的点，坐标为 $(x_i,y_i)$。

Mira 和 Ao 想知道这些星星属于哪些星座，于是拍了一张星空的照片。第二天，二人去了图书馆查找。实际上，这些星星都属于星座 A 或星座 B，而一些星星知道它属于星座 A 和 B 中的某一个，另一些不知道。Mira 想知道用这些星星组成星座 A 和星座 B 的情况总数。由于恒星的大小足够小，因此可以看成一个点。

星座是由照片上的一颗或多颗恒星两两连成的线段组成的。注意仅由一颗星星组成的星座也被看做一个星座。Ao 发现：

- 这些线段可以让星座中任意两颗星彼此可达；
- 构成一个星座的线段不与构成另一星座的线段相交。

此外，Mira 发现恒星满足以下条件：

- 任意三颗星星均不共线；
- 星星只属于星座 A 或星座 B 的一种，她们发现的星星没有属于除星座 A 和星座 B 之外的星座。

Mira 想知道这些星星组成星座 A 和星座 B 的情况总数，但是 Mira 数学不好，于是作为 Ao，你需要帮助 Mira 求出这个值对 $10^9+7$ 取模的值。

# Standard Input

第一行，一个正整数 $n$，意义如题目描述。

第二到第 $n+1$ 行，每行三个整数 $x,y,c$。第 $i$ 行描述第 $i-1$ 颗星星的信息，其中 $x,y$ 分别为恒星位置的横、纵坐标，即恒星的坐标为 $(x,y)$；$c$ 为对于恒星类型的描述，$1$ 表示恒星属于星座 A ，$2$ 表示恒星属于星座 B，$0$ 表示不确定恒星属于哪个星座。

# Standard Output

输出一行一个整数，表示这些星星组成星座 A 和星座 B 的情况总数对 $10^9+7$ 取模后的值。如果不存在任何一种合法的星座 A 与星座 B，则输出 $0$。

若同一星座有多种连线方式满足条件，则只看成一种。

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
1 0 1
0 2 2
2 2 0
1 4 0</td><td>3</td></tr><tr><td>6
1 0 1
1 1 0
2 2 0
3 0 2
3 1 0
4 2 0</td><td>8</td></tr></table>


# Constraints

$2\le n\le 10^5,0\le x_i,y_i\le 10^9,0\le c\le 2$，保证两颗星不会位于同一位置，任意三颗星不共线。

# Note

样例一如下图所示：

![](/source/lutece/di-xue-bu-nobu-huo-gai-er/img/aHR0cHM6Ly9oZXJhbm8uY29kaW5nLm5ldC9wL1BpY1BsYWNlL2QvUGljUGxhY2UvZ2l0L3Jhdy9tYXN0ZXIvaG9zaGkyXzEucG5n.png)

其中，蓝色点表示属于星座 A，红色点表示属于星座 B，黑色点表示所属星座未知。

符合条件的三种情况如下图所示：

![](/source/lutece/di-xue-bu-nobu-huo-gai-er/img/aHR0cHM6Ly9oZXJhbm8uY29kaW5nLm5ldC9wL1BpY1BsYWNlL2QvUGljUGxhY2UvZ2l0L3Jhdy9tYXN0ZXIvaG9zaGkyXzIucG5n.png)

# Source


