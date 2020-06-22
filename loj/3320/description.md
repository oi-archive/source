
# 题目描述

 **译自 [CCO 2020](https://cemc.math.uwaterloo.ca/contests/computing/2020/index.html) Day2 T1「[Travelling Salesperson](https://cemc.math.uwaterloo.ca/contests/computing/2020/cco/day2.pdf)」**，翻译者：[EntropyIncreaser](/user/3532)。

---

给一个 $N$ 个点的完全无向图，每条边是红色或者蓝色。请你对于每个顶点 $u$，找出一条尽量短的路径，经过每个节点，并且按顺序经过的边之颜色交替最多一次。



# 输入格式

第一行输入一个正整数 $N$，表示顶点数量。

接下来 $N-1$ 行，第 $i$ 行是长为 $i-1$ 的，只出现 `R` 和 `B` 的字符串，依次表示 $i$ 节点与 $1, 2, \dots, i-1$ 这些节点间边的颜色。

# 输出格式

输出 $2N$ 行，第 $2i-1$ 行输出一个整数 $M_i$，表示 $i$ 节点起始路径的经过节点数量。

第 $2i$ 行输出 $M_i$ 个整数，表示这条路径依次经过的节点，以 $i$ 起始。


# 样例

#### 样例输入

```plain
4
R
RR
BRB
```

#### 样例输出

```plain
5
1 4 2 1 3
6
2 3 1 2 3 4
5
3 1 2 3 4
4
4 3 1 2
```

#### 样例解释

根据评分方式（见下），该输出以 $3$ 为起点的路径实际上存在一组长为 $4$ 的解（$3,2,1,4$），故在该路径上的得分是 $4\times \lfloor 8 + 8\times \frac{2\times 4 - 5}{4-1} \rfloor = 64$，故得分不会超过 $64$。

# 数据范围与提示

对于 $100 \%$ 的数据，$2 \le N \le 2000$。

#### 评分方式

令 $K_i$ 是以 $i$ 为起点的最优解的长度。如果存在一组 $M_i > 2K_i$，你的答案会得到 $0$ 分并判为 `Wrong Answer`。

如果你得到的均为最优解，你获得满分。

否则，你的得分将是 $4\times \lfloor 8 + 8\times \frac{2K_i - M_i}{K_i-1} \rfloor$ 的最小值。

