
# 题目描述

**题目译自 [PA 2019](https://sio2.mimuw.edu.pl/c/pa-2019-1/dashboard/) Runda 1 [Muzyka pop](https://sio2.mimuw.edu.pl/c/pa-2019-1/p/pop/)**

给定 $ n $ 个整数 $ a_1, a_2, \dots, a_n $ 和一个整数 $ m $。请找到 $ n $ 个非负整数 $ b_1, b_2, \ldots, b_n $，满足 $ 0 \le b_1 < b_2 < \ldots < b_n  \le m $ 并且 $ \sum\limits_{i=1}^{n} \text{popcount}(b_i) \cdot a_i $ 的值最大，其中 $ \text{popcount}(x) $ 为 $ x $ 在二进制下的 $ 1 $ 的个数。

# 输入格式

第一行两个整数 $ n, m $。

第二行包含 $ n $ 个整数 $ a_1, a_2, \dots, a_n $。

# 输出格式

输出一行一个整数，即 $ \sum\limits_{i=1}^{n} \text{popcount}(b_i) \cdot a_i $ 的最大值。

# 样例

#### 样例输入 1
```plain
3 5
2 -1 3
```
#### 样例输出 1
```plain
9
```
#### 样例说明 1
可以取 $ b_1 = 3, b_2 = 4, b_3 = 5$，则答案为 $ 2 \times 2 + (-1) \times 1 + 3 \times 2 = 9$。

#### 样例输入 2
```plain
3 2
1 1 -1
```
#### 样例输出 2
```plain
0
```

# 数据范围与提示

$ 1 \le n \le 200, n - 1  \le m \le 10^{18}, 1 \le |a_i|  \le 10^{14}$

