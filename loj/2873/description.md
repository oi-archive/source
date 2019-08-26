
# 题目描述

**题目译自 JOISC 2014 Day1 T2「[たのしい家庭菜園](https://www.ioi-jp.org/camp/2014/2014-sp-tasks/2014-sp-d1.pdf)」**

JOI 君对家庭菜园感兴趣。他每年在自家的田地中种植一种叫做 IOI 草的植物。JOI 君的田地沿东西方向被划分为 $N$ 个区域，由西到东标号为 $1\sim N$。IOI 草一共有 $N$ 株，每个区域种植着一株。在第 $i$ 个区域种植的 IOI 草，在春天的时候高度会生长至 $h_i$，此后便不再生长。  
去踏青的 JOI 君注意到，IOI 草的配置与预定的不太一样。IOI 草是一种非常依靠阳光的植物，如果某个区域的 IOI 草的东侧和西侧都有比它高的 IOI 草存在，那么这株 IOI 草就会在夏天之前枯萎。换句话说，为了不让任何一株 IOI 草枯萎，$\forall\ 2\le i\le N-1$，以下两个条件至少满足一个：
* $\forall\ 1\le j\le i-1,\ $ $h_j\le h_i$；
* $\forall\ i+1\le j\le N,\ $ $h_k\le h_i$。

IOI 草非常昂贵，为了不让 IOI 草枯萎，JOI 君需要调换 IOI 草的顺序。IOI 草是一种非常高大且纤细的植物，因此 JOI 君每次只能交换相邻两株 IOI 草。也就是说，JOI 君每次需要选择一个整数 $i$ $(1\le i\le N-1)$，然后交换第 $i$ 株 IOI 草和第 $i+1$ 株 IOI 草。随着夏天临近，IOI 草枯萎的可能性越来越大，因此 JOI 君想让所有 IOI 草都不枯萎。  
现在给出田地的区域数，以及每株 IOI 草的高度，请你求出让所有 IOI 草的不会枯萎的最少操作次数。

# 输入格式

第一行一个正整数 $N$，代表田地被分为了 $N$ 个区域。  
接下来 $N$ 行，第 $i$ 行 $(1\le i\le N)$ 一个整数 $h_i$，表示第 $i$ 株植物在春天时的高度。

# 输出格式

输出一行一个整数，表示最少需要的操作次数。

# 样例

#### 样例输入 1
```plain
6
2
8
4
5
3
6
```

#### 样例输出 1
```plain
3
```

#### 样例说明 1
初始情况：

![JOISC.2014.D1T2.1.png](source/loj/2873/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMTAvMTQvNWJjMjhmMTFkZjNlYy5wbmc=.png)

操作方式：

![JOISC.2014.D1T2.2..png](source/loj/2873/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMTAvMTQvNWJjMjhmMTU1ZDYyYS5wbmc=.png)

#### 样例输入 2
```plain
5
4
4
2
4
4
```

#### 样例输出 2
```plain
2
```

#### 样例说明 2
将第 $3$ 株 IOI 草移动到区域 $1$ 或区域 $5$。

#### 样例输入 3
```plain
4
1
3
4
2
```

#### 样例输出 3
```plain
0
```

# 数据范围与提示

对于所有数据，$3\le N\le 3\times 10^5,$ $1\le D_i \le 10^9$。

|子任务编号|分值|$N$|
|-|-|-|
|1|10|$N\le 8$|
|2|20|$N\le 20$|
|3|15|$N\le 5000$|
|4|55||

