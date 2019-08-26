
# 题目描述

**译自 [COCI 2018/2019 Contest #4](http://www.hsin.hr/coci/contest4_tasks.pdf) T4「Slagalica」**

自从 Jurica 学会解魔方之后，他开始对这种谜题有了兴趣，并且自己创造了一个神秘的玩具。他的谜题是一个平行四边形形状的三角形网格，其网格的节点是 $N$ 行 $M$ 列，**从下至上编号，同行从左至右编号**。如下图所示。

<center>
<img src="source/loj/3131/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNS8yNy81Y2ViYmE0ZTgxY2M2LnBuZw==.png" width="60%"/>
</center>

该谜题有以下两种调整方法：

- 选择一个单位菱形，其顶点为 $(x, y), (x + 1, y), (x + 1, y + 1), (x, y + 1)$，将其上的节点顺时针旋转。

<center>
<img src="source/loj/3131/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNS8yNy81Y2ViYmE0ZmIwYzY5LnBuZw==.png" width="60%"/>
</center>

- 选择一个等边三角形，其顶点为 $(x, y), (x + 1, y), (x, y + 1)$，将其上的节点顺时针旋转。

<center>
<img src="source/loj/3131/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNS8yNy81Y2ViYmE0ZjY2NGUxLnBuZw==.png" width="60%"/>
</center>

一天，Jurica 无聊地摆弄着谜题，他进行了一系列操作，称这一系列操作整体为一个大操作。接着他开始不断地重复这个大操作，他发现每经过恰好 $K$ 次大操作后，谜题会回到最初的状态。

给定 $N, M, K$，请找出一个大操作，使得恰好 $K$ 次大操作后，谜题会回到最初的状态，或者确定不存在这样一种大操作。注意你并不需要使得大操作的操作数量最少，但操作数量有一定限制。


# 输入格式

一行输入三个正整数 $N, M, K$，意义如题目描述所示。

# 输出格式

若不存在满足条件的操作序列，输出 $-1$。

否则第一行输出一个正整数 $B (1\le B \le 5\times 10^5)$，表示操作数量。

接下来 $B$ 行，每行表示一个操作，按照操作顺序输出。每行一个字符 `R` 或 `T` 接着两个正整数 $x, y (1\le x < N, 1\le y < M)$，意义如题目描述所示。
- `R` 表示对菱形的旋转
- `T` 表示对三角形的旋转


# 样例

#### 样例输入 1

```plain
2 3 2
```

#### 样例输出 1

```plain
5
R 1 1
R 1 1
T 1 1
T 1 1
T 1 1
```

#### 样例输入 2

```plain
3 3 12
```

#### 样例输出 2

```plain
3
R 1 1
T 2 2
T 2 1
```

#### 样例输入 3

```plain
5 4 116
```

#### 样例输出 3

```plain
-1
```


# 数据范围与提示

对于 $40\%$ 的数据，保证 $N, M\le 3$ 且 $K\le 20$。

对于 $100\%$ 的数据，保证
- $2\le N, M \le 100$
- $2\le K \le 10^{12}$

