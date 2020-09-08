
# 题目描述

**题目译自 [CEOI 2020](http://ceoi2020.inf.elte.hu/contest/tasks/) Day1 T1「[Fancy Fence](http://ceoi2020.inf.elte.hu/wp-content/uploads/2020/09/fancyfence_eng.pdf)」**

众所周知，Balázs 拥有整个城镇中最漂亮的围栏。围栏由 $N$ 个部分组成，每个部分均为矩形，且相邻的两个部分间均紧密相连。第 $i$ 部分矩形的高度为 $h_i$，宽度为 $w_i$，我们需要找到满足如下条件的花式矩形：

- 矩形的每条边均是水平的或竖直的，且每条边的长度为整数。
- 矩形与地面的距离为整数。
- 矩形与围栏第一部分的左侧边的距离为整数。
- 矩形完整包含在围栏中。

现在你需要求出花式矩形的总数。因为这个数字可能很大，请输出其对 $10^9+7$ 取模后的结果。

# 输入格式

输入第一行包含一个整数 $N$，代表围栏由 $N$ 部分组成。

第二行 $N$ 个整数，第 $i$ 个整数为第 $i$ 个矩形的高度 $h_i$。

第三行 $N$ 个整数，第 $i$ 个整数为第 $i$ 个矩形的宽度 $w_i$。

# 输出格式

输出花式矩形数对 $10^9+7$ 取模后的结果。

# 样例

#### 样例输入 1
```plain
2
1 2
1 2
```

#### 样例输出 1
```plain
12
```

#### 样例解释 1

围栏形状如下所示：

![fence1.png](/source/loj/3348/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wOC8yNi81ZjQ2NTRjNzMxMjQ5LnBuZw==.png)

形状如下的矩形有 $5$ 个：

![fence2.png](/source/loj/3348/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wOC8yNi81ZjQ2NTRjNzA3MzgyLnBuZw==.png)

形状如下的矩形有 $3$ 个：

![fence3.png](/source/loj/3348/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wOC8yNi81ZjQ2NTRjNWRjZTRhLnBuZw==.png)

形状如下的矩形有 $1$ 个：

![fence4.png](/source/loj/3348/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wOC8yNi81ZjQ2NTRjNjIwZmQyLnBuZw==.png)

形状如下的矩形有 $2$ 个：

![fence5.png](/source/loj/3348/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wOC8yNi81ZjQ2NTRjNjdhYTdkLnBuZw==.png)

形状如下的矩形有 $1$ 个：

![fence6.png](/source/loj/3348/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wOC8yNi81ZjQ2NTRjNmJkYWMxLnBuZw==.png)

#### 样例 2

见附加文件。

# 数据范围与提示

所有测试点均满足：$1 \leq N \leq 10^5$，$1 \leq h_i,w_i \leq 10^9$。

各子任务的约束条件如下：

| 子任务编号 | 分值 | 约束                                                         |
| :----------: | :----: | :------------------------------------------------------------: |
| $1$        | $0$  | 样例                                                         |
| $2$        | $12$ | $N \leq 50$，且 $\forall i \in [1,N]$，$h_i \leq 50$ 且 $w_i=1$ |
| $3$        | $13$ | $\forall i \in [1,N]$，$h_i=1$ 或 $h_i=2$                    |
| $4$        | $15$ | 所有的 $h_i$ 均相等                                          |
| $5$        | $15 $ | $\forall i \in [1,N-1]$，$h_i \leq h_{i+1}$                  |
| $6$        | $18$ | $N \leq 1000$                                                |
| $7$        | $27$ | 无特殊约束                                                   |



