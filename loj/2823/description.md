
# 题目描述

**本题译自 [BalticOI 2014](http://www.boi2014.lmio.lt/tasks.html) Day1 T2「[Three Friends](http://www.boi2014.lmio.lt/tasks/friends-en.pdf)」**

给定一个字符串 $S$，先将字符串 $S$ 复制一次（~~变成双倍快乐~~），得到字符串 $T$，然后在 $T$ 中插入一个字符，得到字符串 $U$。

给出字符串 $U$，重新构造出字符串 $S$。

所有字符串只包含大写英文字母。


# 输入格式

第一行一个整数 $N$，表示字符串 $U$ 的长度。

第二行一个长度为 $N$ 的字符串，表示字符串 $U$。


# 输出格式

一行一个字符串，表示字符串 $S$。

特别地：

 - 如果字符串无法按照上述方法构造出来，输出 `NOT POSSIBLE`；
 - 如果字符串 $S$ 不唯一，输出 `NOT UNIQUE`。

# 样例

#### 样例输入 1
```plain
7
ABXCABC
```
#### 样例输出 1
```plain
ABC
```
#### 样例输入 2
```plain
6
ABCDEF
```
#### 样例输出 2
```plain
NOT POSSIBLE
```
#### 样例输入 3
```plain
9
ABABABABA
```
#### 样例输出 3
```plain
NOT UNIQUE
```

# 数据范围与提示

|子任务|分数|数据范围|
|:--:|:--:|:--:|
|1|$35$|$2\le N\le 2\ 001$|
|2|$65$|$2\le N\le 2\ 000\ 001$|


