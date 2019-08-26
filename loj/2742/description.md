
# 题目描述

**译自 [JOI Open 2016](https://contests.ioi-jp.org/open-2016/index.html) T2 「RNA 鎖の販売 / Selling RNA Strands」**

基因库中有 $N$ 个字符串，这些字符串仅由 `A`, `G`, `U`, `C`组成（保证每个字符串都包含四种字母）。  
由 $M$ 组查询，每组查询包含两个字符串 $P,Q$，试求：基因库中有多少个字符串同时存在前缀 $P$ 和后缀 $Q$。  
举个例子，`GAC` 存在前缀 `G`, `GA`, `GAC`，存在后缀 `C`, `AC`, `GAC`，那么我们可以说：`GAC` 同时存在前缀 `GA` 和后缀 `AC`。

# 输入格式

第一行有两个整数 $N, M$。  
在接下来的 $N$ 行中，每行一个字符串 $S_i$，表示基因库中的一个字符串。  
在接下来的 $M$ 行中，每行有两个用空格分隔的字符串，表示一组查询。

# 输出格式

输出共 $M$ 行，每行一个整数，表示符合查询条件的字符串的数量。

# 样例

#### 样例输入 1
```plain
2 3
AUGC
AGC
G C
AU C
A C
```

#### 样例输出 1
```plain
0
1
2
```

#### 样例说明 1
第一组查询：找不到。  
第二组查询：`AUGC` 满足条件。  
第三组查询：`AUGC` 和 `AGC` 满足条件。

#### 样例输入 2
```plain
3 3
AA
AA
AGA
AA AA
AG GA
AG GA
```

#### 样例输出 2
```plain
2
1
1
```

#### 样例说明 2
注意基因库中的字符串可以重复。

#### 样例输入 3
```plain
8 7
GCGCUACCCCAACACAAGGCAAGAUAUA
G
GGAC
GCGG
U
GCGCUACCCCAACACAAGGCAAGAUGGUC
GCCG
GCGCUGA
GCGCUACCC A
GCGCUACCCC AC
GCG C
GCGC A
G G
G C
G GGA
```

#### 样例输出 3
```plain
1
0
1
2
3
2
0
```

# 数据范围与提示

对于所有数据，$1\le N, M,$ $\textrm{len}(S_i),$ $\textrm{len}(P_j),$ $\textrm{len}(Q_j)$ $\le 10^5,$ $1\le\sum\textrm{len}(S_i),$ $\sum\textrm{len}(P_j),$ $\sum\textrm{len}(Q_j)$ $\le 2\times 10^6$。  

**子任务 1（10 分）** $\ \ N, M, $ $\textrm{len}(S_i),$ $\textrm{len}(P_j),$ $\textrm{len}(Q_j)$ $\le 100$。  
**子任务 2（25 分）** $\ \ N, M\le 5000$。  
**子任务 3（25 分）** $\ \ \sum\textrm{len}(S_i),$ $\sum\textrm{len}(P_j),$ $\sum\textrm{len}(Q_j)$ $\le 10^5$。  
**子任务 4（40 分）** $\ \ $没有额外限制。

