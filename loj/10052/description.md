
# 题目描述

**原题来自：ACM Pacific NW Region 1998**

给出一些数字串，判断是否有一个数字串是另一个串的前缀。

# 输入格式

输入数据为多组数据，每组数据读到 $9$ 时结束。

# 输出格式

对于每组数据，如果不存在一个数字串是另一个串的前缀，输出一行 `Set t is immediately decodable` ，否则输出一行 `Set t is not immediately decodable` ，其中 $t$ 是这一组数据的组号。

# 样例

#### 样例输入
```plain
01
10
0010
0000
9
01
10
010
0000
9
```
#### 样例输出
```plain
Set 1 is immediately decodable
Set 2 is not immediately decodable
```

# 数据范围与提示

原文如下：

>An encoding of a set of symbols is said to be *immediately decodable* if no code for one symbol is the prefix of a code for another symbol.  We will assume for this problem that all codes are in binary, that no two codes within a set of codes are the same, that each code has at least one bit and no more than ten bits, and that each set has at least two codes and no more than eight. 

数字串只包含 $0,1$，记每个数字串长度为 $l$，则 $1\le l\le 10$。每组数据至少有 $2$ 个数字串，至多有 $8$ 个数字串。

