
# 题目描述

**译自 BalticOI 2011 Day1 T4「Treasures and Vikings」**  

> 官方数据似乎有问题，会出现空输入……空输入已经删除了，所以测试数据的编号并不连续。

你有一张藏宝图，藏宝图可视为 $N×M$ 的网格。每个格子可能是你的船、贼船、海、陆地或藏宝点。你只有一条船，整张图只有一条贼船。你和贼船都只能在海域移动。藏宝点在海中。  
你与贼船交替移动，你移动一次+贼船移动一次算作一回合。每次移动，你可以移动到上下左右四个相邻格子中的一格，也可以不移动。贼船的移动同理，贼船也可以不移动。你先移动。  
每一回合结束后，如果你和贼船在同一行或同一列，你就挂了；在你没挂的情况下，如果你位于藏宝点，你就拿到了宝藏。  
请问：是否有一条安全的路径，使得无论贼船怎么跑你都能或者拿到宝藏。

You have a treasure map that is arranged into a $N ×M$ grid. A grid square may be either sea or part of an island. In addition, the map shows the treasure and an enemy Viking ship that occupies one (sea) square. Finally, for convenience you have also drawn your own position.  
Now you must set up a fixed route to get the treasure. The route must start at your position, end at the treasure, and consist of a sequence of moves. In each move, you can go only to an (horizontally or vertically) adjacent square that is not part of an island. But beware: The Viking ship might follow you, using the same kind of moves! After each of your moves according to your route, the Viking ship may move or not. Your move and the Vikings’ reaction together is called a round.  
After every round, the following checks are made:  
* If you are in line with the Viking ship (you are in the same vertical or horizontal line as the Viking ship with only sea between the Viking ship and you), you are dead.
* If you aren’t dead and at the treasure-spot, you get the treasure.

Write a program that decides whether it is possible to set up a fixed route in advance such that you can get the treasure by following this route and will not get killed by the Vikings – no matter how the Viking ship moves.

# 输入格式

第一行有两个整数 $N$ 和 $M$。  
在接下来的 $N$ 行中，每行 $M$ 个字符。字符的含义如下：

|字符|$\texttt{.}$|$\texttt{I}$|$\texttt{V}$|$\texttt{Y}$|$\texttt{T}$|
|-|-|-|-|-|-|
|含义|海|陆地|贼船|你|藏宝点|

保证只会出现表中的五种字符，保证 $\texttt{V, Y, T}$ 都只出现一次。

The first line of input contains two integers $N$ and $M$, the dimensions of the map. Each of the following $N$ lines contain $M$ characters. Each character describes a square in the map, and is either $\texttt{.}$ (sea), $\texttt{I}$ (part of an island), $\texttt{V}$ (the Viking ship), $\texttt{Y}$ (your position), or $\texttt{T}$ (the treasure). Each of $\texttt{V}$, $\texttt{Y}$, and $\texttt{T}$ will occur exactly once.

# 输出格式

输出 $\texttt{YES}$ 或 $\texttt{NO}$，表示是否有一条安全的路径。

The only line of the output must contain the string $\texttt{YES}$, if it is possible to set up a route to get the treasure, or $\texttt{NO}$ otherwise.

# 样例

#### 样例输入 1
```plain
5 7
Y.....V
..I....
..IIIII
.......
...T...
```

#### 样例输出 1
```plain
YES
```

#### 样例解释 1
路线：下下下右右右下。

#### 样例输入 2
```plain
5 7
Y....V.
..I....
..IIIII
.......
...T...
```

#### 样例输出 2
```plain
NO
```

#### 样例输入 3
```plain
2 3
.YT
VII
```

#### 样例输出 3
```plain
NO
```

# 数据范围与提示

对于 50% 的数据，$1 ≤ N,M ≤ 200$。  
对于所有数据，$1 ≤ N,M ≤ 700$。

