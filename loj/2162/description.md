
# 题目描述

**译自 POI 2011 Round 2. Day 1. B「[Garbage](https://szkopul.edu.pl/problemset/problem/Oa79BU5CwOGRXG_BHQN1tZJ8/site/?key=statement)」**

给定一张 $n$ 个点 $m$ 条边的无向图，每条边居黑白二色之一，且有一个黑或白的目标颜色。

有一辆卡车，可以从任意一个结点开始，经过一个简单环（不经过重复边或起点以外结点的环）回到出发点，将所有经过边的颜色反转，即黑色变为白色，白色变为黑色。卡车可以从不同的结点出发行走若干次。

请给出一个合法的方案，使得每条边最终都变为目标颜色，或判定不可行。

---

The Byteotian Waste Management Company (BWMC) has drastically raised the price of garbage collection lately. This caused some of the citizens to stop paying for collecting their garbage and start disposing of it in the streets. Consequently, many streets of Byteburg are literally buried under litter.

The street system of Byteburg consists of $ n $ intersections, some of which are directly connected with bidirectional streets. No two streets connect the same pair of intersections. Some of the streets are littered while others are not.

The mayor of Byteburg, Byteasar, has decided on an unprecedented action to persuade the citizens to pay for waste collection. Namely, he decided to clean only some of the streets - precisely those that the majority of people living on paid for garbage collection. The streets that the majority of people living on did not pay for waste collection, on the other hand, will thus remain littered - or if it is called for - will become littered by the garbage collected from other streets! Byteasar has already prepared a city map with the streets to be cleaned and to remain or become littered marked on. Unfortunately, the BWMC employees cannot comprehend his master plan. They are, however, quite capable of carrying out simple instructions.

A single such instruction consists in driving the garbage truck along a route that starts on an arbitrary intersection, goes along any streets of choice, and ending on the very same intersection that it started on. However, every intersection can be visited at most once on a single route, except for the one it starts and ends with-the garbage truck obviously appears twice on that one. The truck cleans a littered street it rides along, but on the other hand it dumps the waste on the clean streets along its route, making them littered.

Byteasar wonders if it is possible to execute his plan by issuing a number of aforementioned route instructions. Help him out by writing a program that determines a set of such routes or concludes that it is impossible.

# 输入格式

输入的第一行包含两个空格分隔的正整数 $n$ 和 $m$（$1 \leq n \leq 100\,000$，$1 \leq m \leq 1\,000\,000$），表示图的点数和边数。

接下来 $m$ 行，每行包含四个空格分隔的正整数 $a, b, s, t$（$1 \leq a \lt b \leq n$，$s, t \in \{0, 1\}$），表示一条联结结点 $a$ 与 $b$ 的边，初始颜色和目标颜色分别为 $s$ 与 $t$。

你可以认为若存在合法方案，则存在一个卡车经过总边数不超过 $5m$ 的方案。

对于 $60\%$ 分数的数据，有 $m \leq 10\,000$。

---

There are two integers, separated by a single space, in the first line of the standard input: $ n $ and $ m $($ 1 \le n \le 100000 $, $ 1 \le m \le 1000000 $), denoting the number of intersections and the number of streets in Byteburg, respectively. The intersections are numbered from $ 1 $ to $ n $. The following $ m $ lines specify successive streets, one per line. Each of those lines holds four integers separated by single spaces: $ a $, $ b $, $ s $ and $ t $($ 1 \le a \lt b \le n $, $ s, t \in \{0, 1\} $). Such a quadruple specifies that the intersections $ a $ and $ b $ are connected with a street, $ s $ tells if the street is currently littered ($ 0 $ means clean, while $ 1 $ means littered), and $ t $ tells if the street should be littered according to Byteasar's plan.

You may assume that if there exists a set of routes to carry out Byteasar's plan, then there is one in which the total number of streets that the garbage truck follows does not exceed $ 5 \cdot m $.

In tests worth 60% of the points it additionally holds that $ m \le 10000 $.


# 输出格式

如果不存在合法方案，输出一行 `NIE`（波兰语「否」）；

否则按下列格式输出任意一种方案：
* 第一行包含一个整数 $k$，表示卡车行驶环路的总数；
* 接下来 $k$ 行，每行描述一条环路：
  * 首先是一个正整数 $k_i$ 表示环路经过的边数，后接一个空格；
  * 接下来 $k_i + 1$ 个空格分隔的整数，依次表示环路上结点的编号。

---

If there is no set of routes for the garbage truck to execute Byteasar's plan, then the word "`NIE`" (no in Polish) should be printed out to the first and only line of the standard output. Otherwise, an arbitrary set of routes that does execute Byteasar's plan and has the truck move along no more than $ 5 \cdot m $ streets in total should be printed out. Then the first line should hold the number $ k $ of routes in the set. The following $ k $ lines should describe the routes, one per line. The $ (i + 1) $-th line should start with a positive integer $ k_i $ equal to the number of streets in the $ i $-th route. After a single space, $ k_i +1 $ numbers of successive intersections along the route should follow, separated by single spaces.


# 样例

细线=初始白色，粗线=初始黑色；  
虚线=目标白色，实线=目标黑色。

#### 样例输入 1
```plain
6 8
1 2 0 1
2 3 1 0
1 3 0 1
2 4 0 0
3 5 1 1
4 5 0 1
5 6 0 1
4 6 0 1
```
![smizad1.gif](/source/loj/2162/img/aHR0cHM6Ly9vb28uMG8wLm9vby8yMDE3LzA0LzIwLzU4Zjg0Mjk3ZWZiOTUuZ2lm.gif)

#### 样例输出 1
```plain
2
3 1 3 2 1
3 4 6 5 4
```

#### 样例输入 2
```plain
6 8
1 2 0 1
2 3 1 0
1 3 0 1
2 4 0 0
3 5 1 1
4 5 0 1
5 6 0 1
4 6 0 0
```
![smizad2.gif](/source/loj/2162/img/aHR0cHM6Ly9vb28uMG8wLm9vby8yMDE3LzA0LzIwLzU4Zjg0Mjk4ZDViZGIuZ2lm.gif)

#### 样例输出 2
```plain
NIE
```
---

The clean streets are drawn with a thin line in the figure, whereas the littered streets are drawn with a thick line. The streets that are to be clean are drawn with a dashed line, while those that are to be littered are drawn with a solid line.

For the input data
```plain
6 8
1 2 0 1
2 3 1 0
1 3 0 1
2 4 0 0
3 5 1 1
4 5 0 1
5 6 0 1
4 6 0 1
```
![smizad1.gif](/source/loj/2162/img/aHR0cHM6Ly9vb28uMG8wLm9vby8yMDE3LzA0LzIwLzU4Zjg0Mjk3ZWZiOTUuZ2lm.gif)

one of correct results is:
```plain
2
3 1 3 2 1
3 4 6 5 4
```
whereas for the following input data:
```plain
6 8
1 2 0 1
2 3 1 0
1 3 0 1
2 4 0 0
3 5 1 1
4 5 0 1
5 6 0 1
4 6 0 0
```
![smizad2.gif](/source/loj/2162/img/aHR0cHM6Ly9vb28uMG8wLm9vby8yMDE3LzA0LzIwLzU4Zjg0Mjk4ZDViZGIuZ2lm.gif)

the correct result is:
```plain
NIE
```

# 数据范围与提示

Task author: Michal Pilipczuk.  
SPJ: ceba.  
Translation: Red Scarf.

