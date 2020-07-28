
# 题目描述

> 小d是4xx9小游戏高手。

有一天，小d发现了一个很经典的小游戏：跳青蛙。

游戏在一个**5**个格子的棋盘上进行。在游戏的一开始，最左边的两个格子上各有一个向右的青蛙，最右边的两个格子上各有一个向左的青蛙。

![](/source/loj/2327/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTcvMTIvMTQvNWEzMjYyMjUwOGVhOS5wbmc=.png)<!-- <img src="/source/loj/2327/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTcvMTIvMTQvNWEzMjYyMjUwOGVhOS5wbmc=.png" alt="img"align="middle"width="50.0%"/>-->

每次移动可以选取一个青蛙，向这只青蛙的前方移动一格到空格子中或跳过前方的**一个不同朝向**的青蛙并移动到空格子中。

 ![](https://i.loli.net/2017/12/14/5a3262250ca07.png)<!--<img src="/source/loj/2327/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTcvMTIvMTQvNWEzMjYyMjUwY2EwNy5wbmc=.png" alt="img"align="middle"width="50.0%"/> -->

![](/source/loj/2327/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTcvMTIvMTQvNWEzMjYyMjUwZTM4YS5wbmc=.png) <!--<img src="/source/loj/2327/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTcvMTIvMTQvNWEzMjYyMjUwZTM4YS5wbmc=.png" alt="img"align="middle"width="50.0%"/> -->

为了使你更好地理解这个游戏，我们下发了一个游戏demo作为参考（**注意**：这个demo中的棋盘大小和题目中并不相同）。

这个游戏本身当然难不倒小d，小d轻松地就解决了这个游戏。但是一个人玩游戏实在是太寂寞了，于是小d找到了小m和他一起玩耍。小d规定，自己只能操控向右的青蛙，小m只能操控向左的青蛙。

小d很快发现，这个游戏想要做到双方轮流行动，就无法达到交换所有青蛙的游戏结局。于是，小d打开了`m`个游戏，并规定双方轮流行动，每次选择其中一个游戏并控制自己的青蛙行动一步（不能不动）。小d发现，这么做的话就能够使大部分的游戏最终都交换所有的青蛙了。

由于小d是坑队友高手，所以他们玩了一会之后，就开始互相坑害对方，都希望使对方无法行动。他们约定，当轮到一方行动时，若其所有的青蛙都无法行动，则**对方**获得游戏的胜利。正当博弈论大师小d计算着谁会成为最后的胜者时，电脑卡死了。小d发现，只能kill掉一些游戏才能使剩下的游戏进行下去了。由于电脑已经卡死了，小d无法自由选择kill掉哪些游戏，只能运行系统自带的随机kill小程序。具体来说，小d运行这个随机kill小程序之后，每个游戏有$\frac{1}{2}$的概率被kill掉，有$\frac{1}{2}$的概率能够继续下去。游戏之间被kill掉的概率是独立的。

小d思考了一番，决定如果运行小程序之后他的胜率过低，就直接重启电脑。这时，小d突然发现自己已经不记得刚才轮到谁行动了，于是他决定综合考虑自己先手和后手的胜率。

小d并不擅长概率论，他想让你告诉他运行小程序后，剩下的局面为小d必胜、小m必胜、先手必胜、后手必胜的概率各为多少，这样他才能更好地决定是否重启电脑。

为了避免精度问题，输出答案乘 $2^m$ 之后对 $998244353$ 取模的结果。

**注意：题目并不保证输入的所有`m`个状态中小m和小d之前的总行动步数相差不超过1，但是保证不会出现起始状态无法到达的状态。**


# 输入格式

从标准输入读入数据。

我们使用一个长度为5的字符串来表示一个状态，其中，`L`表示面朝**右**的青蛙，`R`表示面朝**左**的青蛙，`_`（下划线）表示空格子。例如，初始状态为`LL_RR`。

本题含有多组数据，第一行两个整数`T,C`($1\leq C\leq 100$)分别表示测试点编号和数据组数。

对于每组数据，第一行一个整数`n`($1\leq n\leq 23$)表示不同状态的棋盘个数，接下来`n`行每行一个长度为5的字符串$s_i$和一个正整数$a_i$($1\leq a_i\leq 10^6$)，分别表示棋盘的状态和在该状态下的棋盘的个数。

保证输入的字符串合法且不重复。


# 输出格式

输出到标准输出。

定义$m=\sum a_i$。

对于每组数据，输出一行四个整数，分别表示小d必胜（即L的控制方必胜）、小m必胜（即R的控制方必胜）、先手必胜、后手必胜的概率乘$2^m$之后对$998244353$取模的结果。


# 样例

#### 样例输入1

```plain
0 1
1
LL_RR 1

```



#### 样例输出1

```plain
0 0 1 1

```


#### 样例输入2

```plain
0 1
3
LRRL_ 1
LRR_L 1
LLR_R 1

```



#### 样例输出2

```plain
4 2 0 2

```






#### 样例输入3

```plain
0 1
1
LRRL_ 1000000

```



#### 样例输出3

```plain
421273116 0 0 1

```


### 样例1解释

对于样例1，若该游戏没有被kill，双方唯一可能的操作序列为`LL_RR -> L_LRR -> LRL_R -> LR_LR -> LRRL_ -> LRR_L -> L胜`，小m先手时同理，故该情况为先手必胜。若该游戏被kill了，双方都没有合法行动，后手必胜。

### 样例2解释

对于样例2，令这三个棋盘的状态从上到下为`A,B,C`，则$\{A,B,C\},\{A,B\},\{A,C\},\{A\}$为小d必胜，$\{C\},\{B,C\}$为小m必胜，$\{B\},\{\}$为后手必胜。


# 数据范围与提示

保证数据中不会出现从`LL_RR`状态无法到达的状态（如`RLLR_`），故合法的状态共有23种。

定义 **$k-$不可达点** 为从`LL_RR`操作$k$次（双方加起来一共操作$k$次，顺序任意）后依然无法到达的合法状态，如 1-不可达点 为 ：全集$\setminus${`LL_RR`,`L_LRR`,`LLR_R`} 共20个， 5-不可达点 为{`RLR_L`,`RRL_L`,`RR_LL`,`R_LRL`,`R_RLL`}。

对于100%的数据，$1\leq n\leq 23$,$1\leq m\leq 10^6$,$1\leq C\leq 100$，所有可能出现在该数据点的状态均为等概率出现（也就是说你可以认为最后一个点中每种状态的$a_i$之和大约为$10^8/23$）。

 <!-- BEGIN: Migrated markdown table -->

| 测试点编号( $ T $ ) | $ C $ | $ m $ | 其他 |
|-|-|-|-|
| 1 | =100 | =1 | 无限制 |
| 2 | =100 | $ \leq 5 $ | 无限制 |
| 3 | =100 | $ \leq 8 $ | n=m |
| 4 | =100 | $ \leq 10 $ | n=m |
| 5 | =100 | 无限制 | n=1 |
| 6 | =100 | 无限制 | n=1 |
| 7 | =100 | $ \leq 500 $ | 只含5-不可达点 |
| 8 | =100 | $ \leq6\times 10^5 $ | 只含5-不可达点 |
| 9 | =100 | $ \leq 100 $ | 只含2-不可达点 |
| 10 | =100 | $ \leq7\times 10^5 $ | 只含2-不可达点 |
| 11 | =100 | $ \leq 16 $ | 只含1-不可达点 |
| 12 | =100 | $ \leq8\times 10^5 $ | 只含1-不可达点 |
| 13 | =100 | $ \leq 14 $ | 只含0-不可达点 |
| 14 | =100 | $ \leq9\times 10^5 $ | 只含0-不可达点 |
| 15 | =100 | $ \leq 12 $ | 无限制 |
| 16 | =100 | $ \leq 5000 $ | 无限制 |
| 17 | =100 | $ \leq 10^5 $ | 无限制 |
| 18 | =100 | $ \leq2\times 10^5 $ | 无限制 |
| 19 | =100 | 无限制 | 无限制 |
| 20 | =100 | 无限制 | 无限制 |

<!-- Migrated from original HTML table:
<table><thead><tr><th rowspan="1">测试点编号( $ T $ )</th><th rowspan="1"> $ C $ </th><th rowspan="1"> $ m $ </th><th rowspan="1">其他</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">=100</td><td rowspan="1">=1</td><td rowspan="1">无限制</td></tr><tr><td rowspan="1">2</td><td rowspan="1">=100</td><td rowspan="1"> $ \leq 5 $ </td><td rowspan="1">无限制</td></tr><tr><td rowspan="1">3</td><td rowspan="1">=100</td><td rowspan="1"> $ \leq 8 $ </td><td rowspan="1">n=m</td></tr><tr><td rowspan="1">4</td><td rowspan="1">=100</td><td rowspan="1"> $ \leq 10 $ </td><td rowspan="1">n=m</td></tr><tr><td rowspan="1">5</td><td rowspan="1">=100</td><td rowspan="1">无限制</td><td rowspan="1">n=1</td></tr><tr><td rowspan="1">6</td><td rowspan="1">=100</td><td rowspan="1">无限制</td><td rowspan="1">n=1</td></tr><tr><td rowspan="1">7</td><td rowspan="1">=100</td><td rowspan="1"> $ \leq 500 $ </td><td rowspan="1">只含5-不可达点</td></tr><tr><td rowspan="1">8</td><td rowspan="1">=100</td><td rowspan="1"> $ \leq6\times 10^5 $ </td><td rowspan="1">只含5-不可达点</td></tr><tr><td rowspan="1">9</td><td rowspan="1">=100</td><td rowspan="1"> $ \leq 100 $ </td><td rowspan="1">只含2-不可达点</td></tr><tr><td rowspan="1">10</td><td rowspan="1">=100</td><td rowspan="1"> $ \leq7\times 10^5 $ </td><td rowspan="1">只含2-不可达点</td></tr><tr><td rowspan="1">11</td><td rowspan="1">=100</td><td rowspan="1"> $ \leq 16 $ </td><td rowspan="1">只含1-不可达点</td></tr><tr><td rowspan="1">12</td><td rowspan="1">=100</td><td rowspan="1"> $ \leq8\times 10^5 $ </td><td rowspan="1">只含1-不可达点</td></tr><tr><td rowspan="1">13</td><td rowspan="1">=100</td><td rowspan="1"> $ \leq 14 $ </td><td rowspan="1">只含0-不可达点</td></tr><tr><td rowspan="1">14</td><td rowspan="1">=100</td><td rowspan="1"> $ \leq9\times 10^5 $ </td><td rowspan="1">只含0-不可达点</td></tr><tr><td rowspan="1">15</td><td rowspan="1">=100</td><td rowspan="1"> $ \leq 12 $ </td><td rowspan="1">无限制</td></tr><tr><td rowspan="1">16</td><td rowspan="1">=100</td><td rowspan="1"> $ \leq 5000 $ </td><td rowspan="1">无限制</td></tr><tr><td rowspan="1">17</td><td rowspan="1">=100</td><td rowspan="1"> $ \leq 10^5 $ </td><td rowspan="1">无限制</td></tr><tr><td rowspan="1">18</td><td rowspan="1">=100</td><td rowspan="1"> $ \leq2\times 10^5 $ </td><td rowspan="1">无限制</td></tr><tr><td rowspan="1">19</td><td rowspan="1">=100</td><td rowspan="1">无限制</td><td rowspan="1">无限制</td></tr><tr><td rowspan="1">20</td><td rowspan="1">=100</td><td rowspan="1">无限制</td><td rowspan="1">无限制</td></tr></tbody></table>
-->

<!-- END: Migrated markdown table --> 

