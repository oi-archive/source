
# 题目描述

从前有个 alpha1022，他在看某本奇妙的书的时候想到了这样一个函数：  
$$f(n) = \prod\limits_{d|n} \mu(d)$$
然后就有了这样一个问题：
$$\sum\limits_{i=1}^n f(i) \bmod 998244353$$
然后他就把这个问题扔给了你。

# 输入格式

第一行，一个正整数 $n$。

# 输出格式

一行一个非负整数，表示答案。

# 样例

#### 样例输入 1
```plain
5
```

#### 样例输出 1
```plain
998244351
```

#### 样例输入 2
```plain
987654
```

#### 样例输出 2
```plain
445190
```

# 数据范围与提示

对于 $20\%$ 的数据，$n \le 10^6$；  
对于 $40\%$ 的数据，$n \le 10^7$；  
对于 $100\%$ 的数据，$n \le 10^{10}$。

