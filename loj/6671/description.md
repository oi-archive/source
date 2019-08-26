
# 题目描述

> <span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 是组合计数大师。

<span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 很喜欢玩麦块。当然，<span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 拥有非同常人的超能力，他玩的是魔改版的 $n$ 维麦块，换成数学语言也就是 $\mathbb Z^n$ 空间。他现在手里有一个特制的炸药方块：若将它放在 $(x_1,x_2,\dots,x_n)$（注意 $x_i$ 可能为负数）处，它将拥有 $\displaystyle \sum_{i=1}^{n}\left|x_{i}\right|$ 的威力值。<span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 只是想看看这种特制炸药的爆炸场面，他并不希望对其他东西造成太大的损害，所以这个炸药方块的威力值必须 $\leqslant p$。

<span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 想请你告诉他，一共有多少不同的位置放置炸药，使其满足他的要求。答案对 $10^9+7$ 取模。

> <span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 想了一秒就知道了答案。但他决定还是考考你。

# 输入格式

一行两个数 $n,p$，含义见题目描述。

# 输出格式

一行一个整数表示答案。

# 样例

#### 样例输入

```plain
3 5
```

#### 样例输出

```plain
231
```

# 数据范围与提示

对于 $10\%$ 的数据，$n,p\leqslant 5$

对于 $50\%$ 的数据，$n,p \leqslant 1000$

对于 $100\%$ 的数据，$n,p \leqslant 10^6$

Bonus：$n \leqslant 10^6, p \leqslant 10^9$


