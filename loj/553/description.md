
# 题目描述

取石子游戏的规则是这样的：有若干堆石子，两个玩家轮流操作，每个玩家每次要选一堆取走任意多个石子，但不能不取，无石子可取者输。

现在共有 $n$ 堆石子，其中第 $i$ 堆的数量为 $l_i$，现在 LCR 需要在每一堆中扔掉一部分（可以不扔也可以全扔），如果第 $i$ 堆的石子在 LCR 操作后**还有剩余**，LCR 就需要付出 $v_i$ 的代价。LCR 操作完成后神犇会搬来新的一堆个数在 $[0,m]$ 之间的石子，两人玩取石子游戏，LCR 先手。神犇搬运新的一堆石子时会保证自己（后手）必胜，如果他无法做到这一点，就会立即结束游戏。

现在 LCR 有 $q$ 次询问，每次给出一个 $c\in [0,m]$，请你回答如果要让神犇搬来的石子数为 $c$（不能让神犇结束游戏，即使这里要求 $c=0$），LCR 付出代价的总和至少是多少。如果 LCR 不可能通过调整石子使得神犇搬来的石子数为 $c$，输出 `-1`。

<div class="lang-divider"></div>

[NIM](https://en.wikipedia.org/wiki/Nim) is a game of strategy in which two players take turns removing stones from distinct piles. On each turn, a player must remove at least one stone, and may remove any number of stones provided they all come from the same pile. **The player who has no stones to remove loses**.

There are $n$ piles of stones, the $i$-th pile has $l_i$ stones. Alice needs to remove some of the stones from each pile (removing zero or all of the stones from a certain pile is allowed). If the $i$-th pile remains at least one stone after this operation, Alice has to pay a price of $v_i$. After Alice's operation, Bob will create a pile of stones whose number is in $[0,m]$ and add it to the game to make sure that Alice — the player who moves first in this NIM game will lose.If he can't ensure that Alice will lose,he will exit from the game immediately.  

Now Alice has $q$ queries. Each query gives an integer $c$, and you need to calculate the minimal total price Alice needs to pay to ensure Bob’s new pile has exactly $c$ stones(making Bob exit from the game isn't allowed,even if $c=0$). If this is impossible, print `-1` instead. 

# 输入格式

第一行两个正整数 $n,m$。

接下来 $n$ 行每行两个正整数 $v_i,l_i$ 表示该堆石子的代价和数量。 

接下来一行一个正整数 $q$。

接下来 $q$ 行每行一个正整数 $c$ 表示询问。

<div class="lang-divider"></div>

The first line contains two integers $n,m$.  
Each of the following $n$ lines contains two integers $v_i,l_i$.  
The next line contains an integer $q$.
Each of the following $n$ lines contains an integers $c$.  

# 输出格式

输出共 $q$ 行，依次表示每次询问的答案，无解输出 `-1`。

<div class="lang-divider"></div>

Output contains $q$ lines,containing the answer of each query in order.

# 样例

#### 样例输入
```plain
4 6
2 3
4 4
3 5
5 2
7
0
1
2
3
4
5
6
```

#### 样例输出
```plain
0
2
2
2
3
3
5
```

<div class="lang-divider"></div>

#### Sample Input
```plain
4 6
2 3
4 4
3 5
5 2
7
0
1
2
3
4
5
6
```

#### Sample Output
```plain
0
2
2
2
3
3
5
```

# 数据范围与提示

对于所有数据，$1\le n,q \le 10^5,1\le v_i \le 10^9,0\le l_i\le m\le 10^9,c\in [0,m]$。

详细的数据限制及约定如下（留空表示和上述所有数据的约定相同）：

|Subtask #|分值（百分比）|$n,q$|$l_i,m$|特殊性质|
|:-:|:-:|:-:|:-:|:-:|
|$1$|$15$|$\le 10$|$\le 10$|-|
|$2$|$20$|$\le 100$|$\le 100$|-|
|$3$|$20$|-|-|对于每个 $i$ 存在非负整数 $k$ 满足 $l_i=2^k-1$|
|$4$|$20$|$\le 20000$|$\le 20000$|$l_i,v_i$ 在范围内均匀随机（使用 `std::mt19937` 并对最大值取模）|
|$5$|$25$|-|-|$l_i,v_i$ 在范围内均匀随机（使用 `std::mt19937` 并对最大值取模）|

<div class="lang-divider"></div>

For all test cases, $1\le n,q \le 10^5,1\le v_i \le 10^9,0\le l_i\le m\le 10^9,c\in [0,m]$.

Detailed constraints and hints are as follows (blank grids denote the same constraints as mentioned above):

|Subtask #|Score (percentage)|$n,q$|$l_i,m$|Special Constraints|
|:-:|:-:|:-:|:-:|:-:|
|$1$|$15$|$\le 10$|$\le 10$|-|
|$2$|$20$|$\le 100$|$\le 100$|-|
|$3$|$20$|-|-|$\forall i,\exists k\in \mathbb{N}^* \ \text{s.t.}\ l_i=2^k-1$|
|$4$|$20$|$\le 20000$|$\le 20000$|$l_i,v_i$ are randomly generated in range by `std::mt19937` modulo maximum limit|
|$5$|$25$|-|-|$l_i,v_i$ are randomly generated in range by `std::mt19937` modulo maximum limit|

