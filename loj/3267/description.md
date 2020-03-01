
# 题目描述

**题目译自 [USACO 2020 Feburary Contest, Platinum](http://usaco.org/index.php?page=feb20results) Problem 3. [Help Yourself](http://usaco.org/index.php?page=viewproblem2&cpid=1022)**

Bessie 现在有 $N$ 条在一条数轴上的线段，第 $i$ 条线段覆盖了 $[l_i,r_i]$ 的所有实数。

定义一个线段集合的**并**为所有至少被一条线段覆盖的实数。定义一个线段集合的**复杂度**为该集合并的联通块个数的 $K$ 次方。

Bessie 现在想计算这 $N$ 条线段的 $2^N$ 个子集的复杂度之和模 $10^9+7$。通常你的任务是帮 Bessie 进行计算，但是这次你是 Bessie，而且没人能帮你，帮帮你自己吧！

# 输入格式

第一行两个空格分隔的整数 $N,~K$。

接下来 $N$ 行每行两个空格分隔的整数 $l_i,~r_i$

# 输出格式

输出所求的值模 $10^9+7$。


# 样例

#### 样例输入

```plain
3 2
1 6
2 3
4 5
```

#### 样例输出

```plain
10
```

#### 样例解释

各个非空子集的复杂度如下：
$\{[1,6]\}\rightarrow 1,~$$\{[2,3]\}\rightarrow 1,~$$\{[4,5]\}\rightarrow1$

$\{[1,6],[2,3]\}\rightarrow 1,~$$\{[1,6],[4,5]\}\rightarrow 1,~$$\{[2,3],[4,5]\}\rightarrow4$

$\{[1,6],[2,3],[4,5]\}\rightarrow 1$

答案为 $1+1+1+1+1+4+1=10$。

# 数据范围与提示

测试点 $2$ 满足 $N\le 16$。

测试点 $3\ldots 5$ 满足 $N\le 1000,~K=2$。

测试点 $6-8$ 满足 $N\le 1000$。

测试点 $T\in [9,~16]$ 满足 $K=3+(T-9)$。

对于 $100\%$ 的数据，有 $1\le N \le 10^5,~2\le K\le 10,~1\le l_i<r_i\le 2N$。



