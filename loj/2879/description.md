
# 题目描述

**题目译自 [JOISC 2014](https://www.ioi-jp.org/camp/2014/2014-sp-tasks/) Day3 T1「[JOIOJI](https://www.ioi-jp.org/camp/2014/2014-sp-tasks/2014-sp-d3.pdf)」**

JOIOJI 桑是 JOI 君的叔叔。JOIOJI 这个名字是由 $\texttt{J},$ $\texttt{O},$ $\texttt{I}$ 三种字母各两个构成的。

最近，JOIOJI 桑喜当爹。JOIOJI 桑想让自己孩子的名字和自己一样由 $\texttt{J},$ $\texttt{O},$ $\texttt{I}$ 三种字母构成，并且想让 $\texttt{J},$ $\texttt{O},$ $\texttt{I}$ 三个字母的出现次数恰好相同。

JOIOJI 桑家有一份祖传的卷轴，上面写着一首长诗 $S$，长度为 $N$，由 $\texttt{J},$ $\texttt{O},$ $\texttt{I}$ 三种字母组成。JOIOJI 桑想用诗中最长的满足要求的连续子串作为孩子的名字。

现在 JOIOJI 桑将这首长诗交给了你，请你求出诗中最长的、包含同样数目的 $\texttt{J},$ $\texttt{O},$ $\texttt{I}$ 三种字母的连续子串。

# 输入格式

第一行一个正整数 $N$，代表这首长诗的长度。  
接下来一行一个长度为 $N$ 的字符串 $S$ ，表示这首长诗，保证每个字符都是 $\texttt{J},$ $\texttt{O},$ $\texttt{I}$ 三个字母中的一个。

# 输出格式

输出一行一个正整数，代表最长的包含等数量 $\texttt{J},$ $\texttt{O},$ $\texttt{I}$ 三个字母的最长连续子串的长度。如果不存在这样的子串，输出 $0$。

# 样例

#### 样例输入 1
```plain
10
JOIIJOJOOI
```

#### 样例输出 1
```plain
6
```

#### 样例说明 1
选择 $\texttt{IIJOJO}$ 这个子串，长度为 6，包含 $\texttt{J},$ $\texttt{O},$ $\texttt{I}$ 三个字母各 2 个，这是最长的满足要求的子串。

#### 样例输入 2
```plain
8
IOIIJIIO
```

#### 样例输出 2
```plain
0
```

#### 样例输入 3
```plain
20
JJIOOIJIJOIOJIOJOOIJ
```

#### 样例输出 3
```plain
15
```

# 数据范围与提示

对于 $5\%$ 的测试数据，$N\le 500$。  
对于另外 $15\%$ 的测试数据，$N\le 4000$。  
对于所有测试数据，$1\le N\le 2\times 10^5$。

