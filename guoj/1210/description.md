
# 题目描述

**这是一道交互题。**

Nauuo 是一个喜欢二叉树的女孩子。

这天，她创造了一个有 $n$ 个节点的二叉树。节点的编号从 $1$ 到 $n$，其中 $1$ 是二叉树的根节点。

不过，她不记得这棵二叉树具体长什么样子了，她只记录了二叉树上任意两个节点之间的距离。你可以通过向她询问有关距离的信息来还原这棵二叉树，两个节点之间的距离定义为它们之间最短路上的边数。

你可以向 Nauuo 询问不超过 $30000$ 次有关距离的信息。你只需要告诉她 $2\sim n$ 号节点的父亲的编号就可以了。

#### 交互方式

最开始，交互器会向标准输入中输入一个正整数 $n$。

接下来，你可以通过标准输出向交互器询问两个节点之间的距离。

对于一次询问，你需要输出一行 `? u v` 表示你想让 Nauuo 告诉你节点 $u$ 和节点 $v$ 在这棵二叉树上距离，然后换行并刷新缓存。

在每次询问后，交互器会向标准输入中输入一个非负整数 $d$，表示节点 $u$ 和节点 $v$ 之间的距离。

当你的所有询问结束后，你需要输出一行 `! p`，$p$ 是一个长为 $n-1$ 的正整数序列，第 $i$ 个数表示第 $i+1$ 个节点在这棵二叉树上的父亲，然后**换行**并刷新缓存。

当你的程序正确时，保证交互器使用的时间不会超过 $500\ \text{ms}$。

如果你的询问次数超过 $30000$ 次，那么评测机将会返回 <span class="status wrong_answer"><i class="remove icon"></i><b>Wrong Answer</b></span> 或 <span class="status time_limit_exceeded"> <i class="icon clock"> </i><b>Time Limit Exceeded</b></span>，你的程序将会获得 $0$ 分。

如果你的程序没有及时刷新缓存，那么评测机将会返回 <span class="status time_limit_exceeded"> <i class="icon clock"> </i><b>Time Limit Exceeded</b></span>，你的程序将会获得 $0$ 分。

如果你的程序使用 `C++`，可以使用 `fflush(stdout)` 或 `cout.flush()` 或 `cout << endl` 来刷新缓存；

如果你的程序使用 `Java`，可以使用 `System.out.flush()` 来刷新缓存；

如果你的程序使用 `Pascal`，可以使用 `flush(output)` 来刷新缓存；

如果你的程序使用 `Python`，可以使用 `stdout.flush()` 来刷新缓存。

# 输入格式



# 输出格式



# 样例

#### 样例 1 输入
```plain
4
1
2
3
```

#### 样例 1 输出
```plain
? 1 2
? 1 3
? 3 4
! 1 2 1
```

#### 样例 1 解释

样例 1 的二叉树形态如下。

![](/source/guoj/1210/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMDYvMTcvNWQwNzk4ZTQ5OTQwNDk0Njc1LnBuZw==.png)

在第一次询问中，$1$ 号节点和 $2$ 号节点之间的距离是 $1$（$1\to 2$）。

在第二次询问中，$1$ 号节点和 $3$ 号节点之间的距离是 $2$（$1\to 2\to 3$）。

在第三次询问中，$3$ 号节点和 $4$ 号节点之间的距离是 $3$（$3\to 2\to 1\to 4$）。

#### 样例 2 输入

```plain
5
4
1
```

#### 样例 2 输出

```plain
? 4 3
? 2 4
! 1 5 2 1
```
#### 样例 2 解释

样例 2 的二叉树形态如下。

![](/source/guoj/1210/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMDYvMTcvNWQwNzk4ZTcwMDBmYTk0OTk0LnBuZw==.png)


# 数据范围与提示

对于全部的数据，$2\le n\le 3000$。

你输出的 $u,v$ 应该满足 $1\le u,v\le n$，$p_i$ 应该满足 $1\le p_i\le n$，否则评测机会返回 <span class="status judgement_failed"><i class="server icon"></i> <b>Judgement Failed</b></span>。

保证交互器输出的 $d$ 满足 $0\le d\le n-1$。

[为什么要开 6s ？](https://guoj.icu/submission/1046)

---

**以下是英文原题面。**[跳过英文题面至提交页面](#submit_code)

除了把 TeX 翻译成 Markdown，题面没有作任何改动。

**This is an interactive problem.**

Nauuo is a girl who loves binary trees.

One day, she created a binary tree consisting of $n$ nodes. The nodes are numbered from $1$ to $n$. The root of the tree is the node $1$.

However, Nauuo can't remember the tree exactly. She only remembers the distance between every two nodes, you can make some queries on the distance to find the whole binary tree.

The distance between two nodes is the number of edges of the shortest path between the two nodes.

You are allowed to make no more than $30000$ queries, and you only have to tell Nauuo the parent of each node except the root.

#### Interaction

The interaction starts with a line containing one integer $n$ ($2\le n\le 3000$) --- the number of nodes.

After that, you can make queries.

To make a query, print a line "$\texttt{? u v}$" ($1\le u,v\le n$), then $\texttt{flush}$ the output.

After each query, read a single integer $d$ ($0\le d\le n-1$) --- the distance between $u$ and $v$.

When you find the whole binary tree, print a line "$\texttt{! p}$", $\texttt{flush}$ the output and terminate. $p$ is an array containing $n-1$ integers, where the $i$-th element of $p$ is the parent of node $i+1$.

The interactor will cost **no more than** $500ms$ if you make no more than $30000$ queries.

Your solution will get $\texttt{Wrong Answer}$ or $\texttt{Time Limit Exceeded}$ if you make more than $30000$ queries.

Your solution will get $\texttt{Idleness Limit Exceeded}$ if you don't print anything or forget to flush the output.

To $\texttt{flush}$ you need to do the following right after printing a query and a line end:

- $\texttt{fflush(stdout)}$ or $\texttt{cout.flush()}$ in C++;
- $\texttt{System.out.flush()}$ in Java;
- $\texttt{flush(output)}$ in Pascal;
- $\texttt{stdout.flush()}$ in Python;
- see documentation for other languages.

#### Hacks

The first line contains a single integer $n$ ($2\le n\le 3000$) --- the number of nodes.

The second line contains an array $p$ containing $n-1$ integers, where the $i$-th element of $p$ is the parent of node $i+1$.

For hacks, you have to guarantee that the given parents can form a tree.

#### Examples

##### Input
```plain
4
1
2
3
```

#### Output
```plain
? 1 2
? 1 3
? 3 4
! 1 2 1
```

The binary tree is as follows.

![](/source/guoj/1210/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMDYvMTcvNWQwNzk4ZTQ5OTQwNDk0Njc1LnBuZw==.png)

In the first query, the distance between $1$ and $2$ is $1$ ($1\rightarrow2$).

In the second query, the distance between $1$ and $3$ is $2$ ($1\rightarrow2\rightarrow3$).

In the third query, the distance between $3$ and $4$ is $3$ ($3\rightarrow2\rightarrow1\rightarrow4$).

---

##### Input

```plain
5
4
1
```

##### Output

```plain
? 4 3
? 2 4
! 1 5 2 1
```

The binary tree is as follows.

![](/source/guoj/1210/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMDYvMTcvNWQwNzk4ZTcwMDBmYTk0OTk0LnBuZw==.png)


