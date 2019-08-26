
# 题目描述

**译自 ROI 2018 Regional. Day2 T3.** ***[Красота фейерверка](http://neerc.ifmo.ru/school/archive/2017-2018/ru-olymp-regional-2018-day2.pdf)***

已知一棵包含 $n$ 个元素的有根树 $T^1$。定义 $T^m$ 为一棵树，生成方式是在 $T^{m-1}$ 的每个叶结点下面连一棵 $T^1$ 而得。

![Snipaste_2019-03-20_12-58-47.png](source/loj/3028/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wMy8yMC81YzkxYzhiNWYwMGFkLnBuZw==.png)

试求 $T^m$ 的直径的长度（这里的长度指的是直径上的点数）。

# 输入格式

第一行 $n,m$。  
第二行 $p_2\ldots p_n,\ \ $ $p_i$ 表示结点 $p_i$ 与结点 $i$ 有边连接。

# 输出格式

输出一行一个整数，表示答案。

# 样例

#### 样例输入
```plain
4 2
1 1 2
```

#### 样例输出
```plain
10
```

#### 样例解释
![Snipaste_2019-03-20_13-22-50.png](source/loj/3028/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wMy8yMC81YzkxY2Y0N2Q5YjQ1LnBuZw==.png)

# 数据范围与提示

$3≤n≤2\times 10^5,$ $1≤m≤2\times 10^5.$

|子任务编号|分值|$n$|$m$|
|:-:|:-:|:-:|:-:|
|1|19|$3 ≤ n ≤ 5000$|$m = 1$|
|2|10| |$m=1$|
|3|20|$3 ≤ n ≤ 5000$|$1 ≤ m ≤ 5000$|
|4|19|$3 ≤ n≤ 5000$||
|5|32||&nbsp;|


