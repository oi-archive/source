
# 题目描述

**译自 [COCI 2020/2021 Contest #1](https://hsin.hr/coci/archive/2020_2021/contest1_tasks.pdf) T3「3D Histogram」**

> <b>Malnar 先生（通过电话）：</b>听着，我曾在大半夜在 Zagreb 周边贴过一些海报。我遇见了一排栅栏，用不同高度的木板拼成的栅栏，我正想着如何计算我能在这排栅栏上贴上的最大的海报面积。你觉得那会是一道不错的 COCI 题吗？
> 
> <b>同事：</b>你在干啥啊？！而且吧，这题也不怎么好。不过是一个用单调队列的套路题罢了，我们甚至在我们的 x 令营里教小学生这些东西呢。
> 
> <b>Malnar 先生：</b>如果你稍微改编一下，比如对每个前缀都求一遍之类的，那应该够难了吧。
> 
> <b>同事：</b>那就和去年我们的 [CERC 资格赛](https://hsin.hr/studenti2019/zadaci/zadaci.pdf)撞题了（H 题）。那题挺难的，难点在 [Harbingers](https://vjudge.net/problem/Gym-207383I) 一题（CEOI 2009）采用的技巧上（指在凸包上二分更新 DP），但是现在大家都见过了。
> 
> <b>Malnar 先生：</b>你确定我们真的束手无策了吗？
> 
> <b>同事：</b>我觉得我们已经出完了所有直方图类型的题目了。COCI 2010/2011 的 [Tabovi](https://hsin.hr/coci/archive/2010_2011/contest1_tasks.pdf)，COCI 2015/2016 的 [Poplava](https://hsin.hr/coci/archive/2015_2016/contest5_tasks.pdf)，COCI 2017/2018 的 [Krov](https://hsin.hr/coci/archive/2017_2018/contest4_tasks.pdf)，2018 年的 IOI 选拔赛的 [Histogram](https://hsin.hr/pripreme2018/zadaci/prvi/zadaci.pdf)…… 你懂的。
> 
> <b>Malnar 先生：</b>如果直方图是三维的呢？
> 
> <b>同事：</b>嗯……

给定一张三维的直方图，包含 $n$ 个接连排列的块。第 $i$ 个块有 $1$ 米宽，$a_i$ 米高，$b_i$ 米长。换句话说，从前面看，就像是每组高度分别为 $a_1, a_2, \ldots , a_n$ 的直方图，从上面看，就像是每组高度分别为 $b_1, b_2, \ldots , b_n$ 的直方图。

请求出三维直方图中能放下的最大体积的长方体。长方体的各个面需要和组成三维直方图的所有块的各个面平行。

# 输入格式

第一行一个正整数 $n$。  
接下来 $n$ 行，第 $i$ 行两个正整数 $a_i, b_i$。

# 输出格式

输出最大的体积的立方米数。

# 样例

#### 样例输入 1

```plain
5
5 3
4 4
2 1
3 2
1 5
```

#### 样例输出 1

```plain
24
```

#### 样例解释 1

下图显示了样例 1 的三维直方图。最大体积的长方体使用了前两个块的一部分，有 $2$ 米宽，$4$ 米高，$3$ 米长。它的体积为 $2 \cdot 4 \cdot 3 = 24$ 立方米。

<img src="/source/loj/3370/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8xMC8xOS81ZjhjNmJkNzNkOTRjLnBuZw==.png" width="35%" style="clear: both; display: block; margin: auto"/>

#### 样例输入 2

```plain
6
3 1
2 1
2 2
2 3
1 1
2 2
```

#### 样例输出 2

```plain
8
```

#### 样例输入 3

```plain
5
15 19
5 6
1 13
3 7
1 2
```

#### 样例输出 3

```plain
285
```

# 数据范围与提示

| 子任务编号 | 分值 | 特殊限制                      |
| :--------: | :--: | :---------------------------: |
| $1$        | $18$ | $1 \le n \le 2000$            |
| $2$        | $82$ | $1 \le n \le 2 \times {10}^5$ |

----

译者：[PinkRabbit](https://loj.ac/user/9437)

