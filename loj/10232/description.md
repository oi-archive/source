
# 题目描述

有下面这样的一个网格棋盘，$a,b,c,d$ 表示了对应边长度，也就是对应格子数。

![place1.png](/source/loj/10232/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wNS8wNC81ZWFlZjBjOGE5ZDAzLnBuZw==.png)

当 $a=b=c=d=2$ 时，对应下面这样一个棋盘：

![place2.png](/source/loj/10232/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wNS8wNC81ZWFlZjBjODc4ZTQ5LnBuZw==.png)

要在这个棋盘上放 $k$ 个相互不攻击的车，也就是这 $k$ 个车没有两个车在同一行，也没有两个车在同一列，问有多少种方案。同样只需要输出答案 $\bmod 10^5+3$ 后的结果。

# 输入格式

第一行为有五个非负整数 $a, b, c, d$ 和 $k$。

# 输出格式

包括一个正整数，为答案 $\bmod 10^5+3$ 后的结果。

# 样例

#### 样例输入
```plain
2 2 2 2 2
```
#### 样例输出
```plain
38
```

# 数据范围与提示

对于全部数据，$1\le a,b,c,d,k\le 1000$，且保证了至少有一种可行方案。

