
# 题目描述

给出数列 $\{a_n\}$，设 $f(l,r)\ =\ (r-l+1)\times max\{a_l,\ldots,a_r\}\times min\{a_l,\ldots,a_r\}$。

求 $max\{f(i,j)\}$，其中 $1\leq i\leq j\leq n$。

# 输入格式

第一行一个数 $n(1\leq n\leq 10^6)$。

第二行 $n$ 个数,第 $i$ 个数表示 $a_i(1\leq a_i\leq 10^6)$。

# 输出格式

一行一个数字代表最大值。

# 样例

#### 输入样例

```plain
5
1 2 3 4 5
```

#### 输出样例

```plain
45
```

#### 样例解释

$f(3,5) = 3 \times 5 \times 3 = 45$ 为所有子区间的最大值。

# 数据范围与提示



