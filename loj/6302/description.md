
# 题目描述

access_globe 有一个巨大的停车场，这个停车场有 $n$ 行，每行有 $m$ 个车位。为了美观，access_globe 在建立这个停车场时，规定这个停车场必须是长条形的，即 $n\ge m$。每个车位都是一个正方形的区域。

最近，access_globe 正在为抽不到 Missing Poster 而苦恼，因此他请你帮他维护这个停车场。你需要支持两个个事件：

- 一辆车停到某一个车位中，或一辆车从某个车位开走
- 查询一个矩形区域内最大的只包含空车位的正方形区域

如果你能帮 access_globe 高效地解决这个问题，access_globe 一定会好好奖励你的。



# 输入格式

从标准输入读入数据。

第一行包含三个正整数 $n$、$m$、$q$，表示停车场的大小和事件的个数；

接下来 $n$ 行，每行 $m$ 个 0 或 1 的数，如果第 $i$ 行第 $j$ 的数**为 $1$**，则表示第 $i$ 行第 $j$ 列的车位**为空**，否则表示这个车位**非空**；

接下来 $q$ 行，每行表示一个事件，有以下两种形式：

- $0$ $x$ $y$ ：第 $x$ 行第 $y$ 列的车位的停车情况改变，即若此事件发生前这个车位为空，则此事件后这个车位非空，否则此事件后这个车位为空，保证 $1\le x\le n$，$1\le y\le m$
- $1$ $l$ $s$ $r$ $t$：询问以 $(l, s)$ 和 $(r,t)$ 为对角的矩形区域中，最大的全空正方形区域的边长，保证 $1\le l\le r\le n$，$1\le s\le t\le m$


# 输出格式

输出到标准输出。

对每个询问输出一行一个整数，表示该询问的全空正方形的边长。






# 样例

#### 样例 1 输入

```plain
5 4 10
1 1 1 0
1 1 1 1
1 1 0 1
1 0 1 0
1 1 0 0
1 1 1 5 4
1 3 1 3 1
1 3 3 3 3
1 2 3 5 3
0 2 2
1 1 4 2 4
1 1 3 3 3
0 5 1
1 2 3 2 4
1 1 2 2 4

```

#### 样例 1 输出

```plain
2
1
0
1
1
1
1
1

```

# 数据范围与提示

<!-- BEGIN: Migrated markdown table -->

| 子任务编号 | $n,m$ 的额外限制 | $q$ 的额外限制 | 修改操作 | 是否保证 $s=1,t=m$ |
|-|-|-|-|-|
| 1 | $n,m\le 500$ | $q\le 500$ | 存在 | 否 |
| 2 | $m\le 10$ | 无 | 保证不存在 | 是 |
| 3 | $m\le 10$ | 无 | 存在 | 是 |
| 4 | $n\le 40000$ | 无 | 保证不存在 | 是 |
| 5 | $n\le 40000$ | 无 | 存在 | 是 |
| 6 | $m\le 10$ | 无 | 保证不存在 | 否 |
| 7 | $m\le 10$ | 无 | 存在 | 否 |
| 8 | $n\le 40000$ | 无 | 保证不存在 | 否 |
| 9 | $n\le 40000$ | 无 | 存在 | 否 |
| 10 | 无 | 无 | 存在 | 否 |

<!-- Migrated from original HTML table:
<table class="ui celled table">
<thead><tr><th rowspan="1">子任务编号</th><th rowspan="1">$n,m$ 的额外限制</th><th rowspan="1">$q$ 的额外限制</th><th rowspan="1">修改操作</th><th rowspan="1">是否保证 $s=1,t=m$ </th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">$n,m\le 500$ </td><td rowspan="1">$q\le 500$ </td><td rowspan="1">存在</td><td rowspan="1">否</td></tr><tr><td rowspan="1">2</td><td rowspan="2">$m\le 10$ </td><td rowspan="9">无</td><td rowspan="1">保证不存在</td><td rowspan="4">是</td></tr><tr><td rowspan="1">3</td><td rowspan="1">存在</td></tr><tr><td rowspan="1">4</td><td rowspan="2">$n\le 40000$ </td><td rowspan="1">保证不存在</td></tr><tr><td rowspan="1">5</td><td rowspan="1">存在</td></tr><tr><td rowspan="1">6</td><td rowspan="2">$m\le 10$ </td><td rowspan="1">保证不存在</td><td rowspan="5">否</td></tr><tr><td rowspan="1">7</td><td rowspan="1">存在</td></tr><tr><td rowspan="1">8</td><td rowspan="2">$n\le 40000$ </td><td rowspan="1">保证不存在</td></tr><tr><td rowspan="1">9</td><td rowspan="2">存在</td></tr><tr><td rowspan="1">10</td><td rowspan="1">无</td></tr></tbody></table>
-->

<!-- END: Migrated markdown table --> 

所有子任务的分值均等分布。

对于所有数据，保证 $n\times m\le 4 \times 10^{6}$，$q\le 2,000$。

<hr style='color: #ddd; margin-bottom: 1em'>

来自 CodePlus 2018 3 月赛，清华大学计算机科学与技术系学生算法与竞赛协会 荣誉出品。  
Credit：idea/陈俊锟　命题/陈俊锟　验题/吕欣  
Git Repo：https://git.thusaac.org/publish/CodePlus3  
感谢腾讯公司对此次比赛的支持。

