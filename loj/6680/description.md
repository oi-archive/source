
# 题目描述

*感谢 @reek 提出本题题意，@_rqy 提供本题社论。*

某一天，你发现了一个神奇的函数 $g(x)$，它满足很多神奇的性质：

1. $g(1)=1$。
2. $g(p^c)=p \oplus c$（$p$ 为质数，$\oplus$ 表示异或）。
3. $g(ab)=g(a)g(b)$（$a$ 与 $b$ 互质）。

你看到这个函数之后十分高兴，于是就想要求出 $\sum_{i=1}^n g(i)$。

----

然而你始终想不出来这道题怎么做。于是，百思不得其解的你去问了 @[henry_y](https://loj.ac/user/6189)。 

henry_y：这不是 [LibreOJ 原题](https://loj.ac/problem/6053)么？ 

henry_y 觉得这道题太简单，于是给你出了另一道题。

设

$$f(n) = \left( \sum_{i = 1}^n \left\lfloor \frac ni \right\rfloor^2 g(i) \right) \bmod 998244353$$

求出 $f(1) \oplus f(2) \oplus \ldots \oplus f(n)$ 的值。

# 输入格式

只有一行，一个正整数 $n$。


# 输出格式

只有一行，一个整数，表示答案。

# 样例

#### 输入样例 1
```plain
5
```

#### 输出样例 1
```plain
61
```

#### 样例解释 1
$f(1) = 1 \times g(1) = 1$；

$f(2) = 4 \times g(1) + 1 \times g(2) = 4 + 3 = 7$；

$f(3) = 9 \times g(1) + 1 \times g(2) + 1 \times g(3) = 9 + 3 + 2 = 14$；

$f(4) = 16 \times g(1) + 4 \times g(2) + 1 \times g(3) + 1 \times g(4) = 16 + 12 + 2 + 0 = 30$。

$f(5) = 25 \times g(1) + 4 \times g(2) + 1 \times g(3) + 1 \times g(4) + 1 \times g(5) = 25 + 12 + 2 + 0 + 4 = 43$。

答案为 $1 \oplus 7 \oplus 14 \oplus 30 \oplus 43 = 61$。

#### 输入样例 2
```plain
10
```

#### 输出样例 2
```plain
207
```

#### 样例解释 2
答案为 $1 \oplus 7 \oplus 14 \oplus 30 \oplus 43 \oplus 81 \oplus 100 \oplus 137 \oplus 165 \oplus 235 = 207$。

#### 输入样例 3
```plain
10000
```

#### 输出样例 3
```plain
287416092
```

# 数据范围与提示

**Update 2019/7/10 20:23：已将时间限制放宽至 1500ms。但标程每个测试点运行时间不超过 500ms，请尽可能地注意常数因子给程序复杂度带来的影响。**

对于 $10\%$ 的数据，$n \leq 100$。

对于 $30\%$ 的数据，$n \leq 50000$。

对于 $50\%$ 的数据，$n \leq 10^6$。

对于 $100\%$ 的数据，$n \leq 10^7$。

