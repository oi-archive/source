
# 题目描述

**译自 [CCO 2017](https://cemc.math.uwaterloo.ca/contests/computing/2017/) Day2 「[Rainfall Capture](https://cemc.math.uwaterloo.ca/contests/computing/2017/stage%202/day2.pdf)」**

晚上，夜黑风高，大雨疯狂地从天而降。

Lucy 想要接住一些雨滴，但她只有有限的工具。她有一套不同高度的柱子来接住雨滴。每根柱子的高度为整数，宽度为 $1$。她排列好柱子之后，就会用其他器具夹紧柱子，来让雨滴顺利地储存在柱子的间隙里。你可以认为雨滴的数量是无限的。

举个例子，如果 Lucy 有高度分别为 $(1, 5, 2, 1, 4)$ 的五根柱子，她可以这样排列柱子。

![e](source/loj/2753/img/aHR0cHM6Ly9zMS5heDF4LmNvbS8yMDE4LzA4LzA3L1BzM1VvUS5wbmc=.png)

这样会接住 $5R$ 雨滴（$R$ 代表 $1$ 个单位的雨滴）。

**为了方便表述，我们定义 $R$ 为雨滴的单位。**

![e](source/loj/2753/img/aHR0cHM6Ly9zMS5heDF4LmNvbS8yMDE4LzA4LzA3L1BzM3dKcy5wbmc=.png)

当然了，她也可以这样摆放柱子，这样可以接住 $6R$ 雨滴。

![e](source/loj/2753/img/aHR0cHM6Ly9zMS5heDF4LmNvbS8yMDE4LzA4LzA3L1BzM05kZy5wbmc=.png)

再举一个例子，如果柱子的高度分别为 $(5,1,5,1,5)$，Lucy 可以接住 $8R$ 雨滴。

![e](source/loj/2753/img/aHR0cHM6Ly9zMS5heDF4LmNvbS8yMDE4LzA4LzA3L1BzM2Rpai5wbmc=.png)

最后一个例子，如果柱子的高度分别为 $(5,1,4,1,5)$，她可以接住 $9R$ 雨滴。

![e](source/loj/2753/img/aHR0cHM6Ly9zMS5heDF4LmNvbS8yMDE4LzA4LzA3L1BzM3RlUy5wbmc=.png)

Lucy 有 $N$ 个高度为 $h_1,h_2,...h_N$ 的柱子。她想知道，在所有可能的摆放方案中，所有可能的雨滴量（以 $R$ 为单位）是多少。（具体可看样例解释）

# 输入格式

第一行输入柱子的个数 $N$；

下一行输入柱子的高度 $h_i$。

# 输出格式

输出只有一行，把所有可能接住的雨滴数量（以 $R$ 为单位）按照升序输出。

# 样例

#### 样例输入 1
```plain
5
1 5 2 1 4
```
#### 样例输出 1
```plain
0 1 2 3 4 5 6 8 
```
#### 样例解释 1
参见上文第一个例子

#### 样例输入 2
```plain
5
5 1 5 1 5
```
#### 样例输出 2
```plain
0 4 8
```
#### 样例解释 2
参见上文第二个例子

#### 样例输入 3
```plain
5
5 1 4 1 5
```
#### 样例输出3
```plain
0 1 3 4 5 6 7 8 9
```
#### 样例解释 3
参见上文第三个例子

# 数据范围与提示

对于 $20\%$的数据，$N \le 10$；

对于另外$40\%$的数据，$N \le 50$；

对于全部数据，$2 \le N \le 500,1\le h_i\le 50$。

