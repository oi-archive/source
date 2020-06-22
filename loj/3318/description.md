
# 题目描述

 **译自 [CCO 2020](https://cemc.math.uwaterloo.ca/contests/computing/2020/index.html) Day1 T2「[Exercise Deadlines](https://cemc.math.uwaterloo.ca/contests/computing/2020/cco/day1.pdf)」**，翻译者： [ShineEternal](/user/18062)。

---

给定一个长度为 $N$ 的序列 $d_i$。

你有一个长度为 $N$ 的序列 $a_i$，初始状态下 $a_i=i$。

你需要每次交换序列 $a_i$ 中相邻的两个数，使得最终满足对于任意的 $1\le i\le n$，均有 $a_i\le d_i$。求出最少需要多少次。

# 输入格式

输入第一行一个整数 $N$。

第二行共 $N$ 个整数 $d_i$。

# 输出格式

输出最少的交换次数。

# 样例

#### 样例输入 1

```plain
4
4 4 3 2
```

#### 样例输出 1

```plain
3
```

#### 样例解释 1

最优方案之一为 $(1,4,3,2)$，可通过三次交换由 $(1,2,3,4)$ 得到。

#### 样例输入 2

```plain
3
1 1 3
```

#### 样例输出 2

```plain
-1
```

#### 样例解释 2

有两个 $1$，$a_i$ 数组中不存在两个 $\le 1$ 的数，故无解。

# 数据范围与提示

对于 $68\%$ 的数据，保证 $N\le 5000$；  
对于 $100\%$ 的数据，保证 $1\le N\le 2\times 10^5$，$1\le d_i\le N$。

