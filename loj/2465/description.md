
# 题目描述

**译自 POI 2014 Stage 2. Day 1「[Criminals](https://szkopul.edu.pl/problemset/problem/APWi6y6XTt5ujve8ynI_FNJ1/site/?key=statement)」**

两个罪犯 Bitie 和 Bytie 抢劫 $n$ 个房子，每个房子有一个颜色，Bitie从低编号到高编号，Bytie从高编号到低编号，直到相遇为止。已知罪犯开始时所在房子颜色相同（但不知道是什么颜色），并且知道罪犯依次抢劫的所有房子的颜色，且每个罪犯对每种颜色的房子分别最多抢劫一次，求所有可能的相遇点。

# 输入格式

第一行两个整数 $n,k$ ，分别表示房子的个数和不同的颜色数。颜色以从 $1$ 到 $k$ 的整数标号。

接下来一行有 $n$ 个整数 $c_1,c_2,...,c_n (1 \le c_i \le k)$，表示房子的颜色。

第三行有两个整数 $m,l (1 \le m,l \le n,m+l \le n-1)$，分别表示 Bitie 和 Bytie 抢劫房子的个数。

第四行有 $m$ 个两两不同的整数 $x_1, x_2, ..., x_m (1 \le x_i \le k)$，表示 Bitie 抢劫房子的颜色（不包括 Bitie 开始时所在房子的颜色）。

第五行有 $l$ 个两两不同的整数 $y_1, y_2, ..., y_l (1 \le y_i \le k)$，表示 Bytie 抢劫房子的颜色 （不包括 Bytie 开始时所在房子的颜色）。

保证 $x_m = y_l$.

# 输出格式

 输出两行，第一行一个整数，表示可能相遇的房子个数，第二行升序输出可能相遇的房子编号。

# 样例

#### 样例输入
```plain
15 7
2 5 6 2 4 7 3 3 2 3 7 5 3 6 2
3 2
4 7 3
5 3
```

#### 样例输出
```plain
3
7 8 10
```

#### 样例解释

![image](/source/loj/2465/img/aHR0cHM6Ly9zemtvcHVsLmVkdS5wbC9wcm9ibGVtc2V0L3Byb2JsZW0vQVBXaTZ5NlhUdDV1anZlOHluSV9GTkoxL3NpdGUvaW1hZ2VzL09JMjEvcHJ6LnBuZw==.png)

样例中，罪犯可能住在颜色为 $2$ （此时 Bitie 在 $1$ 或 $4$ 号房子，Bytie 在 $15$ 号房子）或 $6$ 的房子（此时 Bitie 在 $3$ 号房子，Bytie 在 $14$ 号房子）中。无论 Bitie 住在 $1$ 号还是 $4$ 号房子，他都可以抢劫 $5$ 号房子（颜色为 $4$），$6$ 号房子（颜色为 $7$），然后任选 $7$，$8$ 或 $10$ 中的一个（颜色为 $3$）。而 Bytie 可以抢劫 $12$ 号房子（颜色为 $5$），然后与 Bitie 在 $7$, $8$, $10$ 号房子（颜色为 $3$）相遇。上图描述了 Bitie 住在 $1$ 号房子且两罪犯在 $8$ 号房子相遇的情况。

# 数据范围与提示

对于 $100\%$ 的数据， $3 \le n \le 1000000,1 \le k \le n,k \le n$ 。

