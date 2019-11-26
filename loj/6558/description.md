
# 题目描述

**译自 [CERC 2018](https://contest.felk.cvut.cz/18cerc/)「[L. Game of Stones](https://contest.felk.cvut.cz/18cerc/solved/stones.pdf)」**

Petyr 和 Varys 两个人在玩游戏。游戏中选手从 $N$ 堆石子中轮流取走一些石子。在自己的回合中，Petyr 可以从任意一堆中取走最多 $A$ 个石子，Varys 可以从任意一堆中取走最多 $B$ 个石子。每一轮选手至少要取走一个石子。取走最后一个石子的一方获胜。

游戏已经开始，并且现在 Petyr 要取石子。你的任务是判断在双方均采用最优策略的情况下 Petyr 是否能赢。

# 输入格式

输入的第一行包含三个整数 $N,A,B$，表示有 $N$ 堆石子和两人的限制。

第二行 $N$ 个数 $X_1,X_2,\ldots ,X_N$，表示当前所有堆中石子个数。

# 输出格式

输出获胜者的名字。

# 样例

#### 样例输入 1
```plain
2 3 4
2 3
```
#### 样例输出 1
```plain
Petyr
```
#### 样例输入 2
```plain
7 8 9
1 2 3 4 5 6 7
```
#### 样例输出 2
```plain
Varys
```

# 数据范围与提示

$1\le N,A,B\le 10^5,1\le X_i\le 10^6$

