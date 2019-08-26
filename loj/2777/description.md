
# 题目描述

**题目译自 [BalticOI 2018](https://boi2018.progolymp.se/tasks/) Day2「[Alternating Current](https://boi18-day2-open.kattis.com/problems/boi18.alternating)」**

给一个环，这个环可以被分为等长的 $N$ 段，分别标号为 $1\ldots N$。同时你可以通过 $M$ 个控制点将环的某一段染成红色或蓝色，这 $M$ 个控制点分别编号为 $1\ldots M$。

如何安排这 $M$ 个点控制的线段的颜色，使得轨道上每个点都被至少一条红色线段和至少一条蓝色线段覆盖。

保证这个环中不存在不能被染色的部分。

# 输入格式

第一行包含两个整数 $N$ 和 $M$，分别表示轨道段数和控制点个数。

接下来 $M$ 行，每行两个整数 $a$ 和 $b$，分别表示每一个控制点可以控制颜色的左右端点。特别地，若 $a=b$ 则这个控制点只控制 $a$ 这一条长度为 $1$ 的线段；若 $b < a$ 则说明这个控制点能控制编号在区间 $[a,\, N]\cup[1,\,b]$ 内的所有线段。

# 输出格式

输出一行 $M$ 个字符，每个字符是 ``0`` 或 ``1``，分别表示设置在第 $i$ 个控制点控制的线段上，染成红色还是蓝色。

如果有多组解请输出任意一组，如果无解请输出 ``impossible``。


# 样例

#### 样例 1 输入
```plain
10 5
1 5
6 7
5 1
7 2
2 4
```
#### 样例 1 输出
```plain
00101
```
#### 样例 1 解释
<img src="source/loj/2777/img/aHR0cHM6Ly9naXRlZS5jb20vbWluZ3FpaHVhbmcvcGljcy9yYXcvbWFzdGVyL2FsdGVybmF0aW5nZmlnLnBkZi5zdmc=.svg" width = 30%>

上图为样例 1 的一组解。注意可以将所有的箭头反向得到另一组合法解 ``11010``。
#### 样例 2 输入
```plain
10 5
1 4
2 5
4 7
6 10
8 1
```
#### 样例 2 输出
```plain
impossible
```
#### 样例 3 输入
```plain
5 2
1 5
3 3
```
#### 样例 3 输出
```plain
impossible
```
#### 样例 4 输入
```plain
5 3
3 3
2 1
4 2
```
#### 样例 4 输出
```plain
101
```

# 数据范围与提示

|子任务|分值|数据范围|附加限制|
|:----:|:--:|:------:|:------:|
|$1$   |$13$|$2\leqslant N,\,M\leqslant15$||
|$2$   |$20$|$2\leqslant N,\,M\leqslant100$||
|$3$   |$22$|$2\leqslant N,\,M\leqslant1000$||
|$4$   |$19$|$2\leqslant N,\,M\leqslant100\,000$|保证 $b\geqslant a$|
|$5$   |$26$|$2\leqslant N,\,M\leqslant100\,000$|　|
**请注意在 LibreOJ 上共有 $6$ 个子任务，其中第一个子任务为样例。**

