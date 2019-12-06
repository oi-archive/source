
# 题目描述

有一天 LoliconAutomaton 梦到了下面这个问题：

$$
\sum\limits_{i=1}^{n}\sum\limits_{j=1}^{n}\sum\limits_{k=1}^{n}[(j\mid i) \land ((j+k)\mid i)]
$$

其中，$(j\mid i) \land ((j+k)\mid i)$ 指 $j$ 整除 $i$ 并且 $j+k$ 也整除 $i$。

但是 LoliconAutomaton 的数学实在是太差啦！你能帮一帮他吗？

# 输入格式

输入包含一个正整数 $n$。

# 输出格式

输出包含一个正整数即题目要求的答案，由于答案可能会很大，你只需要输出答案对 $998244353$ 取模后的结果即可。

# 样例

#### 样例输入
```plain
7
```
#### 样例输出
```plain
13
```

# 数据范围与提示

对于全部数据，$1\le n\le 10^{10}$。

