
# 题目描述

**译自 [JOISC 2018](https://www.ioi-jp.org/camp/2018/2018-sp-tasks/index.html) Day2 T3「[最悪の記者 3](https://www.ioi-jp.org/camp/2018/2018-sp-tasks/day2/worst_reporter3.pdf) / [Worst Reporter 3](https://www.ioi-jp.org/camp/2018/2018-sp-tasks/day2/worst_reporter3-en.pdf)」**

在 IOI 2018 的入场仪式上，$N$ 位选手站成一排进入会场。我们不妨用数轴上的点来表示选手的位置。

旗手站在排头。开始时（时刻 $0$），旗手的位置为 $0$，$i$ 号选手的位置为 $-i$。旗手与选手们的移动方向均为数轴的正半轴。

我们用 $D_i$ 来描述 $i$ 号选手的缓慢程度。在每一时刻，旗手会向前走 $1$ 单位距离，$1\sim N$ 号选手依次检查他与前面的人的距离。

* 若距离 $\le D_i$，$i$ 号选手不移动；
* 若距离 $\ge D_i+1$，则 $i$ 号选手会立即向前走，走到距前者的后方 $1$ 单位距离的位置。

有 $Q$ 组查询，第 $j$ 组查询包含三个整数 $L_j, R_j, T_j$，试求：在时刻 $T_j$，有多少个人位于 $L_j$ 到 $R_j$ 之间（含端点）。

# 输入格式

第一行有两个整数 $N,Q$。  
接下来 $N$ 行，每行一个整数 $D_i$。  
接下来 $Q$ 行，每行三个整数 $T_j, L_j, R_j$。

# 输出格式

输出 $Q$ 行，第 $j$ 行有一个整数，表示第 $j$ 组查询的结果。

# 样例

#### 样例输入 1
```plain
3 6
2
5
3
1 2 4
2 2 4
3 2 4
4 2 4
5 2 4
6 2 4
```

#### 样例输出 1
```plain
0
1
1
2
1
2
```

#### 样例说明 1
开始：

<img src="source/loj/2836/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMTIvMDQvNWMwNjE2YmU0ODE0Yi5wbmc=.png" width="80%" />

时刻 1：

<img src="source/loj/2836/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMTIvMDQvNWMwNjE2YmVlYmRmZS5wbmc=.png" width="80%" />

时刻 2：

<img src="source/loj/2836/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMTIvMDQvNWMwNjE2YzAxMjUzNi5wbmc=.png" width="80%" />

时刻 3：

<img src="source/loj/2836/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMTIvMDQvNWMwNjE2YzAxNjE0NC5wbmc=.png" width="80%" />

时刻 4：

<img src="source/loj/2836/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMTIvMDQvNWMwNjE2YzA2MTE2NS5wbmc=.png" width="80%" />

时刻 5：

<img src="source/loj/2836/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMTIvMDQvNWMwNjE2YzA2MDQxNi5wbmc=.png" width="80%" />

时刻 6：

<img src="source/loj/2836/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMTIvMDQvNWMwNjE2YzIxZjE2MC5wbmc=.png" width="80%" />

#### 样例输入 2
```plain
4 2
1
1
1
1
2 1 4
1 3 6
```

#### 样例输出 2
```plain
2
0
```

#### 样例输入 3
```plain
6 6
11
36
28
80
98
66
36 29 33
190 171 210
18 20 100
1000 900 1100
92 87 99
200 100 300
```

#### 样例输出 3
```plain
1
6
0
5
2
7
```

# 数据范围与提示

对于所有测试数据，$1\le N,Q\le 5\times 10^5,$ $1\le D_j, T_j\le 10^9,$ $1\le L_j\le R_j\le 10^9$。

|子任务编号|分值|特殊限制|
|-|-|-|
|1|7|$D_i=1$|
|2|12|$N,Q\le 1000,$ $T_j,L_j,R_j\le 1000$|
|3|81|无特殊限制|

