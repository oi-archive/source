
# 题目描述

把一个 $n \times m$ 的棋盘染成黑白两色，要求黑色的块全部四连通，白色的块也全部四连通。问有多少种方案？

四连通：一个格子与上、下、左、右四个方向的格子有连通。

# 输入格式

输入三个数 $n, m, p$。

# 输出格式

输出答案模 $p$。

# 样例

#### 样例输入 1
```plain
2 2 998244353
```

#### 样例输出 1
```plain
14
```

#### 样例输入 2
```plain
3 3 998244353
```

#### 样例输出 2
```plain
108
```

#### 样例解释 2
![](source/loj/6385/img/aHR0cHM6Ly9hY20uZWNudS5lZHUuY24vdXBsb2FkLzM1NjgvY2hlc3Nfc2FtcGxlLnpQRDZyQ05QLnBuZw==.png)

# 数据范围与提示

$1 \le m \le 8$；$1 \le n \cdot m \le 10^4$；$2 \le p \le 10^9$；$p$ 是质数。

