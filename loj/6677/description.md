
# 题目描述

> <span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 喜欢计数，也喜欢菱形。

某天 <span style="font-weight:bold"><span style="color:gray">FFjet</span></span> 送给 <span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> ~~超炮里面的激光武器同款~~六边形板子，长成这样：

![ZMo2kt.md.png](/source/loj/6677/img/aHR0cHM6Ly9zMi5heDF4LmNvbS8yMDE5LzA2LzI4L1pNbzJrdC5tZC5wbmc=.png)

<span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 一眼就看出，它里面有很多菱形！如下图所示：

![ZMTwEn.md.png](/source/loj/6677/img/aHR0cHM6Ly9zMi5heDF4LmNvbS8yMDE5LzA2LzI4L1pNVHdFbi5tZC5wbmc=.png)

<span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 十分开心。现在他想让你求出，对于边长分别为 $a, b, c$ 的划分为等边三角形的六边形，有多少种不同的使得它们可以划分为菱形的方案？答案对 $998244353$ 取模。

这里给一个例子，$a=b=c=2$ 时，有 $20$ 种不同的划分方案：

![ZMT7vD.md.png](/source/loj/6677/img/aHR0cHM6Ly9zMi5heDF4LmNvbS8yMDE5LzA2LzI4L1pNVDd2RC5tZC5wbmc=.png)

# 输入格式

一行三个正整数 $a, b, c$。

# 输出格式

一行一个正整数表示答案。

# 样例

#### 样例输入 1
```plain
2 2 2
```

#### 样例输出 1
```plain
20
```

#### 样例输入 2
```plain
2 3 3
```

#### 样例输出 2
```plain
175
```


# 数据范围与提示

对于 $20\%$ 的数据，满足 $1\leqslant a,b,c\leqslant 5$；

对于 $50\%$ 的数据，满足 $1\leqslant a, b, c\leqslant 500$；

对于 $100\%$ 的数据，满足 $1\leqslant a, b, c \leqslant 10^6$。

