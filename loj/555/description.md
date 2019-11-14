
# 题目描述

Moejy0viiiiiv 在平面直角坐标系上抢红包。从 $(0,0)$ 出发，每天中午有 $A/1996488707$ 的概率向上走一格，有 $B/1996488707$ 的概率向右走一格，有 $1-A/1996488707-B/1996488707$ 的概率立即停止行动（之后也不再行动），三种事件两两不会同时发生；Moejy0viiiiiv 在第 $N$ 天傍晚离开平面直角坐标系（总共至多走 $N$ 格）。

已知一个常数 $D$，在所有 $(xD, yD)(0 \leq x, y)$ 处有一个红包；还有 $K$ 个坑，分别在 $(x_1, y_1), (x_2, y_2), (x_3, y_3), \cdots, (x_K, y_K)$，走入坑中将在接下来的回合中无法行动。

Moejy0viiiiiv 会抢走所有她经过的红包（包含 $(0,0)$）问最终期望抢到的红包数量，输出这个值 $\bmod 998244353$，注意 $1996488707 \bmod 998244353 = 1$。

<div class="lang-divider"></div>

Moejy0viiiiiv is collecting red envelopes on a rectangular plane. She starts at $(0,0)$. Every day at noon, she walks from $(x, y)$ to $(x,y+1)$ with probability $A/1996488707$, and to $(x+1,y)$ with probability $B/1996488707$, and stops immediately with probability $1-A/1996488707-B/1996488707$ (once she stops, she will never move again). Besides, she also stops after walking for $N$ days. 

With a given constant integer $D$, there’s a red envelope at each $(xD, yD)(0 \leq x, y)$. There’re also $K$ barriers at $(x_1, y_1), (x_2, y_2), (x_3, y_3), ..., (x_K, y_K)$ (barriers never coincide with red envelopes). If she walks to a barrier, she will stop immediately. 

Moejy0viiiiiv will collect each red envelope she passes by (including $(0,0)$). What’s the expected number of red envelopes Moejy0viiiiiv collects after $N$ days? Output the answer $\bmod 998244353$. Notice that $1996488707 \bmod 998244353 = 1$. 

# 输入格式

第一行两个整数 $A, B$。

第二行四个整数 $N, D, M, K$。

接下来 $K$ 行，每行两个整数，第 $i + 2$ 行两个数为 $x_i, y_i$。

<div class="lang-divider"></div>

The first line contains two positive integers $A,B$. 

The second line contains four positive integers $N,D,M,K$. 

The following $K$ lines each contains two integers, the $i+2$-th line contains $x_i,y_i$. 

# 输出格式

一行一个数，表示期望抢的红包数量。

<div class="lang-divider"></div>

Output contains one integer, the expected number of red envelopes $\bmod 998244353$. 

# 样例

#### 样例输入1
```plain
1 1
2 2 5 1
1 0
```

#### 样例输出 1
```plain
2
```
#### 样例解释 1
共有 $3 $个地方有红包，$(0, 0), (0, 2), (2, 0)$。
由于 $(1, 0)$ 处是坑，所以无法抢 $(2, 0)$ 处的红包，而抢到其余两处红包的概率均为 $1$。

注意，在本题中 $A+B$ 不必为 $1$。


#### 样例输入 2
```plain
1 2
2 2 5 0
```

#### 样例输出 2
```plain
6
```

<div class="lang-divider"></div>

#### Sample Input 1
```plain
1 1
2 2 5 1
1 0
```

#### Sample Output 1
```plain
2
```
#### Sample Explanation 1
There’re three red envelopes satisfies $x+y\le N$, $(0, 0), (0, 2), (2, 0)$. 
As there’s a barrier at $(1, 0)$, the red envelope at $(2, 0)$ is unreachable. The probability of getting the other two red envelopes are both $1$. 

$A+B$ doesn’t need to be $1$. 

#### Sample Input 2
```plain
1 2
2 2 5 0
```

#### Sample Output 2
```plain
6
```

# 数据范围与提示

对于所有数据，$1 \leq N \leq 10^{18}, 0 \leq K \leq 50, 1 \leq D, M \leq 1000, 0 \leq x_1, x_2, ..., x_K \leq M$，
$\forall i \in \{1, 2, 3, ..., K\}, D \nmid x_i \vee D \nmid y_i, x_i + y_i \leq N, 0 \leq A, B < 998244353$。

详细的数据限制及约定如下（留空表示和上述所有数据的约定相同）：

|Subtask #|分值（百分比）|$N$|$D$|$M$|$K$|
|:-:|:-:|:-:|:-:|:-:|:-:|
|$1$|$9$|$\le 10^4$|-|-|-|
|$2$|$12$|$\le 10^5$|$\le 10$|$\le 10$|$0$|
|$3$|$27$|-|-|-|$0$|
|$4$|$8$|$\le 10^5$|$\le  10$|$\le 10$|-|
|$5$|$44$|-|-|-|-|

<div class="lang-divider"></div>

For all test cases, $1 \leq N \leq 10^{18}, 0 \leq K \leq 50, 1 \leq D, M \leq 1000, 0 \leq x_1, x_2, ..., x_K \leq M$, 
$\forall i \in \{1, 2, 3, ..., K\}, D \nmid x_i \vee D \nmid y_i, x_i + y_i \leq N, 0 \leq A, B < 998244353$. 

Detailed constraints and hints are as follows (blank grids denote the same constraints as mentioned above):

|Subtask #|Score (percentage)|$N$|$D$|$M$|$K$|
|:-:|:-:|:-:|:-:|:-:|:-:|
|$1$|$9$|$\le 10^4$|-|-|-|
|$2$|$12$|$\le 10^5$|$\le 10$|$\le 10$|$0$|
|$3$|$27$|-|-|-|$0$|
|$4$|$8$|$\le 10^5$|$\le  10$|$\le 10$|-|
|$5$|$44$|-|-|-|-|

