
# 题目描述

** 译自 BalticOI 2011 Day2 T2「Plagiarism」**

有 $N$ 个数 $f_1, f_2, \ldots, f_N$，试求：有多少对 $(f_i, f_j)\,\,(1\le i<j\le N)$ 满足 $(0.9×f_j)\le f_i\le f_j$。

The participants of the World Programming Competition submitted $N$ solution files $f_1 ,...,f_N$ to the grading system. Before accepting the results as final, the jury would like to rule out any possibility of plagiarism. They have a program that takes two files and compares them to decide if they are too similar to each other.  
However, the number of files is rather big and it would take too much time to compare all pairs. On the other hand, many pairs could be quickly eliminated based on the fact that the file sizes are too different.  
More precisely, the jury decided to fully skip comparing every pair where the size of the smaller file is less than 90% of the size of the larger one. So, the comparison program has to examine only those distinct pairs of files $(f_i, f_j)$ where $i≠j$, $\textrm{size}(f_i) ≤ \textrm{size}(f_j)$ and $\textrm{size}(f_i ) ≥ 0.9 \times \textrm{size}(f_j)$.  
Write a program that computes the number of pairs of files that will have to be examined.

# 输入格式

第一行有一个整数 $N$。  
第二行有 $N$ 个整数 $f_1, f_2, \ldots, f_N$。
 
The first line of input contains the integer $N$, the number of solution files submitted. The second line contains $N$ integers $\textrm{size}(f_1),...,\textrm{size}(f_N)$, each showing the size of one file.

# 输出格式

一行一个整数，表示有多少对 $(f_i, f_j)\,\,(1\le f_i<f_j\le N)$ 满足条件。

The first and only line of output must contain one integer, the number of pairs of files that will have to be examined.

# 样例

#### 样例输入 1
```plain
2
2 1
```

#### 样例输出 1
```plain
0
```

#### 样例输入 2
```plain
5
1 1 1 1 1
```

#### 样例输出 2
```plain
10
```

# 数据范围与提示

对于 $50\%$ 的数据，$ 1 ≤ N ≤ 2000$。  
对于所有数据，$ 1 ≤ N ≤ 10^5, 1 ≤ f_i ≤ 10^8 $。

