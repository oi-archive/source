
# 题目描述

**本题译自 [eJOI2020](https://ejoi2020.ge/) Problem F.** ***[Dots and Boxes](https://ejoi2020.ge/static/assets/Day2/Problems/Game.pdf)***

Tamta 和 Anna 是姐妹，她们喜欢玩[点格棋](https://zh.wikipedia.org/zh-cn/%E9%BB%9E%E6%A0%BC%E6%A3%8B)。

游戏开始时，有一个由 $(N+1)\times (M+1)$ 个格点组成的网格（即大小为 $N\times M$ 的格子）。玩家轮流在两个*尚未连接*且相邻的两个格点之间添加一条水平或竖直的线段（如果两个格点间距离为 $1$，则称它们相邻）。如果一个玩家在她连线后填满了某个 $1\times 1$ 格子的四个边界，则这个格子就归属与她，她获得一分并且**继续画线**，否则轮到另一位玩家画线。当玩家画不了线时，游戏结束。

当 $N=2,M=3$ 时接下来三轮玩家可能的画线情况如下（虚线表示玩家画的线）。

![game1.png](/source/loj/3378/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8xMS8wOS81ZmE5MWVjYWI2NjZjLnBuZw==.png)

Anna 和 Tamta 已经玩了一会儿。这是你注意到了目前的状态**每个格子都恰好有 $0$ 或 $2$ 条未连线的边，并且现在是 Anna 连线的轮次**。下图为一个当前状态的例子。注意上面第一张图片不符合这里的描述。

![game2.png](/source/loj/3378/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8xMS8wOS81ZmE5NTk5ODBjY2YzLnBuZw==.png)

这个游戏的分值计算为 $S_A-S_T$，$S_A$ 是 Anna 从现在开始所获得的分值，$S_T$ 是 Tamta 获得的分值。显然，Anna 试图最大化这个分值，Tamta 试图最小化这个分值。你需要当玩家双方均采取最优策略时的最终得分。

# 输入格式

输入的第一行包含两个整数 $N$ 和 $M$，表示格子的行数和列数。

接下来 $N+1$ 行，每行包含 $M$ 个数码，每个数码非 $0$ 即 $1$（两个数码之间没有空格），第 $i$ 行的第 $j$ 个数码是 $1$ 当且仅当有一条**水平**线段连接点 $(i,j)$ 和点 $(i,j+1)$。

接下来 $N$ 行，每行包含 $M+1$ 个数码，每个数码非 $0$ 即 $1$（两个数码之间没有空格），第 $i$ 行的第 $j$ 个数码是 $1$ 当且仅当有一条**竖直**线段连接点 $(i,j)$ 和点 $(i+1,j)$。

# 输出格式

输出一行仅一个整数，表示最终得分。

# 样例

#### 样例输入 1

```plain
3 3
000
111
011
110
1010
1000
1001
```

#### 样例输出 1

```plain
-5
```

#### 样例说明 1

样例 $1$ 和一种可能的最优连线顺序如下图所示（边上的数字表示连线的顺序，红色线表示 Anna 的操作，蓝色线表示 Tamta 的操作）。

![game4.png](/source/loj/3378/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8xMS8wOS81ZmE5NWFmNDdlNTJkLnBuZw==.png)

#### 样例输入 2

```plain
5 5
00100
10100
11010
00100
01000
11100
011111
001011
101011
110111
100111
```

#### 样例输出 2

```plain
6
```

#### 样例说明 2

样例 $2$ 的图示如「题目描述」中第二张图所示。

# 数据范围与提示

对于全部数据，满足：

- $3\le N,M\le 20$
- **每个格子都恰好有 $0$ 或 $2$ 条未连线的边**

定义一个连通分量为局面中通过未连线的边互相连通且未被某玩家占有的格子的最大集合。下图中有 $5$ 个不同的连通分量。

![game3.png](/source/loj/3378/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8xMS8wOS81ZmE5NWM5MjFkMDA1LnBuZw==.png)

详细子任务附加限制及分值如下表：

| 子任务编号 |          附加限制          | 分值 |
| :--------: | :------------------------: | :--: |
|    $1$     | 目前局面中只有一个连通分量 | $20$ |
|    $2$     |      $N\cdot M\le 12$      | $20$ |
|    $3$     | 目前局面中只有两个连通分量 | $20$ |
|    $4$     |      $N\le 7,M\le 7$       | $20$ |
|    $5$     |         无附加限制         | $20$ |


---


[点击开始游戏](https://gametable.org/games/dots-and-boxes/)

