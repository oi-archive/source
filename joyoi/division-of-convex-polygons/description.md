## 题目描述

　　给定一个具有 $N$ 个顶点（从 $1$ 到 $N$ 编号）的凸多边形，每一个顶点的权值均是一个正整数。问：如何把这个凸多边形划分成 $N-2$ 个互不相交的三角形，使得这些三角形顶点的权值的乘积之和最小？

　　**【注意】本问题不要求输出方案，仅需输出结果即可。**
	
****

## 输入输出格式

### 输入格式：
　　第一行：一个正整数 $N\left( 3\leq N\leq 100\right)$，表示顶点数。

　　第二行：$N$ 个正整数 $a_i\left( 1\leq a_i\leq 10^{9}\right)$，表示从 $1$ 到 $N$ 数第 $i$ 个顶点的权值。

### 输出格式：
　　第一行：一个正整数，表示这些三角形顶点的权值的乘积之和的最小值。

****

## 输入输出样例

Sample Input 1
```
5
121 122 123 245 231
```
Sample Output
```
12214884
```

****

## 样例解释

![](/source/joyoi/division-of-convex-polygons/img/aHR0cHM6Ly9jZG4ubHVvZ3Uub3JnL3VwbG9hZC9waWMvMzM4MjMucG5n.png)

　　如图。样例中的凸五边形可以分成 $\triangle ABC$，$\triangle ACE$，$\triangle CDE$，三角形顶点权值乘积之和为：

$$121\times 122\times 123+121\times 123\times 231+123\times 245\times 231=12214884$$

****

## 数据规模

　　对于 $27\%$ 的数据，有 $3\leq N\leq 30$。

　　对于另 $47\%$ 的数据，有 $1\leq a_i\leq 10^{6}$。

　　对于 $100\%$ 的数据，有 $3\leq N\leq 50$，$1\leq a_i\leq 10^{9}$。