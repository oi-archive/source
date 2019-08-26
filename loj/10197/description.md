
# 题目描述

**原题来自：Waterloo local，题面详见 [POJ 2689](http://poj.org/problem?id=2689)**

给定两个整数 $L,R$，求闭区间 $[L,R]$ 中相邻两个质数差值最小的数对与差值最大的数对。当存在多个时，输出靠前的素数对。

# 输入格式

多组数据。每行两个数 $L,R$。

# 输出格式

详见输出样例。

# 样例

#### 样例输入
```plain
2 17
14 17
```
#### 样例输出
```plain
2,3 are closest, 7,11 are most distant.
There are no adjacent primes.
```

# 数据范围与提示

对于全部数据，$1\le L\lt R\lt 2^{31},R-L\le 10^6$。

