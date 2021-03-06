
# 题目描述

**题目译自 [ROI 2017](http://neerc.ifmo.ru/school/archive/2016-2017.html) Day 1 T4.** ***[Путешествие в Метрополис](http://neerc.ifmo.ru/school/archive/2016-2017/ru-olymp-roi-2017-day1.pdf)***

某国有编号为 $1$ 到 $n$ 的 $n$ 座城市，还有编号为 $1$ 到 $m$ 的 $m$ 条铁路线。$i$ 号铁路线被沿途 $(s_i+1)$ 座城市分为 $s_i$ 段。$i$ 号铁路线从起点到终点依次经过 $v_{\large i,1},$ $v_{\large i,2},$ $\dots,$ $v_{\large i,s}$ 号城市，城市 $v_{\large i,j}$ 通过这条线路到城市 $v_{\large i,j+1}$ 花费的时间为 $t_{\large i,j}$。**注意，本题中铁路线均为单向。**  
现在，你位于 $1$ 号城市，你想要坐火车前往 $n$ 号城市，途中可以换乘。你希望花费的时间最少，并且在花费时间最少的情况下使经过任意两个相邻城市所花费时间的平方和尽可能大，保证给你的图是一个连通图。

# 输入格式

第一行，两个整数 $n,m$，表示有 $n$ 个城市，$m$ 条铁路线。  
以下 $m$ 行，每行描述一条铁路线：  
开头一个整数 $s_i$，之后 $(2s_i+1)$ 个整数：$v_{\large i,1},$ $t_{\large i,1},$ $v_{\large i,2},$ $t_{\large i,2},$ $v_{\large i,3}$ $\dots$ $t_{\large i,s_i},$ $v_{\large i,s_i+1}$。  

# 输出格式

一行，两个整数 $time,score$，表示最少花费时间与最大的平方和。

# 样例

#### 样例输入 1
```plain
2 1
1 1 3 2
```
#### 样例输出 1
```plain
3 9
```

#### 样例输入 2
```plain
5 2
4 1 3 2 3 3 5 5 10 4
3 4 2 2 1 3 4 1
```
#### 样例输出 2
```plain
9 35
```

#### 样例说明 2
样例 2 如图所示。  

<div style="text-align: center;">
<img src="/source/loj/2769/img/aHR0cHM6Ly9naXRlZS5jb20vbWluZ3FpaHVhbmcvcGljcy9yYXcvbWFzdGVyL3d3dy5hbGx0b2FsbC5uZXRfdHJhaW5zLTJfMmdudmRWZlBXbS5zdmc=.svg" width="40%" style="margin: 0 auto;">  
</div>

从 $1$ 号城市乘坐 $1$ 号线直达 $5$ 号城市并非最佳方案（无法达到最短时间）。  
最佳方案：
* 从 $1$ 号城市乘坐 $1$ 号线到 $2$ 号城市；
* 换乘 $2$ 号线，坐到 $3$ 号城市；
* 再换乘 $1$ 号线，坐到 $5$ 号城市。

此时，平方和为 $3^2 + 1^2 + 5^2 = 35$。  
注意，这组样例不属于子任务 1 和子任务 2。

#### 样例输入 3
```plain
5 2
3 1 1 2 2 3 3 4
3 2 2 3 3 4 4 5
```
#### 样例输出 3
```plain
10 82
```

#### 样例说明 3
无论是在中途哪一站转 2 号线，结果都一样。平方和为 $1^2+9^2=82$。  
注意，这组样例同样不属于子任务 1 和子任务 2。

# 数据范围与提示

对于 $100\%$ 的数据，$2 ⩽ n ⩽ 10^6,$ $1 ⩽ m ⩽ 10^6,$ $1 ⩽ v_{\large i,j} ⩽ n,$ $1 ⩽ t_{\large i,j} ⩽ 1000,$ $1 ⩽ \sum s_i ⩽ 10^6$。

|子任务|分值|$n$|$s_i$|
|:-:|:-:|:-:|:-:|
|1|10|$n ⩽ 10$|$\sum s_i ⩽ 20, s_i = 1$|
|2|&nbsp;10&nbsp;|$n ⩽ 1000$|$\sum s_i ⩽ 1000, s_i = 1$|
|3|17|$n ⩽ 1000$|$\sum s_i ⩽ 1000$|
|4|&nbsp;17&nbsp;|$n ⩽ 1000$|$\sum s_i ⩽ 10^5$|
|5|19|$n ⩽ 10^4$|$\sum s_i ⩽ 2×10^5$|
|6|&nbsp;19&nbsp;|$n ⩽ 2×10^5$|$\sum s_i ⩽ 2×10^5$|
|7|8|$n ⩽ 10^6$|$\sum s_i ⩽ 10^6$|

