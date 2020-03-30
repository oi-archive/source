
# 题目描述

随着人类计算机技术的发展，计算机的能力不断提升，让跳蚤国王非常羡慕。

终于有一天，跳蚤国王发布政令：大力发展跳蚤国的计算机产业！然而，跳蚤国尚未进行工业革命，无法制造出电子计算机所需的元器件。但是跳蚤国王想出了一个绝妙的想法：把每只跳蚤作为一个计算节点，每只跳蚤只完成一个特定的小任务。

跳蚤国王带领 $n$ 只跳蚤来到了一片旷野上，把跳蚤作为计算节点在旷野上排列好，并编号为 $1$ 到 $n$。每个计算节点会把某几个（也有可能是 $0$ 个）计算节点的结果作为输入，计算得到输出。除此之外，跳蚤国王还有一个巨型的终端，可以从终端输入和输出数据，这台终端和所有计算节点组成了一台计算机。

记第 $t$ 个计算节点的输出为 $x_t$，该节点的操作可分为以下几种类型：

<!-- BEGIN: Migrated markdown table -->

| 名称 | 操作符（类型） | 操作数 | 计算结果 |
|-|-|-|-|
| 输入节点 | `I` | 无 | 从终端读入一个实数作为 $x_t$ |
| 输出节点 | `O` | $i$ | $x_t = x_i$，并将 $x_t$ 输出到终端 |
| 加法节点 | `+` | $i,j$ | $x_t = x_i+x_j$ |
| 偏移节点 | `C` | $i,c$ | $x_t=x_i+c$ |
| 取反节点 | `-` | $i$ | $x_t=-x_i$ |
| 左移节点 | `<` | $i,k$ | $x_t=x_i\cdot 2^k$ |
| 右移节点 | `>` | $i,k$ | $x_t=x_i\cdot 2^{-k}$ |
| S 型节点 | `S` | $i$ | $x_t=s(x_i)$ |
| 比较节点 | `P` | $i,j$ | $x_t=\begin{cases}-1 &x_i<x_j\\ 0 &x_i=x_j\\1 &x_i>x_j\\\end{cases}$|
| Max 节点 | `M` | $i,j$ | $x_t=\begin{cases}x_i &x_i>x_j\\x_j &x_i \leq x_j\end{cases}$ |
| 乘法节点 | `*` | $i,j$ | $x_t=x_i \cdot x_j$ |

<!-- Migrated from original HTML table:
<table class="ui celled table">
<thead>
<tr><th> 名称 </th><th> 操作符（类型） </th><th> 操作数 </th><th> 计算结果 </th></tr>
</thead>
<tbody>
<tr><td> 输入节点 </td><td> `I` </td><td> 无 </td><td> 从终端读入一个实数作为 $x_t$ </td></tr>
<tr><td> 输出节点 </td><td> `O` </td><td> $i$ </td><td> $x_t = x_i$，并将 $x_t$ 输出到终端 </td></tr>
<tr><td> 加法节点 </td><td> `+` </td><td> $i,j$ </td><td> $x_t = x_i+x_j$ </td></tr>
<tr><td> 偏移节点 </td><td> `C` </td><td> $i,c$ </td><td> $x_t=x_i+c$ </td></tr>
<tr><td> 取反节点 </td><td> `-` </td><td> $i$ </td><td> $x_t=-x_i$ </td></tr>
<tr><td> 左移节点 </td><td> `<` </td><td> $i,k$ </td><td> $x_t=x_i\cdot 2^k$ </td></tr>
<tr><td> 右移节点 </td><td> `>` </td><td> $i,k$ </td><td> $x_t=x_i\cdot 2^{-k}$ </td></tr>
<tr><td> S 型节点 </td><td> `S` </td><td> $i$ </td><td> $x_t=s(x_i)$ </td></tr>
<tr><td> 比较节点 </td><td> `P` </td><td> $i,j$ </td><td> 
  $x_t=
    \begin{cases}
    -1 &x_i<x_j\\
    0 &x_i=x_j\\
    1 &x_i>x_j
   \end{cases}$ </td></tr>
<tr><td> Max 节点 </td><td> `M` </td><td> $i,j$ </td><td>
  $x_t=
    \begin{cases}
    x_i &x_i>x_j\\
    x_j &x_i \leq x_j
   \end{cases}$ </td></tr>
<tr><td> 乘法节点 </td><td> `*` </td><td> $i,j$ </td><td> $x_t=x_i \cdot x_j$ </td></tr>
</tbody>
</table>
-->

<!-- END: Migrated markdown table -->

其中，函数 $s(x)$ 的定义如下：（$e$ 为自然常数，其值约为 $ 2.718281828459045 \ldots$）
$$s(x)=\frac{1}{1+e^{-x}}$$

$s(x)$ 的函数图像如下图所示：

![](/source/loj/2088/img/aHR0cDovL2ltZy51b2ouYWMvcHJvYmxlbS8yMjQvdy5wbmc=.png)

上述表格中的操作数 $i, j$ 均要小于当前节点的编号 $t$，这样随着跳蚤国王的一声令下，跳蚤就可以按编号从小到大的顺序，依次获得输入然后计算输出。每个跳蚤的计算能力都是有限的，他们仅可以精确到十进制小数点后 $90$ 位，超过的部分将会被四舍五入。同理，上述表格中的操作数 $c$ 的小数部分也不能超过 $90$ 位。另外，左移节点和右移节点中的操作数 $k$ 必须是非负整数，且不能超过 $10000$。

把跳蚤排列好后，野心勃勃的跳蚤国王决心测试一下这台由跳蚤组成的计算机的计算能力，于是蝈蝈大臣给跳蚤国王献上了 $10$ 个计算任务。完成每个计算任务均需要从终端获取输入，进行中间计算，再用输出节点将结果输出。具体任务说明如下：

<!-- BEGIN: Migrated markdown table -->

| 编号 | 输入 | 输入限制 | 输出 |
|-|-|-|-|
| $1$ | $a,b$ | <div> $\lvert a \rvert, \lvert b \rvert \le 10^9$ </div><div> 小数部分不超过 $9$ 位 </div> | $-2a-2b$ |
| $2$ | $a$ | <div> $\lvert a \rvert \le 10^9$ </div><div> 小数部分不超过 $9$ 位 </div> | $\frac{1}{1+e^{17a}}$ |
| $3$ | $a$ | <div> $\lvert a \rvert \le 10^9$ </div><div> 小数部分不超过 $9$ 位 </div> | $\begin{equation}\begin{cases}-1 & a \lt 0 \\ 0 & a = 0 \\ 1 & a \gt 0\end{cases}\end{equation}$ |
| $4$ | $a$ | <div> $\lvert a \rvert \le 10^9$ </div><div> 小数部分不超过 $9$ 位 </div> | $\lvert a \rvert$，即 $a$ 的绝对值 |
| $5$ | $a_1, \dots, a_{32}$ | $a_1, \dots, a_{32} \in \{0, 1\}$ | 把 $a_1, \dots, a_{32}$ 从左到右看成一个二进制整数，高位在左低位在右，输出该整数的值 |
| $6$ | $a$ | <div> $0 \le a \lt 2^{32}$ </div><div> $a$ 为整数 </div> | 输出 $32$ 个整数，从高位到低位输出 $a$ 的二进制表示（不足 $32$ 位的在高位补 $0$） |
| $7$ | $a,b$ | <div> $0 \le a, b \lt 2^{32}$ </div><div> $a,b$ 均为整数 </div> | $a, b$ 按位异或的结果 |
| $8$ | $a$ | <div> $\lvert a \rvert \le 10^9$ </div><div> 小数部分不超过 $9$ 位 </div> | $\frac{a}{10}$ |
| $9$ | $a_1, \dots, a_{16}$ | <div> $\lvert a_1 \rvert, \dots, \lvert a_{16} \rvert \le 10^9$ </div><div> 小数部分不超过 $9$ 位 </div> | 输出 $16$ 个实数，表示 $a_1, \dots, a_{16}$ 从小到大排序后的结果 |
| $10$ | $a,b,m$ | <div> $0 \le a, b \lt 2^{32}$ </div><div> $1 \le m \lt 2^{32}$ </div><div> $a,b,m$ 均为整数 </div> | $a \cdot b$ 除以 $m$ 的余数 |

<!-- Migrated from original HTML table:
<table class="ui celled table"><thead><tr><th>编号</th>
<th>输入</th>
<th>输入限制</th>
<th>输出</th>
</tr></thead><tbody><tr><td> $1$ </td><td> $a,b$ </td><td><div> $\lvert a \rvert, \lvert b \rvert \le 10^9$ </div><div> 小数部分不超过 $9$ 位 </div></td><td> $-2a-2b$ </td></tr><tr><td> $2$ </td><td> $a$ </td><td><div> $\lvert a \rvert \le 10^9$ </div><div> 小数部分不超过 $9$ 位 </div></td><td> $\frac{1}{1+e^{17a}}$ </td></tr><tr><td> $3$ </td><td> $a$ </td><td><div> $\lvert a \rvert \le 10^9$ </div><div> 小数部分不超过 $9$ 位 </div></td><td> 
$$
\begin{equation}\begin{cases}-1 & a \lt 0 \\ 0 & a = 0 \\ 1 & a \gt 0\end{cases}\end{equation}
$$ </td></tr><tr><td> $4$ </td><td> $a$ </td><td><div> $\lvert a \rvert \le 10^9$ </div><div> 小数部分不超过 $9$ 位 </div></td><td> $\lvert a \rvert$，即 $a$ 的绝对值 </td></tr><tr><td> $5$ </td><td> $a_1, \dots, a_{32}$ </td><td> $a_1, \dots, a_{32} \in \{0, 1\}$ </td><td> 把 $a_1, \dots, a_{32}$ 从左到右看成一个二进制整数，高位在左低位在右，输出该整数的值 </td></tr><tr><td> $6$ </td><td> $a$ </td><td><div> $0 \le a \lt 2^{32}$ </div><div> $a$ 为整数 </div></td><td> 输出 $32$ 个整数，从高位到低位输出 $a$ 的二进制表示（不足 $32$ 位的在高位补 $0$）</td></tr><tr><td> $7$ </td><td> $a,b$ </td><td><div> $0 \le a, b \lt 2^{32}$ </div><div> $a,b$ 均为整数 </div></td><td> $a, b$ 按位异或的结果 </td></tr><tr><td> $8$ </td><td> $a$ </td><td><div> $\lvert a \rvert \le 10^9$ </div><div> 小数部分不超过 $9$ 位 </div></td><td> $\frac{a}{10}$ </td></tr><tr><td> $9$ </td><td> $a_1, \dots, a_{16}$ </td><td><div> $\lvert a_1 \rvert, \dots, \lvert a_{16} \rvert \le 10^9$ </div><div> 小数部分不超过 $9$ 位 </div></td><td> 输出 $16$ 个实数，表示 $a_1, \dots, a_{16}$ 从小到大排序后的结果 </td></tr><tr><td> $10$ </td><td> $a,b,m$ </td><td><div> $0 \le a, b \lt 2^{32}$ </div><div> $1 \le m \lt 2^{32}$ </div><div> $a,b,m$ 均为整数 </div></td><td> $a \cdot b$ 除以 $m$ 的余数 </td></tr></tbody></table>
-->

<!-- END: Migrated markdown table --></div>

跳蚤国王发现自己没有足够的能力设计这样的计算机。于是他找到了来参加 NOI 的你。请你依次设计每个计算节点的类型及操作数，完成蝈蝈大臣给的这 $10$ 个计算任务，且要求使用的计算节点数尽量少。

# 输入格式

所有输入数据 `nodes1.in~nodes10.in` 见数据下载，分别对应 $10$ 个计算任务。

每组输入数据仅包含一个整数，表示需要解决的计算任务编号。

# 输出格式

输出文件为 `nodes1.out~nodes10.out`，分别对应相应的输入文件。

对于每组输入数据，你需要依次输出若干行，第 $i$ 行描述第 $i$ 个计算节点。

描述每个计算节点时，首先一个字符表示该计算节点的类型，接下来若干个数按顺序表示该计算节点的内置参数。字符与数，数与数之间均用空格隔开。

输出的行数不能超过 $10^4$ 行。

# 样例

#### 样例输入
```plain
1
```
#### 样例输出
```plain
I
+ 1 1
- 2
I
+ 4 4
- 5
+ 3 6
- 7
- 8
O 9
```
#### 样例说明
该样例输出为第一个计算任务一个可能的构造。共用了 $10$ 个计算节点，可获得 $3$ 分。

# 数据范围与提示

#### 评分方式
我们提供了十个评分文件 `nodes1.ans~nodes10.ans`，分别对应每个计算任务。每个评分文件共 $10$ 行，第 $i$ 行一个评分参数 $w_i$，具体意义将在下面给出。

本题中，每个测试点单独进行评分，每个测试点 $10$ 分，如果选手的输出格式不合法或者参数不符合题目约定，则得 $0$ 分。

否则，按照以下规则判定选手的输出是否正确：

首先测评器会生成若干组输入数据，并将输入数据代入你构造的计算机。

如果在代入某一组输入数据时：你构造的计算机的计算过程中，某个计算节点的计算结果的绝对值超过 $10^{1000}$，则得 $0$ 分；你构造的计算机的输出中的某个值与预期的输出值相差超过 $10^{-9}$，则认为你的输出不正确，得 $0$ 分。

否则，我们认为你的计算机能完成给定的计算任务，并按照以下规则得分。

对于每个测试点，我们设置了 $10$ 个评分参数 $w_1 , w_2 , w_3 , \dots , w_9 , w_{10}$，假设共使用了 $n$ 个计算节点,你的分数将会由下表给出：

| 得分 |          条件          | 得分 |         条件          |
| :--: | :--------------------: | :--: | :-------------------: |
| $10$ |     $n\le w_{10}$      | $5$  | $w_{6}\lt n\le w_{5}$ |
| $9$  | $w_{10}\lt n\le w_{9}$ | $4$  | $w_{5}\lt n\le w_{4}$ |
| $8$  | $w_{9}\lt n\le w_{8}$  | $3$  | $w_{4}\lt n\le w_{3}$ |
| $7$  | $w_{8}\lt n\le w_{7}$  | $2$  | $w_{3}\lt n\le w_{2}$ |
| $6$  | $w_{7}\lt n\le w_{6}$  | $1$  | $w_{2}\lt n\le w_{1}$ |

若不符合表中所有条件，得 $0$ 分。

除此之外，使用比较节点、Max 节点和乘法节点的代价是极为昂贵的。因此，这三种节点每使用**一种**，就会从你这个测试点的得分中倒扣 $4$ 分。

注意这里是按使用节点的种类数计算扣分，与使用次数无关。例如多次使用比较节点，只会扣除 $4$ 分；又如同时使用了比较节点和乘法节点，即使各只使用了一次，也会扣除 $8$ 分。

一个测试点至多被扣到 $0$ 分，即使分数不够扣除，也不会出现负数。

#### 如何测试你的输出
在附加文件中，我们提供了 `checker.cpp` 和所需的 `testlib.h`，请自行编译后测试。

编译好后，在终端（Linux）中输入如下命令（假设编译好的检查器名称为 `checker`）：
```bash
./checker <case_no>
```
或在命令提示符（Windows）中输入如下命令：
```bash
checker <case_no>
```
其中，`<case_no>` 为需要检查的测试点编号。在运行前，请将 `nodes*.in/out/ans` 与 `checker` 放于同一目录下。

