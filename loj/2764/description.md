
# 题目描述

**本题译自 [JOI 2013 Final](https://www.ioi-jp.org/joi/2012/2013-ho/index.html) T4「[JOIOIの塔](https://www.ioi-jp.org/joi/2012/2013-ho/2013-ho.pdf)」**

JOIOI 塔是一种单人游戏。

这个游戏要用到一些写有 `J`, `O`, `I` 中任一文字的圆盘。这些圆盘的直径互不相同。游戏开始时，这些圆盘按照直径大的在下面的规则堆叠。你需要用这些圆盘做尽量多的迷你 JOIOI 塔。迷你 JOIOI 塔由 $ 3 $ 个圆盘构成，从直径较小的圆盘开始分别为 `J`, `O`, `I` 或分别为 `I`, `O`, `I` 。不过，每个圆盘最多只能使用一次。

![3ab6e7ae407ceb0dbca914b199af6144.png](source/loj/2764/img/aHR0cHM6Ly93d3cuejRhLm5ldC9pbWFnZXMvMjAxOC8wOC8xNC8zYWI2ZTdhZTQwN2NlYjBkYmNhOTE0YjE5OWFmNjE0NC5wbmc=.png)

#### 任务
给出长为 $ N $ 的字符串 $ S $ ，表示直径从小到大的圆盘上的文字。请编写程序求出使用这些圆盘能够做出的迷你 JOIOI 塔个数的最大值。


# 输入格式

第一行为一个整数 $ N $ ，表示字符串 $ S $ 的长度。
第二行是一个字符串 $ S $ 。

# 输出格式

输出一行一个整数：表示能够做出的迷你 JOIOI 塔数量的最大值。

# 样例

#### 输入样例 1
```plain
6
JOIIOI
```
#### 输出样例 1
```plain
2
```
#### 样例说明 1

JOIIOI 分别含子串 `JOI` 和子串 `IOI` 各一个，故可以做出 $ 2 $ 个迷你 JOIOI 塔。

#### 输入样例 2
```plain
5
JOIOI
```
#### 输出样例 2
```plain
1
```
#### 样例说明 2

虽然 JOIOI 也分别含子串 `JOI` 和子串 `IOI` 各一个，但每个字符不能被使用两次或以上。

#### 输入样例 3
```plain
6
JOIOII
```
#### 输出样例 3
```plain
2
```
#### 样例说明 3

此样例对应题目描述中的例子。

#### 输入样例 4
```plain
15
JJOIIOOJOJIOIIO
```
#### 输出样例 4
```plain
4
```

# 数据范围与提示

对于所有数据，$1\leq N \leq 10^6$。

|子任务|分值|$N\le$|
|:-:|:-:|:-:|
|$1$|$10$|$ N \leq 15 $|
|$2$|$20$|$ N \leq 50 $|
|$3$|$20$|$ N \leq 3000 $|
|$4$|$50$|$ N \leq 10^6 $|


