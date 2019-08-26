
# 题目描述

给 $n$ 个二维点 $(a_i,b_i)$，询问有多少种排列 $p$（答案对 $10^9+7$ 取模）使得执行以下伪代码后留下的点是 $i$，即最后 $\text{saved} = i$。

```
saved = p[1]
for x from 2 to n
    if a[p[x]] >= a[saved] and b[p[x]] >= b[saved]
        saved = p[x]
```
保证 $a$ 和 $b$ 分别为一个排列。

# 输入格式

第一行一个整数 $n$，接下来 $n$ 行每行两个整数表示一个点。

# 输出格式

输出 $n$ 行，每行一个整数表示留下的点为 $i$ 的排列种数。

# 样例

#### Input
```plain
3
1 2
2 3
3 1
```
#### Output
```plain
0
4
2
```

# 数据范围与提示

$n \le 100000$

$1 \leq a_i, b_i \leq n$  
$a_i \neq a_j, b_i \neq b_j \ \forall 1 \leq i \lt j \leq n$

