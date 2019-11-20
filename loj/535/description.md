
# 题目描述

> 「Hanabi, hanabi……」
>
> 一听说祭典上没有烟火，Karen 一脸沮丧。
>
> 「有的哦…… 虽然比不上大型烟花就是了。」
>
> 还好 Shinobu 早有准备，Alice、Ayaya、Karen、Shinobu、Yoko 五人又能继续愉快地玩耍啦！
>
> 「噢……！不是有放上天的烟花嘛！」Karen 兴奋地喊道。
>
> 「啊等等……」Yoko 惊呼。Karen 手持点燃引信的烟花，「嗯？？」
>
> Yoko 最希望见到的是排列优美的烟火，当然不会放过这个机会…… 不过时间似乎已经不多了。

$n$ 个烟火排成一排，从左到右高度分别为 $h_1,h_2,\cdots,h_n$，这些高度两两不同。

每次 Yoko 可以选择两个相邻的烟火交换，这样的交换可以进行任意多次。

每次 Yoko 还可以选择两个不相邻的烟火交换，但这样的交换至多进行一次。

你的任务是帮助 Yoko 用最少次数的交换，使这些烟火从左到右的高度递增。

# 输入格式

第一行包含一个正整数 $n$。

第二行包含 $n$ 个正整数 $h_1,h_2,\cdots,h_n$，相邻整数之间用一个空格隔开。

# 输出格式

输出一个整数，表示最少的交换次数。

# 样例

#### 样例输入
```plain
5
3 5 4 1 2
```

#### 样例输出
```plain
5
```

#### 样例解释
一开始，$5$ 个烟火的高度依次为 $3,5,4,1,2$。

第 $1$ 次，交换第 $4$ 根烟火和第 $5$ 根烟火，交换后烟火的高度依次为 $3,5,4,2,1$。

第 $2$ 次，交换第 $3$ 根烟火和第 $4$ 根烟火，交换后烟火的高度依次为 $3,5,2,4,1$。

第 $3$ 次，交换第 $1$ 根烟火和第 $2$ 根烟火，交换后烟火的高度依次为 $5,3,2,4,1$。

第 $4$ 次，交换第 $2$ 根烟火和第 $3$ 根烟火，交换后烟火的高度依次为 $5,2,3,4,1$。

第 $5$ 次，交换第 $1$ 根烟火和第 $5$ 根烟火，交换后烟火的高度依次为 $1,2,3,4,5$。

可以证明这是交换次数最少的方案。

# 数据范围与提示

对于所有数据，满足 $1\le n\le 300,000$，$1\le h_i\le n$，$h_i$ 互不相同。

<!-- BEGIN: Migrated markdown table -->

| Subtask # | 分值 | $n$ |
|:-:|:-:|:-:|
| 1 | $6$ | $\le 4$ |
| 2 | $11$ | $\le 8$ |
| 3 | $16$ | $\le 100$ |
| 4 | $8$ | $\le 300$ |
| 5 | $13$ | $\le 700$ |
| 6 | $7$ | $\le 2,000$ |
| 7 | $6$ | $\le 6,000$ |
| 8 | $14$ | $\le 60,000$ |
| 9 | $19$ | $\le 300,000$ |

<!-- Migrated from original HTML table:
<table class='ui table'>
    <thead>
        <tr>
            <th style='text-align: center'>Subtask #</th>
            <th style='text-align: center'> 分值 </th>
            <th style='text-align: center'> $n$ </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>1</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $6$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 4$ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>2</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $11$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 8$ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>3</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $16$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 100$ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>4</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $8$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 300$ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>5</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $13$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 700$ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>6</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $7$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 2,000$ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>7</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $6$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 6,000$ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>8</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $14$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 60,000$ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>9</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $19$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 300,000$ </td>
        </tr>
    </tbody>
</table>
-->

<!-- END: Migrated markdown table -->

