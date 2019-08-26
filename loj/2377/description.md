
# 题目描述

给定一个长度为 $n$ 的字符串 $S$ ，令 $T_i$ 表示它从第 $i$ 个字符开始的后缀，求：
$$\sum_{1 \le i < j \le n} \operatorname{len}(T_i)+\operatorname{len}(T_j)-2\operatorname{lcp}(T_i,T_j)$$

# 输入格式

一行，一个字符串 $S$ 。

# 输出格式

一行，一个整数，表示所求值。

# 样例

### 样例输入
```plain
ababc
```

### 样例输出
```plain
54
```

# 数据范围与提示

对于 $100\%$ 的数据， $2 \le n \le 500000$。

