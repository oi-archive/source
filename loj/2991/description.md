
# 题目描述

众所周知，香山的红叶非常著名。然而，CTSC 举行的时间是在 5 月，而红叶的季节是秋天，所以这个季节是看不到红叶的，于是我们在 CTSC 比赛中就只能讨论香山的树了。

s-quark 很喜欢这些树，他计划在每棵树上贴上一个各不相同的标签。每个标签为条形，可以在树干上绕成一圈。为了区分每一棵树，s-quark 在每个标签上印了一个由小写英文字母组成的字符串。由于树干周长的限制，标签的长度也是有限的，因此这个字符串至多只能由 $N$ 个字母组成。

但是，由于标签是在树干上围成一圈的，所以当标签在树上贴好以后，就不再能找到标签的起始位置了。所以，如果两棵树上的标签循环同构，例如分别为 `abc` 和 `cab`，那么这两棵树就不再能通过标签区分了。针对这个问题，s-quark 想了一个巧妙的办法。对于一个已经在树上贴好的标签，s-quark 规定它的起始位置必须是能够使得字符串的字典序最小的起始位，即如果看到的字符串是 `aba`，那么就可以推断出从正确的起始位置开始看到的字符串应为 `aab`。

另外，对于有些标签，例如 `abab`，尽管符合字典序最小的规则，但是这样的起始位置不唯一，s-quark 认为这种情况也是不理想的。所以，这样的标签 s-quark 也会避免使用。s-quark 已经把所有的树编好了顺序，准备在第一棵树上贴标签 `a`，之后按照字典序给每棵树贴上不同的标签。

以 $n = 3$ 为例，s-quark 将依次使用这些标签来标记这些树木：`a`，`aab`，`aac`，……，`aaz`，`ab`，`abb`，……，`abz`，`ac`，……

s-quark 知道，香山上的树总共有 $K$ 棵。他想知道他将在最后一棵树上贴的标签是什么。但是，这个问题显然太简单了。现在， s-quark 要问你，如果他在第一棵树上贴的标签是字符串 $S$，那么他将在最后一棵树上贴的标签是什么呢？

# 输入格式

输入文件为 `treelabel.in`。

输入的第一行两个正整数 $N$ 和 $K$，分别为字符串的长度和树的总数。

第二行一个由小写英文字母组成的字符串 $S$，表示在第一棵树上所贴的标签。$S$ 的长度不超过 $N$，并且保证是一个合法的标签。

# 输出格式

输出文件为 `treelabel.out`。

输出仅一行，输出一个字符串 $T$，表示 s-quark 将在最后一棵树上贴的标签，或输出 $−1$，表示剩余的合法标签数量不足以贴完所有的树。

# 样例

#### 样例输入 1
```plain
3 10
a
```
#### 样例输出 1
```plain
aaj
```
#### 样例输入 2
```plain
3 10
xy
```
#### 样例输出 2
```plain
yzz
```
#### 样例输入 3
```plain
1 100
a
```
#### 样例输出 3
```plain
-1
```
#### 样例输入 4
```plain
25 1000000000000000
u
```
#### 样例输出 4
```plain
uuuuuvxzuxvwwyzzuyzvxuvxw
```

# 数据范围与提示

<!-- BEGIN: Migrated markdown table -->

| 测试点 | $N$ | $K$ | 数据特点 |
|:-:|:-:|:-:|:-:|
| $1$ | $=8$ | $\le 10^4$ | $S$ 为字符串 `a` |
| $2,3$ | $=9$ | $\le 10^6$ | 无 |
| $4$ | $=8$ | $\le 10^{15}$ | 无 |
| $5$ | $=9$ | $\le 10^{15}$ | 无 |
| $6$ | $=10$ | $\le 10^{15}$ | 无 |
| $7,8$ | $\le 30$ | $\le 10^{15}$ | 无 |
| $9,10$ | $\le 50$ | $\le 10^{15}$ | 无 |

<!-- Migrated from original HTML table:
<table><thead>
  <tr>
    <th style='text-align: center'>测试点</th>
    <th style='text-align: center'> $N$ </th>
    <th style='text-align: center'> $K$ </th>
    <th style='text-align: center'>数据特点</th>
  </tr></thead><tbody>
  <tr>
    <td style='text-align: center'> $1$ </td>
    <td style='text-align: center'> $=8$ </td>
    <td style='text-align: center'> $\le 10^4$ </td>
    <td style='text-align: center'> $S$ 为字符串 `a` </td>
  </tr>
  <tr>
    <td style='text-align: center'> $2,3$ </td>
    <td style='text-align: center'> $=9$ </td>
    <td style='text-align: center'> $\le 10^6$ </td>
    <td rowspan="6" style='text-align: center'>无</td>
  </tr>
  <tr>
    <td style='text-align: center'> $4$ </td>
    <td style='text-align: center'> $=8$ </td>
    <td rowspan="5" style='text-align: center'> $\le 10^{15}$ </td>
  </tr>
  <tr>
    <td style='text-align: center'> $5$ </td>
    <td style='text-align: center'> $=9$ </td>
  </tr>
  <tr>
    <td style='text-align: center'> $6$ </td>
    <td style='text-align: center'> $=10$ </td>
  </tr>
  <tr>
    <td style='text-align: center'> $7,8$ </td>
    <td style='text-align: center'> $\le 30$ </td>
  </tr>
  <tr>
    <td style='text-align: center'> $9,10$ </td>
    <td style='text-align: center'> $\le 50$ </td>
  </tr></tbody>
</table>
-->

<!-- END: Migrated markdown table -->

