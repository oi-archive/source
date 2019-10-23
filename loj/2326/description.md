
# 题目描述

参加完 IOI2018 之后就是姚班面试。而你，由于讨厌物理、并且想成为乔布斯一样的创业家，被成功踢回贵系。

转眼，时间的指针被指向 2019，大二，12 月初，考试周。

你早听学长说，数据结构期中考很难，对竞赛生不友好，集训队选手做不完卷子。

你冷笑。哼，堂堂国际金，这点难度的考试算什么。

两小时，你看完习题解析前五章所有内容，并且倒背如流；

一小时，你看了 500 页的讲义，并且记忆犹新；

十分钟，你骑车到考场，自信的你只带了一把水笔，虽然考试让带资料；

现在，摊开传说中神级卷子，你定神一看——

给出一个长度为 $N$ 的序列 $A_{1},A_{2},\cdots,A_{N}$ ，如果 $A$ 中的一个子序列 $B_1,B_2,\cdots,B_M$，满足条件：

- $1\le M\le N$
- $\forall 1\le i<M$，$B_i\Big{|}B_{i+1}$

那么称 $B$ 为 $A$ 的`上升倍数子序列`。

现在有一个长度为 $N$ 的序列 $A$ 被初始化为 $A_{1},A_{2},\cdots,A_{N}$，以及 $Q$ 次对序列 $A$ 的操作。此处要求实现如下四种操作：

- `0 x`：在序列 $A$ 的最左端插入一个数字 $x$；
- `1 x`：在序列 $A$ 的最右端插入一个数字 $x$；
- `2`：移除序列 $A$ 最左端的一个数字；
- `3`：移除序列 $A$ 最右端的一个数字；

在初始化序列 $A$ 和**每次**操作之后，请计算此时序列 $A$ 中**最长**上升倍数子序列的长度 $\mathrm{MaxLen}$，以及所有长度为 $\mathrm{MaxLen}$ 的上升倍数子序列的不同的开头数 $\mathrm{Cnt}$，输出 $\mathrm{MaxLen}$ 和 $\mathrm{Cnt}$。

为了大幅度降低题目难度，保证在**任意时刻**序列 $A$ **非空**，其中的元素**互不相等**，并且均为 $1\sim M$ 之间的正整数；同一个数字最多只会被插入 $C$ 次。

# 输入格式

输入第一行包含三个正整数 $N,M,Q$，具体含义见上，保证 $1\le N \le 10^5$，$N\le M \le 10^6$，$0\le Q \le 10^5$；

输入第二行包含 $N$ 个正整数，为 $A_1,A_2,\cdots,A_N$，保证 $1\le A_i\le M$，并且序列 $A$ 中的元素互不相等；

接下来共 $Q$ 行输入，每行输入格式形如`0 x`或者`1 x`或者`2`或者`3`，具体含义见上。

# 输出格式

输出共 $Q+1$ 行，在初始化和每次对序列 $A$ 操作后，输出 $A$ 中最长上升倍数子序列的长度 $\mathrm{MaxLen}$ 和所有长度为 $\mathrm{MaxLen}$ 的上升倍数子序列的不同的开头数 $\mathrm{Cnt}$，用一个空格隔开。

# 样例

#### 样例输入
```plain
5 10 10
1 2 5 9 10
2
1 7
3
3
0 8
3
2
1 8
3
0 3
```

#### 样例输出
```plain
3 1
2 2
2 2
2 2
1 3
1 4
1 3
1 2
2 1
1 2
1 3
```

#### 样例解释

表格中以`//`隔开不同开头的最长上升子序列。

<!-- BEGIN: Migrated markdown table -->

| 操作次数 | $A$ | 输出答案 | 可能的解释 |
|:-:|:-:|:-:|:-:|
| 0 | 1 2 5 9 10 | 3 1 | 1 2 10 |
| 1 | 2 5 9 10 | 2 2 | 2 10//5 10 |
| 2 | 2 5 9 10 7 | 2 2 | 2 10//5 10 |
| 3 | 2 5 9 10 | 2 2 | 2 10//5 10 |
| 4 | 2 5 9 | 1 3 | 2//5//9 |
| 5 | 8 2 5 9 | 1 4 | 2//5//8//9 |
| 6 | 8 2 5 | 1 3 | 2//5//8 |
| 7 | 2 5 | 1 2 | 2//5 |
| 8 | 2 5 8 | 2 1 | 2 8 |
| 9 | 2 5 | 1 2 | 2//5 |
| 10 | 3 2 5 | 1 3 | 2//3//5 |

<!-- Migrated from original HTML table:
<table class='ui table'>
    <thead>
        <tr>
            <th style='text-align: center'> 操作次数 </th>
            <th style='text-align: center'> $A$ </th>
            <th style='text-align: center'> 输出答案 </th>
            <th style='text-align: center'> 可能的解释 </th>
        </tr>
    </thead>
    <tbody>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 0 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 1 2 5 9 10 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 3 1 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 1 2 10 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 1 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2 5 9 10 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2 2 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2 10//5 10 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2 5 9 10 7 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2 2 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2 10//5 10 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 3 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2 5 9 10 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2 2 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2 10//5 10 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 4 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2 5 9 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 1 3 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2//5//9 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 5 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 8 2 5 9 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 1 4 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2//5//8//9 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 6 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 8 2 5 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 1 3 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2//5//8 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 7 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2 5 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 1 2 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2//5 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 8 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2 5 8 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2 1 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2 8 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 9 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2 5 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 1 2 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2//5 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 10 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 3 2 5 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 1 3 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2//3//5 </td>
    	</tr>
    </tbody>
</table>
-->

<!-- END: Migrated markdown table -->

# 数据范围与提示

对于所有的数据，有 $1\le N \le 10^5$，$N\le M \le 10^6$，$0\le Q \le 10^5$，$1\le A_i\le M$，$C=10$。

下表展示了某些数据点的一些特殊约束，其中`只有1`表示只有形如`1 x`的操作，其他表述同理。

<!-- BEGIN: Migrated markdown table -->

| 测试点编号 | 约束条件 |
|:-:|:-:|
| 1,2,3 | $N,Q\le 100$ |
| 4,5 | $N,Q\le 1000$ |
| 6 | $N=M\le 1000$ |
| 7 | $Q=0$ |
| 8 | 只有0 |
| 9 | 只有1 |
| 10 | 只有2 |
| 11,12 | 只有3 |
| 13 | 只有0和1 |
| 14,15 | 只有0和2 |
| 16 | 只有1和3 |
| 17 | 只有2和3 |
| 18,19,20 | 无限制 |

<!-- Migrated from original HTML table:
<table class='ui table'>
    <thead>
        <tr>
            <th style='text-align: center'> 测试点编号 </th>
            <th style='text-align: center'> 约束条件 </th>
        </tr>
    </thead>
    <tbody>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 1,2,3 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $N,Q\le 100$ </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 4,5 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $N,Q\le 1000$ </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 6 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $N=M\le 1000$ </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 7 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $Q=0$ </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 8 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 只有0 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 9 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 只有1 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 10 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 只有2 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 11,12 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 只有3 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 13 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 只有0和1 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 14,15 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 只有0和2 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 16 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 只有1和3 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 17 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 只有2和3 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 18,19,20 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 无限制 </td>
    	</tr>
    </tbody>
</table>
-->

<!-- END: Migrated markdown table -->

#### 后记

「奋战两小时，考个四五十」的表情包占领了你的朋友圈：

- 「啊，感觉自己人生完全了。」
- 「但愿……我真的能拿到四五十。」
- 「我考完了……考完了……完了。」
- 「曾经以为是开玩笑的，原来我还是 *naïve* 了。」

你冷笑。提前半小时交卷，你自然觉得，数据结构，满分，正常。

