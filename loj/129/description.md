
# 题目描述

这是一道模板题。

读入一个由大小写英文字母或数字组成的字符串 $s$ ，请把这个字符串分成若干部分 $s=s_1s_2s_3\dots s_m$，使得每个 $s_i$ 都是 [Lyndon Word](https://en.wikipedia.org/wiki/Lyndon_word)，且 $\forall 1\leq i <n:s_i \geq s_{i+1}$。输出 $s_1$ 到 $s_m$ 这些串长度的右端点的位置。位置编号为 $1$ 到 $n$。

一个字符串 $s$ 是一个 Lyndon Word 表示 $s$ 是其所有后缀中的最小者。

# 输入格式

一行一个长度为 $n$ 的仅包含大小写英文字母或数字的字符串 $s$。

# 输出格式

一行若干个整数，第 $i$ 个表示 $s_i$ 的右端点在 $s$ 中的位置。

# 样例

#### 样例输入 1
```plain
ababa
```

#### 样例输出 1
```plain
2 4 5
```

#### 样例输入 2
```plain
bbababaabaaabaaaab
```

#### 样例输出 2
```plain
1 2 4 6 9 13 18
```

#### 样例输入 3
```plain
azAZ0129
```

#### 样例输出 3
```plain
2 4 8
```

# 数据范围与提示

$1 \leq |s|\leq 2^{20} $

