
# 题目描述

**原题来自：[POJ 2752](http://poj.org/problem?id=2752)**

给定若干字符串（这些字符串总长 $ \le 4\times 10^5 $），在每个字符串中求出所有既是前缀又是后缀的子串长度。

例如：`ababcababababcabab`，既是前缀又是后缀的：`ab`，`abab`，`ababcabab`，`ababcababababcabab`。

# 输入格式

输入若干行，每行一个字符串。

# 输出格式

对于每个字符串，输出一行，包含若干个递增的整数，表示所有既是前缀又是后缀的子串长度。

# 样例

#### 样例输入
```plain
ababcababababcabab
aaaaa
```
#### 样例输出
```plain
2 4 9 18
1 2 3 4 5
```


# 数据范围与提示



