
# 题目描述

**题目来自 [USACO 2020 January Contest, Platinum](http://usaco.org/index.php?page=jan20results) Problem 2. [Non-Decreasing Subsequences](http://usaco.org/index.php?page=viewproblem2&cpid=997)**

Bessie 最近参加了一场 USACO 竞赛，遇到了以下问题。当然 Bessie 知道怎么做。那你呢？ 

考虑一个仅由范围在 $1\ldots K$ 之间的整数组成的长为 $N$ 的序列 $A_1,A_2,\ldots ,A_N$。给定 $Q$ 个形式为 $[L_i,R_i]$ 的询问。对于每个询问，计算 $A_{L_i},A_{L_{i+1}},\ldots ,A_{R_i}$ 中不下降子序列的数量模 $10^9+7$ 的余数。

$A_L,\ldots ,A_R$ 的一个不下降子序列是一组索引 $(j_1,j_2,\ldots ,j_x)$，满足 $L\le j_1<j_2<\ldots <j_x\le R$ 以及 $A_{j_1}\le A_{j_2}\le \ldots \le A_{j_x}$。确保你考虑了空子序列！

# 输入格式

输入的第一行包含两个空格分隔的整数 $N$ 和 $K$。

第二行包含 $N$ 个空格分隔的整数 $A_1,A_2,\ldots ,A_N$。

第三行包含一个整数 $Q$。

以下 $Q$ 行每行包含两个空格分隔的整数 $L_i$ 和 $R_i$。

# 输出格式

对于每个询问 $[L_i,R_i]$，你应当在新的一行内输出 $A_{L_i},A_{L_{i+1}},\ldots ,A_{R_i}$ 的不下降子序列的数量模 $10^9+7$ 的余数。

# 样例

#### 样例输入
```plain
5 2
1 2 1 1 2
3
2 3
4 5
1 5
```
#### 样例输出
```plain
3
4
20
```
#### 样例说明
对于第一个询问，不下降子序列为 $()$、$(2)$ 和 $(3)$。$(2,3)$ 不是一个不下降子序列，因为 $A_2\not \le A_3$。

对于第二个询问，不下降子序列为 $()$、$(4)$、$(5)$ 和 $(4,5)$。

# 数据范围与提示

对于全部数据，$1\le K\le 20,1\le N\le 5\times 10^4,1\le Q\le 2\times 10^5,1\le L_i\le R_i\le N$。

各测试点性质如下：
- 测试点 $2\sim 3$ 满足 $N\le 10^3$；
- 测试点 $4\sim 6$ 满足 $K\le 5$；
- 测试点 $7\sim 9$ 满足 $Q\le 10^5$；
- 测试点 $10\sim 12$ 没有额外限制。

