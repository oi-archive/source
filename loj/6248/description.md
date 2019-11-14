
# 题目描述

「无体育，不清华」、「每天锻炼一小时，健康工作五十年，幸福生活一辈子」

在清华，体育运动绝对是同学们生活中不可或缺的一部分。为了响应学校的号召，模范好学生王队长决定坚持晨跑。不过由于种种原因，每天都早起去跑步不太现实，所以王队长决定每 $a$ 天晨跑一次。换句话说，假如王队长某天早起去跑了步，之后他会休息 $a-1$ 天，然后第 $a$ 天继续去晨跑，并以此类推。

王队长的好朋友小钦和小针深受王队长坚持锻炼的鼓舞，并决定自己也要坚持晨跑。为了适宜自己的情况，小钦决定每 $b$ 天早起跑步一次，而小针决定每 $c$ 天早起跑步一次。

某天早晨，王队长、小钦和小针在早起跑步时相遇了，他们非常激动、相互鼓励，共同完成了一次完美的晨跑。为了表述方便，我们把三位同学相遇的这天记为第 $0$ 天。假设三位同学每次晨跑的时间段和路线都相同，他们想知道，下一次三人在跑步时相遇是第几天。由于三位同学都不会算，所以希望由聪明的你来告诉他们答案。

# 输入格式

输入共一行，包含三个正整数 $a,b,c$，表示王队长每隔 $a$ 天晨跑一次、小钦每隔 $b$ 天晨跑一次且小针每隔 $c$ 天晨跑一次。

# 输出格式

输出共一行，包含一个正整数 $x$，表示三位同学下次将在第 $x$ 天相遇。

# 样例

#### 样例输入 1
```plain
2 3 5
```
#### 样例输出 1
```plain
30
```

#### 样例输入 2
```plain
3 4 6
```
#### 样例输出 2
```plain
12
```

#### 样例输入 3
```plain
10 100 1000
```
#### 样例输出 3
```plain
1000
```

# 数据范围与提示

<!-- BEGIN: Migrated markdown table -->

| 测试点编号 | $a, b, c$ 的范围 | 特殊约定 |
|-|-|-|
| 1 | $1 \leq a, b, c \leq 50$ | $a = b = c = 1$ |
| 2 | $1 \leq a, b, c \leq 50$ | $a = b = 1$ |
| 3 | $1 \leq a, b, c \leq 50$ | $a, b, c$ 中恰有两个数为 $1$ |
| 4 | $1 \leq a, b, c \leq 50$ | $a, b, c$ 中恰有两个数为 $1$ |
| 5 | $1 \leq a, b, c \leq 50$ | $a = 1$ |
| 6 | $1 \leq a, b, c \leq 50$ | $a, b, c$ 中恰有两个数为 $1$ |
| 7 | $1 \leq a, b, c \leq 50$ | $a, b, c$ 中恰有两个数为 $1$ |
| 8 | $1 \leq a, b, c \leq 50$ | $a, b, c$ 互质 |
| 9 | $1 \leq a, b, c \leq 50$ | $a, b$ 互质 |
| 10 | $1 \leq a, b, c \leq 50$ | $a, b, c$ 中恰有两个数互质 |
| 11 | $1 \leq a, b, c \leq 50$ | $a, b, c$ 中恰有两个数互质 |
| 12 | $1 \leq a, b, c \leq 50$ | 无特殊约定 |
| 13 | $1 \leq a, b, c \leq 1000$ | $a, b, c$ 互质 |
| 14 | $1 \leq a, b, c \leq 1000$ | $a, b$ 互质 |
| 15 | $1 \leq a, b, c \leq 1000$ | $a, b, c$ 中恰有两个数互质 |
| 16 | $1 \leq a, b, c \leq 1000$ | $a, b, c$ 中恰有两个数互质 |
| 17 | $1 \leq a, b, c \leq 1000$ | 无特殊约定 |
| 18 | $1 \leq a, b, c \leq 100000$ | 无特殊约定 |
| 19 | $1 \leq a, b, c \leq 100000$ | 无特殊约定 |
| 20 | $1 \leq a, b, c \leq 100000$ | 无特殊约定 |

<!-- Migrated from original HTML table:
<table class='ui center aligned celled table'>
<thead>
  <tr>
    <th>测试点编号</th>
    <th>$a, b, c$ 的范围</th>
    <th>特殊约定</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td rowspan='12'>$1 \leq a, b, c \leq 50$ </td>
    <td>$a = b = c = 1$ </td>
  </tr>
  <tr>
    <td>2</td>
    <td>$a = b = 1$ </td>
  </tr>
  <tr>
    <td>3</td>
    <td rowspan='2'>$a, b, c$ 中恰有两个数为 $1$ </td>
  </tr>
  <tr>
    <td>4</td>
  </tr>
  <tr>
    <td>5</td>
    <td>$a = 1$ </td>
  </tr>
  <tr>
    <td>6</td>
    <td rowspan='2'>$a, b, c$ 中恰有两个数为 $1$ </td>
  </tr>
  <tr>
    <td>7</td>
  </tr>
  <tr>
    <td>8</td>
    <td>$a, b, c$ 互质</td>
  </tr>
  <tr>
    <td>9</td>
    <td>$a, b$ 互质</td>
  </tr>
  <tr>
    <td>10</td>
    <td rowspan='2'>$a, b, c$ 中恰有两个数互质</td>
  </tr>
  <tr>
    <td>11</td>
  </tr>
  <tr>
    <td>12</td>
    <td>无特殊约定</td>
  </tr>
  <tr>
    <td>13</td>
    <td rowspan='5'>$1 \leq a, b, c \leq 1000$ </td>
    <td>$a, b, c$ 互质</td>
  </tr>
  <tr>
    <td>14</td>
    <td>$a, b$ 互质</td>
  </tr>
  <tr>
    <td>15</td>
    <td rowspan='2'>$a, b, c$ 中恰有两个数互质</td>
  </tr>
  <tr>
    <td>16</td>
  </tr>
  <tr>
    <td>17</td>
    <td rowspan='4'>无特殊约定</td>
  </tr>
  <tr>
    <td>18</td>
    <td rowspan='3'>$1 \leq a, b, c \leq 100000$ </td>
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
Credit：idea/何昊天　命题/何昊天　验题/卢政荣  
Git Repo：https://git.thusaac.org/publish/CodePlus201711  
感谢腾讯公司对此次比赛的支持。

