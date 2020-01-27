
# 题目描述

**译自 POI 2010 Stage 1.「[Intelligence Test](https://szkopul.edu.pl/problemset/problem/Arkza0f7GKKb-m1YZJulnlMk/site/?key=statement)」**

给出一个母串 $a_1,a_2,a_3,\cdots ,a_n$ ，若干次询问，每次询问给出一个子串 $b_1,b_2,\cdots b_m$ ，请你求出这个子串是不是母串的子序列。


# 输入格式

第一行一个正整数 $n$ 。  
第二行 $n$ 个空格隔开的正整数 $a_1,a_2,\cdots ,a_n$ ，表示母串。  
第三行一个正整数 $q$ ，表示询问次数。  
接下来 $2 \times q$ 行，每两行表示一次询问，其中的第一行是一个正整数 $m$ ，第二行是 $m$ 个空格隔开的正整数表示 $b_1,b_2,\cdots ,b_m$ ，表示询问的子串。

# 输出格式

输出共 $q$ 行，每行一个字符串。  
若第 $i$ 次询问的串是母串的子序列，那么第 $i$ 行应为 ```TAK``` ，否则应为 ```NIE``` 。

# 样例

#### 样例输入

```plain
7
1 5 4 5 7 8 6
4
5
1 5 5 8 6
3
2 2 2
3
5 7 8
4
1 5 7 4
```

#### 样例输出

```plain
TAK
NIE
TAK
NIE
```

# 数据范围与提示

对于 $100\%$ 的数据，有 $1\le n,m,a_i,b_i\le 1\ 000\ 000$ ，且 $\sum m\le 1\ 000\ 000$ ，这里 $\sum m$ 表示 $q$ 组询问的 $m$ 之和。

Translated By diamond_duke

