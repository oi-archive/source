
# 题目描述

**译自 BalticOI 2011 Day1 T1「Growing Trees」**（为啥这次没链接？官网挂了呀）

给出一个长度为 $N$ 的数组 $a$，数组中每个数的取值范围均为 $[1,N]$（没说互不相同）。
接下来有 $M$ 组操作，操作分为两种：
1. $\texttt{F}\:\:c\:\:h$  
将满足 $a[i] \ge h$ 的所有 $a[i]$ 中最小的 $c$ 个数都 $+1$；
2. $\texttt{C}\:\:\min\:\:\max$  
输出满足 $\min \le a[i] \le \max$ 的 $a[i]$ 的个数。

For fertilizing the trees he has several bottles of MegaBoostFertilizer, which, when treated on trees, causes them to grow one centimeter up instantly. Every bottle has a limited capacity $c_i$ , which determines the number of trees it can be applied to. Moreover, for each bottle there is a minimal height $h_i$ of trees, which can be treated with it. Since Egon wants to have all his trees as big as possible, he always applies the fertilizer to the $c_i$ smallest trees chosen from the trees that are at least $h_i$ centimeters high.  
When Egon computes statistics about trees he has to determine the number of trees whose height is in some given interval. Egon is quite busy working in the garden, so he asked you to write a program, that given the list of his tasks, computes the statistics for him.  

# 输入格式

第一行有两个整数 $N$ 和 $M$。    
第二行有 $N$ 个整数，表示数组 $a$。  
在接下来的 $M$ 行中，每行有一组操作。

The first line of the standard input contains two integers $N$ and $M$ denoting the number of trees in Egon’s garden and the number of his tasks. The second line contains a sequence of $N$ integers fromthe range $[1,N]$ describing the initial heights of the trees in centimeters. The following $M$ lines describe the tasks in chronological order. Each of those lines begins with a character $t_i$ ($t_i = \texttt{F } or \texttt{ C}$), which describes the type of the task.  
If $t_i = \texttt{F}$ then two integers $c_i$ and $h_i$ follow. Such a line means that Egon applies a bottle of MegaBoostFertilizer to the $c_i$ smallest trees among those trees that are at least $h_i$ centimeters high. When there are less than $c_i$ trees of sufficient height, he applies the fertilizer to all such trees and discards the bottle with some fertilizer remaining.  
If $t_i = \texttt{C}$ then two integers $\min_i$ and $\max_i$ follow. They denote that Egon has to compute the number of trees whose height $H$ is between $\min_i$ and $\max_i$ centimeters ($\min_i ≤ H ≤ \max_i$ ).  

# 输出格式

对于每组 $\texttt{C}\:\:\min\:\:\max$ 操作输出一行，每行一个整数，表示满足 $\min \le a[i] \le \max$ 的 $a[i]$ 的个数。

For every task of type $\texttt{C}$, output one line containing the number of apple trees that have the required height. The order of the results should conform to the order of type $\texttt{C}$ tasks in the input.

# 样例

#### 样例输入
```plain
5 7
1 3 2 5 2
F 2 1
C 3 6
F 2 3
C 6 8
F 2 1
F 2 2
C 3 5
```

#### 样例输出
```plain
3
0
5
```

# 数据范围与提示

$1 ≤ N,M ≤ 10^5, 1 ≤ c ≤ N, 0 ≤ h ≤ 10^9, 1 ≤\ min ≤ \max ≤ 10^9$。

