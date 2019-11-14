
# 题目描述

> 激动人心的日子终于到了。这天，他们坐上了奔向考场的列车。夕阳下绯色的天空，衬着纯黑的目送者的剪影，成为了列车消失前最后的背景。
>
> 列车徐徐行驶，Rlc 望着 Jsp，欲言又止。但她知道 Jsp 对 OI 以外的东西总是一副冷冰冰的样子，于是找来了一道旅行商问题：

给定完全图 $G=(V,E)$，每个点 $v\in V$ 有一个权值 $w_v\in\mathbb{Z}$，边 $e=(u,v)\in E$ 的长度 $w_e$ 定义为 $w_e=(w_u-w_v)^2$。

现要求一条 $G$ 中的哈密顿回路 $C$，要求经过 $V$ 中的各个点恰好一次，且回路的长度 $w(C)$ 最小。回路 $C$ 的长度 $w(C)$ 定义为 $C$ 经过的所有边的长度之和，即

$$w(C)=\sum_{e\in E(C)}w_e$$

你只需输出最小的 $w(C)$ 值。

# 输入格式

输入第一行包含一个正整数 $n$，表示 $|V|$。设 $V=\{1,2,\cdots,n\}$。

第二行包含 $n$ 个由空格分隔的整数，表示 $w_1,w_2,\cdots,w_n$。

# 输出格式

输出仅一行，包含一个整数，表示最小的 $w(C)$ 值。

# 样例

#### 样例输入
```plain
4
1 2 3 4
```

#### 样例输出
```plain
10
```

#### 样例解释
令回路 $C:1\rightarrow 3\rightarrow 4\rightarrow 2\rightarrow 1$，则回路长度为

$$w(C)=(w_1-w_3)^2+(w_3-w_4)^2+(w_4-w_2)^2+(w_2-w_1)^2=2^2+1^2+2^2+1^2=10$$

可以证明这是最小的 $w(C)$ 值。

# 数据范围与提示

对于所有数据，满足 $2\le n\le 100,000$，$-10^9\le w_v\le 10^9$。

<!-- BEGIN: Migrated markdown table -->

| Subtask # | 分值 | $n$ | $\|w_v\|$ |
|:-:|:-:|:-:|:-:|
| 1 | $10$ | $\le 10$ | $\le 10^3$ |
| 2 | $10$ | $\le 15$ | $\le 10^3$ |
| 3 | $10$ | $\le 20$ | $\le 10^3$ |
| 4 | $20$ | $\le 100$ | $\le 10^3$ |
| 5 | $20$ | $\le 2,000$ | $\le 10^6$ |
| 6 | $30$ | $\le 100,000$ | $\le 10^9$ |

<!-- Migrated from original HTML table:
<table class='ui table'>
    <thead>
        <tr>
            <th style='text-align: center'>Subtask #</th>
            <th style='text-align: center'> 分值 </th>
            <th style='text-align: center'> $n$ </th>
            <th style='text-align: center'> $|w_v|$ </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>1</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $10$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 10$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='4'> $\le 10^3$ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>2</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $10$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 15$ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>3</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $10$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 20$ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>4</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $20$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 100$ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>5</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $20$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 2,000$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 10^6$ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>6</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $30$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 100,000$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 10^9$ </td>
        </tr>
    </tbody>
</table>
-->

<!-- END: Migrated markdown table -->

