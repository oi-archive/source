
# 题目描述

**译自 [CCO 2017](https://cemc.math.uwaterloo.ca/contests/computing/2017/) Day2 「[Shifty Grid](https://cemc.math.uwaterloo.ca/contests/computing/2017/stage%202/day2.pdf)」**

给你一个二维数组。我们只能通过**移动 (_Shift_) **操作来改动这个数组。一次移动操作可以将一行元素向左（或向右）移几个单位；或将一列元素向上（或向下）移几个单位。如果被移动的元素越界，则将越界元素移动到该行或列的另一侧。

举个例子：

![aa](source/loj/2755/img/aHR0cHM6Ly9zMS5heDF4LmNvbS8yMDE4LzA4LzA4L1B5a2NLcy5wbmc=.png)

将第二列向下移动 $1$ 个单位（或向上移动 $3$ 个单位），二维数组将会变成这样：

![a](source/loj/2755/img/aHR0cHM6Ly9zMS5heDF4LmNvbS8yMDE4LzA4LzA4L1B5a3l2ai5wbmc=.png)

一次移动 $K$ 个单位的**左移**操作等价于移动 $N-K$ 个单位的**右移**操作。在列上的变换同样。

因此，我们规定只有**下移**和**右移**操作。

在一个 $N \cdot M$ 的二维数组中，所有的数各不相同，且 $\text{Num}_{ij} \in [0,N-1]$（规定第 $i$ 行 $j$ 列的数编号为 $\text{Num}_{ij}$）。

在第一个例子中，我们给你的二维数组非常**和谐**，我们叫它**和谐数组 (_Solved_)**。一个二维数组当且仅当第一行的元素按照升序编号分别为从 $0$ 到 $M-1$，第二行元素为从 $M$ 到 $2M-1$，以此类推时，我们称它为**和谐数组**。

你的任务是找到一系列的操作，使得二维数组变成**和谐数组**。

# 输入格式

第一行为两个整数 $N,M$；

下面的 $N$ 行将会包含 $M$ 个代表二维数组的正整数。

# 输出格式

按照下列标准，输出一系列的**移动**操作。

1.  第一行输出移动的步数 $K$。
2.  下面的 $K$ 行输出：$1 \ i \ r (1 \le i \le N, 0 \le r \lt M)$，代表使第 $i$ 行**右移** $r$ 格，或 $ 2 \ j \ d (1 \le j \le M, 0 \le d \lt N)$，代表使第 $j$ 列**下移** $d$ 格。

# 样例

#### 样例输入1
```plain
2 4
4 2 3 0
1 5 6 7
```
#### 样例输出 1
```plain
2
2 1 1
1 1 1
```
#### 样例解释 1
经过如下变换：

![](source/loj/2755/img/aHR0cHM6Ly9zMS5heDF4LmNvbS8yMDE4LzA4LzEwL1A2VTkwSS5wbmc=.png)

#### 样例输入 2
```plain
4 2
2 3
5 0
4 1
6 7
```
#### 样例输出 2
```plain
7
1 1 1
2 1 1
1 2 1
1 3 1
2 1 2
1 1 1
2 1 1
```
#### 样例解释 2
经过如下变换：

![](source/loj/2755/img/aHR0cHM6Ly9zMS5heDF4LmNvbS8yMDE4LzA4LzA4L1B5a3I4Zy5wbmc=.png)

# 数据范围与提示

$N,M$ 永远为偶数，$K \le 10^5$。

对于 $20 \% $ 的数据，$N \times M \le 8$；  
对于另外 $40 \%$ 的数据，$K \le 2$；  
对于 $100 \% $ 的数据，$2 \le N,M \le 100$。

如果数组本身就是**和谐数组**，输出 $0$。

