
# 题目描述

<!-- Given n, calculate the sum LCM(1,n) + LCM(2,n) + .. + LCM(n,n), where LCM(i,n) denotes the Least Common Multiple of the integers i and n. -->

**原题来自 [SPOJ - LCMSUM](https://www.spoj.com/problems/LCMSUM/)**

给定 $n$，计算下式的值：

$$
\sum_{i=1}^n\text{lcm}(i,n)
$$

其中 $\text{lcm}(i,n)$ 表示 $i,n$ 的最小公倍数。

# 输入格式

<!-- The first line contains T the number of test cases. Each of the next T lines contain an integer n. -->

第一行包含一个整数 $T$，表示数据组数；

接下来 $T$ 行，每行一个整数 $n$。

# 输出格式

<!-- Output T lines, one for each test case, containing the required sum. -->

输出 $T$ 行，每行一个整数，表示这组数据的答案。

# 样例

#### 样例输入
```plain
3
1
2
5
```

#### 样例输出
```plain
1
4
55
```

# 数据范围与提示

<!-- 1<=T<=300000
1<=n<=1000000 -->

对于所有数据，$1\le T\le 3\times 10^5,1\le n\le 10^6$。

