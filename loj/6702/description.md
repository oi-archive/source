
# 题目描述

Tsukimaru 要给自己的比赛出一道签到题。简单来说，这道题只需要选手使用线性筛筛出 $\mu(1), \mu(2), \ldots, \mu(m)$，然后暴力求和即可。

为了防止选手用优于暴力做法的做法碾压正解，导致选手浪费多余的时间，Tsukimaru 给题目增加了一个随机数生成器，以使得除了暴力没有别的做法。

定义函数 `f(k, seed)`：

```cpp
unsigned f(unsigned k, unsigned seed) {
    if (k == 0)
        return 1;

    unsigned t;
    unsigned ans = 0;

    for (t = 1; t <= n; t++) {
        ans += absmu(seed % m + 1) * ~seed * f(k - 1, (seed >> 16) | (seed << 16));
        seed ^= seed << 16;
        seed ^= seed >> 5;
        seed ^= seed << 1;
    }

    return ans;
}
```

其中 $\text{absmu}(p) = |\mu(p)|$。该函数满足：

* 若存在大于 $1$ 的整数 $x$ 使得 $x^2$ 为 $p$ 的因子，则 $\text{absmu}(p) = 0$；
* 否则 $\text{absmu}(p) = 1$。

给出 $n, m, x$，请你求出 `f(6, x)` 的值。

----
Tsukimaru 想出了一个 $O(n^6 \sqrt m)$ 的优秀解法。Tsukimaru 相信没有更优的做法了，于是，他高兴地、蹦蹦跳跳地去找 @[henry_y](https://loj.ac/user/6189) 验题。

> Tsukimaru：帮我验一下这道题  
> henry_y：好  
> henry_y：这个可以加强到 $n = 25, m = 10^7$ 吧  
> Tsukimaru：？

Tsukimaru 认为 henry_y 可以直接 A 掉这道题。

henry_y 说：「黑的实在逼真 =.=，你起码把时限开到每个测试点 $1500\ \text{ms}$ 吧。」

Tsukimaru 觉得 henry_y 说的有道理，于是想让你帮他求 `f(6, x)` 的结果。


# 输入格式

只有一行，三个正整数 $n, m, x$。


# 输出格式

只有一行，一个非负整数，表示答案。


# 样例

#### 样例输入 1
```plain
4 5 19260817
```

#### 样例输出 1
```plain
509600808
```

#### 样例解释 1
$\text{absmu}(1) = 1, \text{absmu}(2) = 1, \text{absmu}(3) = 1, \text{absmu}(4) = 0, \text{absmu}(5) = 1$。

根据以上代码模拟即可得出结果。

# 数据范围与提示

对于 $30\%$ 的数据，$1 \leq n \leq 15, 1 \leq m \leq 1000$。

另外 $70\%$ 的数据，$1 \leq n \leq 25, 5 \times 10^6 \leq m \leq 10^7$。

对于 $100\%$ 的数据，$1 \leq x \leq 10^9$。

欢迎 Hack。如果你发现了可以让标程运行超时的数据，可以在题目讨论提出。

**提醒：如果你希望提出 Hack 数据，请认真检查输入数据中 $n, m$ 的范围是否合法。如果你输入的 $n > 15$，那么 $m$ 必须不小于 $5 \times 10^6$。**

来自 Tsukimaru 的善意提醒：

* 函数中的所有变量和函数返回值的类型都是 `unsigned`；这意味着函数中的所有计算都会自动对 $2^{32}$ 取模。
* 请注意常数因子给程序运行时间带来的影响。

#### 题目信息
* Idea / Std / Data: @[cutekibry](https://loj.ac/user/1408)
* Solution: @[djq_cpp](https://loj.ac/user/3560)
* Testing: @[moonoshawott](https://loj.ac/user/10399)

