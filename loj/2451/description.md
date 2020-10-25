
# 题目描述

**译自 POI 2010 Stage 2. Day 1「[Hamsters](https://szkopul.edu.pl/problemset/problem/qQGtOc61vnHgCrs01ORC7iD1/site/?key=statement)」**

Byteasar 有 $n$ 个由小写字母组成的字符串，他称一个字符串是优美的，当且仅当他由小写字母组成，且 Byteasar 的 $n$ 个字符串在这个字符串中出现了至少 $m$ 次（同一个字符串可以重复出现多次， $A$ 在 $B$ 中出现等价于 $A$ 是 $B$ 的子串）。  
Byteasar 想知道，最短的优美字符串有多长。

# 输入格式

第一行两个空格隔开的正整数 $n,m$ 。  
接下来 $n$ 行，每行一个小写字母串，表示 Byteasar 拥有的字符串，保证这些字符串互不包含。

# 输出格式

一行一个正整数，表示最短的优美字符串的长度。

# 样例

#### 样例输入
```plain
4 5
monika
tomek
szymon
bernard
```

#### 样例输出
```plain
23
```

# 数据范围与提示

对于 $100\%$ 的数据， $1\le n\le 200,1\le m\le 10^9$ ，所有字符串的总长 $\le 100\ 000$ 。

Translated by vincent163

