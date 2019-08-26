
# 题目描述

设 $f(n)=\prod_{i=1}^{n}(2i-1)$，给定 $n,m,x$，求：

$$
\sum_{i=0}^{n}\sum_{j=0}^{m} f(i \text{ xor } j \text{ xor } x)
$$

特别的，$f(0)=0$。

由于答案巨大无比，因此你只需要使用 `unsigned int` 自然溢出即可。


# 输入格式

一行三个整数 $n,m,x$。

# 输出格式

一行一个整数表示答案。

# 样例

#### 样例输入

``` plain
1073740936 1073740828 260741043
```

#### 样例输出

``` plain
431358029
```


# 数据范围与提示

$1 \le n,m,x \le 2^{30}$

![256.png](source/loj/6668/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNi8xNy81ZDA3OGZmNDRmMmY4LnBuZw==.png)

