
# 题目描述

**译自 [JOI Open 2020](https://contests.ioi-jp.org/open-2020/index.html) T2 「[白黒の点](http://s3-ap-northeast-1.amazonaws.com/data.cms.ioi-jp.org/open-2020/monochrome/2020-open-monochrome-statement.pdf) / [Monochrome Points](http://s3-ap-northeast-1.amazonaws.com/data.cms.ioi-jp.org/open-2020/monochrome/2020-open-monochrome-statement-en.pdf)」**

在一个环上有 $2N$ 个点，按顺时针顺序编号为 $1$ 到 $2N$。每个点是黑白两种颜色中的一种。有 $N$ 个白点和 $N$ 个黑点。

我们会画 $N$ 条线段将这些点连接起来，使其满足以下条件：

- 每个点都恰好是一条线段的端点；
- 每条线段都连接一个白点和一个黑点。

在这 $N$ 条线段中，相交的线段对数称为**相交数**。给出每个点的颜色，计算画 $N$ 条线段时最大的相交数。

# 输入格式

第一行一个整数 $N$；

第二行，一个长为 $2N$ 的字符串 $S$，表示每个点的颜色。$S$ 中的每个字符是 $\texttt{B}$ 或 $\texttt{W}$ 中的一种，第 $i\ (1\le i\le 2N)$ 个字符表示的是第 $i$ 个点的颜色。如果是 $\texttt{B}$ 表示这个点是黑色，如果是 $\texttt{W}$ 则表示这个点是白色。

# 输出格式

输出一行到标准输出，输出当画 $N$ 条满足条件的线段时，最大的相交数。

# 样例

#### 样例输入 1

```plain
3
BBWWBW
```

#### 样例输出 1

```plain
2
```

#### 样例说明 1

如果我们按左图绘制线段，那么相交数就是 $2$。另一方面，如果我们按右图绘制线段，那么相交数是 $3$，然而不满足题目描述中的条件。

![monochrome.png](/source/loj/3362/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wOS8wNy81ZjU1ZGVjYjBjN2UwLnBuZw==.png)

#### 样例输入 2

```plain
5
BWBWBBWBWW
```

#### 样例输出 2

```plain
8
```

#### 样例输入 3

```plain
10
WBBBWBBWWBWWBWWBWBWB
```

#### 样例输出 3

```plain
41
```

#### 样例输入 4

```plain
16
WWWBWBBBBWWBWWBWWBBWWBBBWBBBWWBW
```

#### 样例输出 4

```plain
105
```


# 数据范围与提示

对于全部数据，$1\le N\le 2\times 10^5$，保证 $S$ 的长度为 $2N$ 并且只包含 $\texttt{B}$ 与 $\texttt{W}$ 两种字符。并且保证 $\texttt{B}$ 出现 $N$ 次且 $\texttt W$ 也出现 $N$ 次。

详细子任务附加限制与分值如下表：

| 子任务编号 |      附加限制       | 分值 |
| :--------: | :-----------------: | :--: |
|    $1$     |      $N\le 8$       | $4$  |
|    $2$     |     $N\le 300$      | $21$ |
|    $3$     | $N\le 2\times 10^3$ | $10$ |
|    $4$     |     无附加限制      | $65$ |



