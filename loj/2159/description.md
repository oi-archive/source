
# 题目描述

**译自 POI 2011 Round 1. E「[Plot](https://szkopul.edu.pl/problemset/problem/mzrTn1kzVBOAwVYn55LUeAai/site/?key=statement)」**

给定 $n$ 个点 $ \left( P_1, \ldots, P_n \right) $，将其分成不多于 $m$ 个连续的段：

$$ \left( P_{k_0 + 1}, \ldots, P_{k_1} \right), \left( P_{k_1 + 1}, \ldots, P_{k_2} \right), \ldots, \left( P_{k_{s - 1}+ 1}, \ldots, P_{k_s} \right), $$

其中 $ 0 = k_0 \lt k_1 \lt k_2 \lt \ldots \lt k_s = n $，且对于 $ i = 1, \ldots, s $，子序列 $ \left( P_{k_{i - 1}+ 1}, \ldots, P_{k_i} \right) $ 用一个新点 $Q_i$ 替代。这时我们说 $ P_{k_i - 1}, \ldots, P_{k_i} $ 这些点被「收缩」到了点 $Q_i$，从而产生一个新的点集 $ Q_1, \ldots, Q_s $。两个点集的相似度定义为 $ P_1, \ldots, P_n $ 这些点与其对应的「收缩」后的点距离的最大值：

$$ \max_{i = 1, \ldots, s} \left( \max_{j = k_{i-1}+1, \ldots, k_i}\left( d\left( P_j, Q_i \right) \right) \right) ,$$

其中 $ d\left( P_j, Q_i \right) $ 表示 $P_j$ 和 $Q_i$ 之间的距离，公式为：

$$ d \left( \left(x_1, y_1 \right), \left( x_2, y_2 \right) \right) = \sqrt{ \left( x_2 - x_1 \right)^2 + \left( y_2 - y_1 \right)^2 } $$

![](source/loj/2159/img/aHR0cHM6Ly9vb28uMG8wLm9vby8yMDE3LzA0LzIwLzU4ZjgzNThjMmNlY2EuanBn.jpg)

上图为一个将 $ (P_1, \ldots, P_7) $ 收缩为 $ ( Q_1, Q_2 ) $ 的例子，其中 $ (P_1, \ldots, P_4) $ 被收缩为 $ Q_1 $，$ (P_5, P_6, P_7) $ 被收缩为 $Q_2$.

给定 $n$ 个点组成的序列，你需要将其「收缩」为最多 $m$ 个点，使得相似度最小。原序列可以任意切割。受限于浮点数的精度限制，只要答案比最优解多出不超过 $ 0.000001$ 即算正确。

# 输入格式

第一行两个整数 $n$ 和 $m$，$ 1 \le m \le n \le 100000 $，用一个空格分开。

接下来 $n$ 行每行两个整数，用一个空格分开。第 $i+1$ 行两个整数 $x_i, y_i$（$ -1000000 \le x_i,y_i \le 1000000$），表示 $P_i$ 的坐标为 $(x_i, y_i)$.


# 输出格式

第一行一个实数 $d$，表示与原序列的相似度。

接下来一个整数 $s$，表示收缩后点集的大小。

接下来 $s$ 行表示 $Q_i, \ldots, Q_s$ 的坐标。每行两个整数 $u_i$ 和 $v_i$ 表示 $Q_i$ 的坐标 $ (u_i, v_i) $。

实数应保留小数点后最多 $15$ 位。


# 样例

#### 样例输入
```plain
7 2
2 0
0 4
4 4
4 2
8 2
11 3
14 2
```

#### 样例输出
```plain
3.00000000
2
2.00000000 1.76393202
11.00000000 1.99998199
```

# 数据范围与提示

Task author: Jakub Pawlewicz.  
~~Uncompleted SPJ: ceba~~  
SPJ: [Tangjiaming](/user/9213)

翻译：vincent163

