
# 题目描述

这是一道非常简单的数学题。

最近 $LzyRapx$ 正在看 *mathematics for computer science* 这本书，在看到数论那一章的时候， $LzyRapx$ 突然想到这样一个问题。

设 
$$
F(n)=\sum_{i=1}^n\sum_{j=1}^i\frac{\mathrm{lcm}(i,j)}{\mathrm{gcd}(i,j)}
$$

其中，$\mathrm{lcm}(a,b)$ 表示 $a$ 和 $b$ 的最小公倍数，$\mathrm{gcd}(a,b)$ 表示 $a$ 和 $b$ 的最大公约数。

给定 $n$ ，让你求： $F(n) \bmod1000000007$。

$L$ 同学太菜啦，QAQ，并不会做这道简单题，所以他想请你帮他解决这个问题。



# 输入格式

输入一行，一个正整数 $ n\,(1 \le n \le 10^9)$。

# 输出格式

输出 $F(n)$ ，对 $10^9 + 7$ 取模。

# 样例

#### 样例输入

```plain
5
```

#### 样例输出

```plain
84
```


# 数据范围与提示

对于所有数据，$1 \le n \le 10^9$。

