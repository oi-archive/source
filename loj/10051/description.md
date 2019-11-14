
# 题目描述

**原题来自：[CODECHEF September Challenge 2015 REBXOR](https://www.codechef.com/problems/REBXOR)**

给定一个含 $N$ 个元素的数组 $A$，下标从 $1$ 开始。请找出下面式子的最大值：$(A[l_1]\bigoplus A[l_1+1]\bigoplus …\bigoplus A[r_1])+ (A[l_2]\bigoplus A[l_2+1]^…\bigoplus A[r_2])$，其中$ 1\le l_1\le r_1<l_2\le r_2\le N$，$x\bigoplus y$ 表示 $x$ 和 $y$ 的按位异或。

# 输入格式

输入数据的第一行包含一个整数 $N$，表示数组中的元素个数。

第二行包含 $N$ 个整数 $A[1],A[2],\ldots ,A[N]$。

# 输出格式

输出一行包含给定表达式可能的最大值。

# 样例

#### 样例输入
```plain
5
1 2 3 1 2
```
#### 样例输出
```plain
6
```
#### 样例解释
满足条件的 $(l_1,r_1,l_2,r_2)$ 有：$(1,2,3,3),(1,2,4,5),(3,3,4,5)$。

# 数据范围与提示

对于 $100\%$ 的数据，$2\le N \le 4\times 10^5, 0\le A_i\le 10^9$。

