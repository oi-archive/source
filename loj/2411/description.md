
# 题目描述

四环路上行人稀，常有车神较高低。

如今车道依旧在，不见当年老司机。

B 君心情不好的时候，喜欢去四环路上飙车。看着窗外飞驰而过的景色，B 君想到了过去的 R 君和 G 君；想到了现在的 YJQ 和 FLZ；想到了宇宙之浩渺，时空之无限；也想到了这道题。

输入 $n, X, Y, Z$，保证 $X$ 是 $2$ 的整数次幂，$Y$是 $3$ 的整数次幂，$Z$ 是 $5$ 的整数次幂，同时 $1 \leq n \leq 1000, 1 \leq XYZ \leq 2000$。

输入四个长度为 $n$ 的数组 $\{a_i\}, \{b_i\}, \{c_i\}, \{r_i\}(0 \leq a_i, b_i, c_i, r_i \leq 1000000000)$

对于 $(u, v, w)$ 求有多少组解 $\{x_i\}, \{y_i\}, \{z_i\}$

满足对于所有的 $i$，有 $a_i \le x_i, b_i \le y_i, c_i \le z_i, r_i \ge x_i - a_i + y_i - b_i + z_i - c_i$

并且

$$\left(\sum_{i=1}^{n} x_i \right)\bmod X = u$$

$$\left( \sum_{i=1}^{n} y_i \right) \bmod Y = v$$

$$\left(\sum_{i=1}^{n} z_i \right)\bmod Z = w$$

设解的个数为 $F(u, v, w)$

输出

$$\mathop{\mathrm{xor}} \limits_{\substack{0 \leq u < X \\ 0 \leq v < Y \\ 0 \leq w < Z}} ((u  Y  Z + v  Z + w) \times (F(u, v, w) \bmod 466560001))$$

# 输入格式

输入第一行 $n, X, Y, Z$。

接下来 $n$ 行，第 $i$ 行四个整数 $a_i, b_i, c_i, r_i$。


# 输出格式

一行一个整数表示答案。


# 样例

#### 样例输入 1
```plain
3 2 3 1
0 0 0 1
0 0 0 2
0 0 0 3
```

#### 样例输出 1
```plain
573
```

#### 样例输入 2
```plain
3 2 3 5
0 0 0 1
0 0 0 2
0 0 0 3
```

#### 样例输出 2
```plain
253
```


# 数据范围与提示



