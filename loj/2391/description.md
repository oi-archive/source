
# 题目描述

**题目译自 [JOISC 2017](https://www.ioi-jp.org/camp/2017/2017-sp-tasks/index.html) Day1 T2「[港湾設備](https://www.ioi-jp.org/camp/2017/2017-sp-tasks/2017-sp-d1.pdf) / [Port Facility](https://www.ioi-jp.org/camp/2017/2017-sp-tasks/2017-sp-d1-en.pdf)」**

JOI 港口虽然很小，却非常繁忙。  
JOI 港口放置集装箱的结构可视为两个本质不同的栈。每天从船上卸下的集装箱会被压入某个栈，而被运出港口的集装箱则从栈顶弹出。  
今天 JOI 港口会迎来 $N$ 个集装箱，它们在今天内会被运出港口。今天出入口有 $2N$ 条记录，每条记录都表示一个集装箱到港或离港。  
第 $i$ 个集装箱 $(1\le i\le N)$ 的到港记录为 $A_i$，离港记录为 $B_i$。  
我们把 $N$ 个集装箱分别放在哪个栈称为一个方案。求放置集装箱的方案数 $\bmod (10^9+7)$。

# 输入格式

第一行有一个整数 $N$。
在接下来的 $N$ 行中，第 $i$ 行 $(1\le i\le N)$ 有两个整数 $A_i, B_i$，用空格分隔。


# 输出格式

一个整数，表示放置集装箱的方案数 $\bmod (10^9+7)$。

# 样例

#### 样例输入 1
```plain
4
1 3
2 5
4 8
6 7
```

#### 样例输出 1
```plain
4
```

#### 样例说明 1
为了方便叙述，将这两个栈分别称为 A 和 B 。  
四种方案分别为：ABAA（第 $1$ 个集装箱放在 A，第 $2$ 个集装箱放在 B，以此类推），ABAB，BABA，BABB。

#### 样例输入 2
```plain
3
1 4
2 5
3 6
```

#### 样例输出 2
```plain
0
```

#### 样例输入 3
```plain
5
1 4
2 10
6 9
7 8
3 5
```

#### 样例输出 3
```plain
8
```

#### 样例输入 4
```plain
8
1 15
2 5
3 8
4 6
14 16
7 9
10 13
11 12
```

#### 样例输出 4
```plain
16
```

# 数据范围与提示

对于所有数据，$1\le N\le 10^6, 1\le A_i, B_i\le 2N(1\le i\le N), A_1\ldots A_N$ 和 $B_1\ldots B_N$ 这 $2N$ 个整数互不相同。

<table class="ui celled table">
<thead>
<tr>
  <th>Subtask \# </th>
  <th>1</th>
  <th>2</th>
  <th>3</th>
  <th>4</th>
</tr>
</thead>
<tbody>
<tr>
  <td>$N\le$ </td>
  <td>$20$ </td>
  <td>$2000$ </td>
  <td>$2\times 10^5$ </td>
  <td>$10^6$ </td>
</tr>
<tr>
  <td>分值</td>
  <td>10</td>
  <td>12</td>
  <td>56</td>
  <td>22</td>
</tr>
</tbody>
<table>

