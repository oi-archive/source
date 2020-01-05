
# 题目描述

**题目译自 [USACO 2018 US Open Contest, Platinum](http://usaco.org/index.php?page=open18results) Problem 1. [Out of Sorts](http://usaco.org/index.php?page=viewproblem2&cpid=840)**

奶牛 Bessie 正在为它将来在农场外的职业规划作打算。它正在大型同性交友网站 [LibreOJ](https://loj.ac) 上学习算法。它最喜欢的两个算法是「冒泡排序」和「快速排序」，但 Bessie 一不小心就把它们弄混淆了，实现了一种混合算法。

如果数组 $A$ 中前 $i$ 个数的最大值不大于第 $i+1$ 个数之后的数的最小值，则把 $i \ldots i+1$ 之间的位置称为「分隔点」。Bessie 记得快速排序的步骤之一是重排数组使得它有一个「分隔点」，然后将分隔点两边的数组递归排序。但它发现它也能在线性时间内找出所有的「分隔点」，导致它忘记快速排序如何重排数组来创造出一个「分隔点」。它决定用冒泡排序来解决这个问题。这可能是排序算法历史上发生过最严重的错误。

以下是 Bessie 最初用来排序数组 $A$ 的大致过程。它先写了一个简单的函数来实现冒泡排序：
```
bubble_sort_pass (A) {
   for i = 0 to length(A)-2
      if A[i] > A[i+1], swap A[i] and A[i+1]
}
```
它实现的递归算法是：
```
quickish_sort (A) {
   if length(A) = 1, return
   do { // 主循环
      work_counter = work_counter + length(A)
      bubble_sort_pass(A)
   } while (no partition points exist in A) 
   divide A at all partition points; recursively quickish_sort each piece
}
```
Bessie 很好奇它的代码能跑多快。为了简化问题，它发现它的主循环只需要线性时间，所以它在主循环内加了一个全局变量 `work_counter` 来统计算法的总工作量。

给定数组 $A$，请预测进行 `quickish_sort` 后 `work_counter` 的值。

# 输入格式

第一行一个整数 $N$。

接下来 $N$ 行每行一个整数，表示 $A[0] \ldots A[N-1]$，不保证输入的数互不相同。

# 输出格式

输出最终 `work_counter` 的值。

# 样例

#### 样例输入
```plain
7
20
2
3
4
9
8
7
```

#### 样例输出
```plain
12
```

#### 样例解释
开始时的数组是 `20 2 3 4 9 8 7`. 经过一轮冒泡排序（使 `work_counter` 加 $7$）后，数组变为 `2 | 3 | 4 | 9 8 7 | 20`，其中 `|` 表示一个分隔点。接下来的问题便是递归排序 `2`、`3`、`4` 和 `20` 这些数组（不改变 `work_counter` 的值），和 `9 8 7` 这个数组。对于 `9 8 7` 这个数组，一次主循环后得到的数组是 `8 7 | 9`（使 `work_counter` 加 $3$），对 `8 7`数组进行一次循环（使 `work_counter` 加 $2$）后排序算法结束。

# 数据范围与提示

对于全部数据，$1\le N\le 10^5,0\le A[i]\le 10^9$。

Problem credits: Brian Dean

