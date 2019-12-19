
# 题目描述

**题目译自 [PA 2019](https://sio2.mimuw.edu.pl/c/pa-2019-1/dashboard/) Runda 1 [Wina](https://sio2.mimuw.edu.pl/c/pa-2019-1/p/win/)**

有 $ n $ 行总共 $ \frac{n(n + 1)}{2} $ 个数叠成了一个数塔，从上往下数第 $ i $ 行里面恰好有 $ i $ 个数。

给定 $ k $，你需要从中拿走恰好 $ k $ 个数，使得拿走的数的最小值最小。一个数能被拿走当且仅当它左上角和右上角都没有数或者那个数已经被拿走了。

# 输入格式

第一行两个正整数 $ n $ 和 $ k $。

接下来 $ n $ 行，第 $ i $ 行有 $ i $ 个正整数 $ a_{i, 1}, a_{i, 2} \ldots, a_{i, i} $，其中 $ a_{i, j} $ 表示从上往下第 $ i $ 行从左往右第 $ j $ 个数。

# 输出格式

输出一行一个整数，即拿走的数的最小值的最小值。

# 样例

#### 样例输入
```plain
5 7
1999
2019 2010
850 1500 1600
900 900 710 900
1000 800 600 800 1000
```
#### 样例输出
```plain
710
```
#### 样例说明
左边为数塔，右边为最优拿数顺序。

![win.png](/source/loj/3216/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8xMi8xOS81ZGZiMDc4ZWM4MWEwLnBuZw==.png)

# 数据范围与提示

$1 \le n \le 2\times 10^3, 1 \le k \le \frac{n(n + 1)}{2}, 1 \le a_{i, j} \le 2019$

