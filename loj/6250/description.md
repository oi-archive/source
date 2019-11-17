
# 题目描述

小 A 最近一直在找自己的爸爸，用什么办法呢，就是 DNA 比对。

小 A 有一套自己的 DNA 序列比较方法，其最终目标是最大化两个 DNA 序列的相似程度，具体步骤如下：

1. 给出两个 DNA 序列，第一个长度为 $n$，第二个长度为 $m$。
2. 在两个序列的任意位置插入任意多的空格，使得两个字符串长度相同。
3. 逐位进行匹配，**如果两个序列相同位置上的字符都不是空格**，假设第一个是 $x$，第二个是 $y$，那么他们的相似程度由 $d(x,y)$ 定义。对于两个序列中任意一段极长连续空格，设其长度为 $k$，我们定义这段空格的相似程度为 $g(k)=-A-B\times (k-1)$，其中 $A,B$ 均为正整数。

那么最终两个序列的相似程度就是所有的 $d(x,y)$ 加上所有的极长空格段的相似程度之和。

现在小 A 通过某种奥妙重重的方式得到了小 B 的 DNA 序列中的一段，他想请你帮他算一下小 A 的 DNA 序列和小 B 的 DNA 序列的最大相似程度。

# 输入格式

输入第 $1$ 行一个字符串，表示小 A 的 DNA 序列。

输入第 $2$ 行一个字符串，表示小 B 的 DNA 序列。

接下来 $4$ 行，每行 $4$ 个整数，用空格隔开，表示 $d$ 数组，具体顺序如下所示。

> $d(A,A)$　$d(A,T)$　$d(A,G)$　$d(A,C)$  
> $d(T,A)$　$d(T,T)$　$d(T,G)$　$d(T,C)$  
> $d(G,A)$　$d(G,T)$　$d(G,G)$　$d(G,C)$  
> $d(C,A)$　$d(C,T)$　$d(C,G)$　$d(C,C)$

最后一行两个用空格隔开的正整数 $A,B$，意义如题中所述。

# 输出格式

输出共一行，表示两个序列的最大相似程度。

# 样例

#### 样例输入
```plain
ATGG
ATCC
5 -4 -4 -4
-4 5 -4 -4
-4 -4 5 -4
-4 -4 -4 5
2 1
```

#### 样例输出
```plain
4
```

#### 样例解释

首先，将序列补成如下形式（`-` 代表空格）

```plain
ATGG--
AT--CC
```

然后所有 $d(x,y)$ 的和为 $d(A,A)+d(T,T)=10$，所有极长连续空格段的相似程度之和为 $g(2)+g(2)=-6$。总和为 $4$，可以验证，这是相似程度最大的情况。

# 数据范围与提示

对于所有测试点，有 $0< B<A \le 1000, -1000\le d(x,y)\le 1000,d(x,y)=d(y,x)$，序列只包含 $\{\text{A},\text{T},\text{G},\text{C}\}$ 四种字符。

<!-- BEGIN: Migrated markdown table -->

| 测试点编号 | $n + m$ 的范围 | 特殊约定 |
|-|-|-|
| 1 | $n = m = 1$ | 无特殊要求 |
| 2 | $n + m \leq 15$ | 无特殊要求 |
| 3 | $n + m \leq 300$ | 无特殊要求 |
| 4 | $n + m \leq 300$ | 无特殊要求 |
| 5 | $n + m \leq 3000$ | 序列中只包含一种字符 |
| 6 | $n + m \leq 3000$ | 无特殊要求 |
| 7 | $n + m \leq 3000$ | 无特殊要求 |
| 8 | $n + m \leq 3000$ | 无特殊要求 |
| 9 | $n + m \leq 3000$ | 无特殊要求 |
| 10 | $n + m \leq 3000$ | 无特殊要求 |

<!-- Migrated from original HTML table:
<table class='ui center aligned celled table'>
<thead>
  <tr>
    <th>测试点编号</th>
    <th>$n + m$ 的范围</th>
    <th>特殊约定</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td>$n = m = 1$ </td>
    <td rowspan='4'>无特殊要求</td>
  </tr>
  <tr>
    <td>2</td>
    <td>$n + m \leq 15$ </td>
  </tr>
  <tr>
    <td>3</td>
    <td rowspan='2'>$n + m \leq 300$ </td>
  </tr>
  <tr>
    <td>4</td>
  </tr>
  <tr>
    <td>5</td>
    <td rowspan='6'>$n + m \leq 3000$ </td>
    <td>序列中只包含一种字符</td>
  </tr>
  <tr>
    <td>6</td>
    <td rowspan='5'>无特殊要求</td>
  </tr>
  <tr>
    <td>7</td>
  </tr>
  <tr>
    <td>8</td>
  </tr>
  <tr>
    <td>9</td>
  </tr>
  <tr>
    <td>10</td>
  </tr>
</tbody>
</table>
-->

<!-- END: Migrated markdown table -->

<hr style='color: #ddd; margin-bottom: 1em'>

来自 CodePlus 2017 11 月赛，清华大学计算机科学与技术系学生算法与竞赛协会 荣誉出品。  
Credit：idea/邢健开　命题/邢健开　验题/陈宇  
Git Repo：https://git.thusaac.org/publish/CodePlus201711  
感谢腾讯公司对此次比赛的支持。

