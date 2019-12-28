
# 题目描述

**题目译自 [USACO 2017 December Contest, Platinum](http://usaco.org/index.php?page=dec17results) Problem 3. [Greedy Gift Takers](http://usaco.org/index.php?page=viewproblem2&cpid=770)**

$N$ 头奶牛排成一列，准备领礼物。此时，奶牛们依次编号为 $1 \ldots N$。农夫约翰站在队头发礼物。

奶牛 $i$ 的权值为 $c_i$，每个到达队头的牛拿到礼物后会插队，插进倒数第 $c_i + 1$ 的位置。现在我们想知道，有多少奶牛不可能领到礼物。


# 输入格式

第一行一个数表示 $N$；  
第二行 $N$ 个数表示 $c_1,c_2,\dots, c_n$。

# 输出格式

一行一个数表示答案。

# 样例

#### 样例输入
```plain
3
1 2 0
```

#### 样例输出
```plain
1
```

# 数据范围与提示

对于全部数据，$1\le N\le 10^5, 0\le c_i\le N-1$。

