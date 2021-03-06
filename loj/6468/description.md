
# 题目描述

达拉然国中有一条长为 $n$ 的街道，其中住了 $q$ 个法师,并且街道中每一户仅存在一种法力水晶 $a_i$  。

法师们会一种神奇的法术，就是瞬间收集一个法力水晶，其需要消耗的法力值就是该法师到法力水晶的距离。

每个法师都喜欢一些法力水晶，并且喜欢的种类都恰好是一个连续的区间 $[l, r]$ 。

他想收集到街道中每一种他喜欢并且**存在**的法力水晶，**每一种只需收集一个**。

而法师很懒，呆在他所在的位置 $p$ 不会走动，他想知道最少需要耗费多少法力值才能满足要求。

# 输入格式

第一行两个整数 $n, q$。  
第二行共 $n$ 个整数,其中第 $i$ 个为 $a_i$ 。  
接下来共 $q$ 行,每行三个整数 $p, l, r$ 。

# 输出格式

共 $q$ 行,每行一个整数,其中第 $i$ 个为第 $i$ 个法师的需要的花费的最小法力值。

# 样例

#### 样例输入
```plain
5 4
1 5 3 3 1
3 3 4
4 4 5
2 1 4
5 3 5
```
#### 样例输出
```plain
0
2
2
4
```
#### 样例解释
第一个法师在 $3$ 处，喜欢的种类是 $\{3, 4\}$ 但由于 $\{4\}$ 不存在，只需要找到 $\{3\}$，
它位置上刚好有一个为 $3$ 的法力水晶，故最小消耗为 $0$ 。

第二个法师只需取 $\{a_2 = 5\}$ ，那么消耗为 $| 2 - 4 | = 2$ 。

第三个法师取最近的两个即可，取 $\{a_1=1, a_3=3\}$ ，消耗为 $| 1 - 2 | + | 3 - 2 | = 2$ 。

第四个法师取 $\{a_4=3, a_2=5\}$ ，消耗为 $|4 - 5| + |2 - 5| = 4$ 。


# 数据范围与提示

对于 $30 \%$ 的数据满足 $1\le n, q \le 1000$ 。  
另有 $10 \%$ 的数据满足 $a_i = i$ 。  
另有 $30 \%$ 的数据满足 $\forall i, l_i =1, r_i = n$ 。  
对于 $100 \%$ 的数据满足 $1\le n, q \le 2 \times 10^5$ ， $1\le l, r, p, a_i \le n$。

