
# 题目描述

给出 $n$ 行 $m$ 列的网格，你可以选择任意两个网格配对，每个网格最多只能与一个网格配对，也可以不与任何网格配对。定义关于两个网格 $A, B$ 的权值函数 $f(A, B)$：
$$\begin{aligned} dx &= \left|x_A - x_B\right| \\ dy &= \left|y_A - y_B\right| \\ f(A, B) &= \begin{cases} dx + dy & , dx + dy \geq k \\ 0 & , dx + dy < k \end{cases} \end{aligned}$$

一个配对方案的权值为其所有网格配对的权值之和 $\sum f$。求给出网格中，所有配对方案中权值的最大值。

<div class="lang-divider"></div>

Given a grid with $n$ rows and $m$ columns, in this grid, you can choose two different grid points and match them into a pair. Notice that a point can only be matched with no more than one point. It means unmatched points are allowed. We define a weight function $f(A, B)$ for a pair of points $A, B$ as the following form:  
$$\begin{aligned} dx &= \left|x_A - x_B\right| \\ dy &= \left|y_A - y_B\right| \\ f(A, B) &= \begin{cases} dx + dy & , dx + dy \geq k \\ 0 & , dx + dy < k \end{cases} \end{aligned}$$

The weight of a possible matching scheme is defined as the sum of weights that the matching pairs given. Your task is to calculate the maximum possible weight of all matching schemes. 

# 输入格式

从标准输入中读取数据。

第一行，一个整数 $T$，表示数据组数。

接下来 $T$ 行，每行三个整数 $n, m, k$，表示网格的行数、列数以及权值函数中的常数 $k$。

<div class="lang-divider"></div>

Read from the standard input. 

The first line contains a single integer $T$ which means the number of the test cases. 

Each of the following $T$ lines contains three integers $n, m, k$ which means the height and the width of the grid, and the constant $k$ in the weight function. 

# 输出格式

输出到标准输出中。

输出共 $T$ 行，对于每一组数据，输出一行一个整数，表示所有配对方案的配对权值和的最大值。

<div class="lang-divider"></div>

Write to the standard output. 

For each test case, output a line containing a single integer — the maximum of the weight of possible matching plans. 

# 样例

#### 样例输入 1

```plain
4
1 1 0
1 2 0
2 2 1
2 3 1
```

#### 样例输出 1

```plain
0
1
4
7
```

#### 样例解释 1

对于 $1 \times 1$ 的网格，不存在匹配方案，答案为 $0$。

对于 $1 \times 2$ 的网格，匹配方案唯一，答案为 $1$。

对于 $2 \times 2$ 的网格，左上格与右下格匹配，右上格与左下格匹配，答案为 $4$。如下图所示。

![样例说明 1](https://loj.ac/problem/1/testdata/download/Explanation3.png)

对于 $2 \times 3$ 的网格，左上格与中下格匹配，中上格与右下格匹配，右上格与左下格匹配，答案为 $7$。如下图所示。

![样例说明 1](https://loj.ac/problem/1/testdata/download/Explanation4.png)

#### 样例输入 2

```plain
6
23 66 12
233 666 123
2333 6666 1234
23333 6666 1234
2333 66666 1234
23333 66666 12345
```

#### 样例输出 2

```plain
33759
34876089
34987610889
1166494448889
2682884270889
34998761108889
```

<div class="lang-divider"></div>

#### Sample Input 1

```plain
4
1 1 0
1 2 0
2 2 1
2 3 1
```

#### Sample Output 1

```plain
0
1
4
7
```

#### Sample Explanation 1

As for $1 \times 1$ grid, there is no point for the only one to match, so the answer is $0$. 

As for $1 \times 2$ grid, we match the only two points into a pair, so the answer is $1$. 

As for $2 \times 2$ grid, we match the top left point and the bottom right one into a pair, the top right point and the bottom left one into a pair. The answer is $4$, as shown by the following picture. 

![Sample Explanation 1](https://loj.ac/problem/1/testdata/download/Explanation3.png)

As for $2 \times 3$ grid, we match the top left point and the bottom middle one, the top middle point and the bottom right one, the top right point and the bottom left one. The answer is $7$, as shown by the following picture. 

![Sample Explanation 1](https://loj.ac/problem/1/testdata/download/Explanation4.png)

#### Sample Input 2

```plain
6
23 66 12
233 666 123
2333 6666 1234
23333 6666 1234
2333 66666 1234
23333 66666 12345
```

#### Sample Output 2

```plain
33759
34876089
34987610889
1166494448889
2682884270889
34998761108889
```

# 数据范围与提示

对于所有数据，$1 \leq T \leq 10^5$，$1 \leq n,m \leq 10^6$，$0 \leq k \leq \min(n, m) - 1$。

详细的数据限制及约定如下（留空表示和上述所有数据的约定相同）：  

|	子任务编号	|分值(百分比)	|$T$			|	$n, m$				|	特殊限制									|
|:----------------------:|:----------------:|:-----------------------:|:-----------------------------------:|:-------------------------------------------------------------------:|
|	$1$			|	$10$		|	$\leq 20$		|	$\leq 2000$			|	$n \leq 2$								|
|	$2$			|	$15$		|	$\leq 5$		|	$\leq 8$				|	$n \times m \leq 10$ 且 $k = \min(n, m) - 1$	|
|	$3$			|	$25$		|	$\leq 3$		|	$\leq 16$				|	无										|
|	$4$			|	$18$		|	$\leq 100$	|	$\leq 5000$			|	$n = m$ 且 $n \equiv 0 \pmod 2$				|
|	$5$			|	$32$		|	$\leq 10^5$	|	$\leq 10^6$			|	无										|

<div class="lang-divider"></div>

For all test cases, $1 \leq T \leq 10^5$，$1 \leq n,m \leq 10^6$，$0 \leq k \leq \min(n, m) - 1$.

Detailed constraints and hints are as follows (blank grids denote the same constraints as mentioned above):    

|	Subtask#	|	Score (percentage)	|$T$			|	$n, m$				|	Special Constraints |
|:----------------------:|:----------------:|:-----------------------:|:-----------------------------------:|:-------------------------------------------------------------------:|
|	$1$			|	$10$		|	$\leq 20$		|	$\leq 2000$			|	$n \leq 2$								|
|	$2$			|	$15$		|	$\leq 5$		|	$\leq 8$				|	$n \times m \leq 10$ and $k = \min(n, m) - 1$	|
|	$3$			|	$25$		|	$\leq 3$		|	$\leq 16$				|	-									|
|	$4$			|	$18$		|	$\leq 100$	|	$\leq 5000$			|	$n = m$ and $n \equiv 0 \pmod 2$			|
|	$5$			|	$32$		|	$\leq 10^5$	|	$\leq 10^6$			|	-									|

