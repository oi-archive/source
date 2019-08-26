
# 题目描述

有 $n$ 棵树，初始时每棵树的高度为 $H_i$，第 $i$ 棵树每月都会长高 $A_i$。现在有个木料长度总量为 $S$ 的订单，客户要求每块木料的长度不能小于 $L$，而且木料必须是整棵树（即不能为树的一部分）。现在问你最少需要等多少个月才能满足订单。

# 输入格式

第一行 $3$ 个用空格隔开的非负整数 $n,S,L$，表示树的数量、订单总量和单块木料长度限制。

第二行 $n$ 个用空格隔开的非负整数，依次为 $H_1,H_2,\dots ,H_n$。

第三行 $n$ 个用空格隔开的非负整数，依次为 $A_1,A_2,\dots ,A_n$。

# 输出格式

输出一行一个整数表示答案。

# 样例

#### 样例输入
```plain
3 74 51
2 5 2
2 7 9
```

#### 样例输出
```plain
7
```

#### 样例解释

对于样例，在六个月后，各棵树的高度分别为 $14,47,56$，此时无法完成订单。

在七个月后，各棵树的高度分别为 $16,54,65$，此时可以砍下第 $2$ 和第 $3$ 棵树完成订单了。

# 数据范围与提示

<!-- BEGIN: Migrated markdown table -->

| 测试点编号 | $n$ | 特殊约定 |
|-|-|-|
| 1 | $n = 1$ | $1 \leq S \leq H_i \leq 10000$ |
| 2 | $n = 1$ | $1 \leq S, L, H_i, A_i \leq 10000$ |
| 3 | $1 \leq n \leq 1000$ | $1 \leq S, L, H_i, A_i \leq 10000$ |
| 4 | $1 \leq n \leq 1000$ | $1 \leq S, L, H_i, A_i \leq 10000$ |
| 5 | $1 \leq n \leq 1000$ | $1 \leq S, L, H_i, A_i \leq 10000$ |
| 6 | $1 \leq n \leq 1000$ | $1 \leq S, L, H_i, A_i \leq 10^9$ |
| 7 | $1 \leq n \leq 1000$ | $1 \leq S, L, H_i, A_i \leq 10^9$ |
| 8 | $1 \leq n \leq 1000$ | $1 \leq S, L, H_i, A_i \leq 10^9$ |
| 9 | $1 \leq n \leq 20000$ | $1 \leq S, L, H_i, A_i \leq 10^9$ |
| 10 | $1 \leq n \leq 20000$ | $1 \leq S, L, H_i, A_i \leq 10^9$ |
| 11 | $1 \leq n \leq 20000$ | $1 \leq S, L \leq 10^{18}$，$1 \leq H_i, A_i \leq 10^9$ |
| 12 | $1 \leq n \leq 20000$ | $1 \leq S, L \leq 10^{18}$，$1 \leq H_i, A_i \leq 10^9$ |
| 13 | $1 \leq n \leq 200000$ | $L = 1$ |
| 14 | $1 \leq n \leq 200000$ | $S \leq L$ |
| 15 | $1 \leq n \leq 200000$ | $1 \leq S, L \leq 10^{18}$，$1 \leq H_i, A_i \leq 10^9$ |
| 16 | $1 \leq n \leq 200000$ | $1 \leq S, L \leq 10^{18}$，$1 \leq H_i, A_i \leq 10^9$ |
| 17 | $1 \leq n \leq 200000$ | $1 \leq S, L \leq 10^{18}$，$1 \leq H_i, A_i \leq 10^9$ |
| 18 | $1 \leq n \leq 200000$ | $1 \leq S, L \leq 10^{18}$，$1 \leq H_i, A_i \leq 10^9$ |
| 19 | $1 \leq n \leq 200000$ | $1 \leq S, L \leq 10^{18}$，$1 \leq H_i, A_i \leq 10^9$ |
| 20 | $1 \leq n \leq 200000$ | $1 \leq S, L \leq 10^{18}$，$1 \leq H_i, A_i \leq 10^9$ |

<!-- Migrated from original HTML table:
<table class='ui center aligned celled table'>
<thead>
  <tr>
    <th>测试点编号</th>
    <th>$n$ </th>
    <th>特殊约定</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td rowspan='2'>$n = 1$ </td>
    <td>$1 \leq S \leq H_i \leq 10000$ </td>
  </tr>
  <tr>
    <td>2</td>
    <td rowspan='4'>$1 \leq S, L, H_i, A_i \leq 10000$ </td>
  </tr>
  <tr>
    <td>3</td>
    <td rowspan='6'>$1 \leq n \leq 1000$ </td>
  </tr>
  <tr>
    <td>4</td>
  </tr>
  <tr>
    <td>5</td>
  </tr>
  <tr>
    <td>6</td>
    <td rowspan='5'>$1 \leq S, L, H_i, A_i \leq 10^9$ </td>
  </tr>
  <tr>
    <td>7</td>
  </tr>
  <tr>
    <td>8</td>
  </tr>
  <tr>
    <td>9</td>
    <td rowspan='4'>$1 \leq n \leq 20000$ </td>
  </tr>
  <tr>
    <td>10</td>
  </tr>
  <tr>
    <td>11</td>
    <td rowspan='2'>$1 \leq S, L \leq 10^{18}$，$1 \leq H_i, A_i \leq 10^9$ </td>
  </tr>
  <tr>
    <td>12</td>
  </tr>
  <tr>
    <td>13</td>
    <td rowspan='8'>$1 \leq n \leq 200000$ </td>
    <td>$L = 1$ </td>
  </tr>
  <tr>
    <td>14</td>
    <td>$S \leq L$ </td>
  </tr>
  <tr>
    <td>15</td>
    <td rowspan='6'>$1 \leq S, L \leq 10^{18}$，$1 \leq H_i, A_i \leq 10^9$ </td>
  </tr>
  <tr>
    <td>16</td>
  </tr>
  <tr>
    <td>17</td>
  </tr>
  <tr>
    <td>18</td>
  </tr>
  <tr>
    <td>19</td>
  </tr>
  <tr>
    <td>20</td>
  </tr>
</tbody>
</table>
-->

<!-- END: Migrated markdown table -->

<hr style='color: #ddd; margin-bottom: 1em'>

来自 CodePlus 2017 11 月赛，清华大学计算机科学与技术系学生算法与竞赛协会 荣誉出品。  
Credit：idea/郑林楷　命题/郑林楷　验题/王聿中  
Git Repo：https://git.thusaac.org/publish/CodePlus201711  
感谢腾讯公司对此次比赛的支持。

