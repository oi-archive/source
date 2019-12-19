
# 题目描述

**题目译自 [PA 2019](https://sio2.mimuw.edu.pl/c/pa-2019-1/dashboard/) Runda próbna [A + B](https://sio2.mimuw.edu.pl/c/pa-2019-1/p/apb/)，感谢 [zimpha](https://github.com/zimpha) 提供 PA 2019 的题目翻译和官方数据。**

在列竖式计算两个十进制数的和的时候，人们可能会错算成这样：

![apb.png](/source/loj/3214/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8xMi8xOC81ZGY5ZjNlMzUxZWIwLnBuZw==.png)

在图里的左边，$ 248 + 208 $ 被错算成了 $4416$。

给定正整数 $ n $，问有多少对非负整数 $ a, b $ 满足 $ a + b $ 会被错算成 $ n $。

注意：$ a $ 可以等于 $ b $，且 $ a = 1, b = 2 $ 和 $ a = 2, b = 1 $ 是两种不同的方案。

# 输入格式

第一行包含一个正整数 $n$。


# 输出格式

输出一个整数，即满足条件的 $ a, b $ 的数量。


# 样例

#### 样例输入
```plain
112
```

#### 样例输出
```plain
50
```


# 数据范围与提示

对于 $100\%$ 的数据，保证 $1 \le n < 10^{18}$


