
# 题目描述

回到了正常的时空，神犇和 LCR 暂时过着安宁又平静的生活，他们回想起三年前的往事……

> 秋日的北校门格外美丽，这天，神犇和 LCR 第一次因化学中二而相遇……

令神犇难以忘怀的是，他与 LCR 相遇是在校门外的树下。那棵树的奇特形态深深印在神犇的脑中。神犇称这棵树是一棵“K 项树”。  
为了纪念他和 LCR 的第一次相遇，神犇后来写的树状数组都是以 K 进制而非二进制为基的。

神犇的机房里有一位名叫 LCA 的蒟蒻，一天他碰巧欣赏到了神犇的代码，它发现神犇的树状数组是这么写的：  

```
function add(x,v)
    while x <= n do
        s[x] = s[x] xor v
        x = x + lowbitv(x)
    end while
end function

function query(x)
    ans = 0
    while x > 0 do
        ans = ans xor s[x]
        x = x - lowbit(x)
    end while
    return ans
end function
```
其中：
* $\mathrm{lowbit}(x)$ 表示 $K$ 进制下 $x$ 的最低非零位的值（例如当 $K=5$ 时，$\mathrm{lowbit}(230_{(5)})=30_{(5)}=15_{(10)}$）
* $\mathrm{lowbitv}(x)$ 表示 $K$ 进制下 $x$ 的最低非零位的位值（即该位为 1 其它位都为 0 时的数值，例如当 $K=5$ 时，$\mathrm{lowbitv}(230_{(5)})=10_{(5)}=5_{(10)}$）

这份代码的作用是维护一个长度为 $n$ 的序列 $A$，支持单点**异或**上一个值和求前缀**异或和**。$s[i]$ 维护的是 $\mathop{\oplus}\limits_{i\in (s[i]-\mathrm{lowbit}(s[i]),s[i]]} A_i$。（$\oplus$ 表示按位异或）

LCA 觉得这种写法十分不错，于是自己也这么写，但总是写挂的 LCA 漏打了一个字符，还把 $K$ 的值设定得大了很多。

也就是说，LCA 的代码是这么写的：
```
function add(x,v)
    while x <= n do
        s[x] = s[x] xor v
        x = x + lowbit(x) //注意，这里是 lowbit，这也是两份代码唯一的区别
    end while
end function

function query(x)
    ans = 0
    while x > 0 do
        ans = ans xor s[x]
        x = x - lowbit(x)
    end while
    return ans
end function
```
**注意：两个函数调用的都是 $\mathrm{lowbit}$。**

紧接着 LCA 就发现自己的代码跑得比谁都慢，他百思不得其解，只好来请你帮他解决这个问题。

请写一个和 LCA 的程序的输出相同的程序。

**注意，你的任务是写一个和 LCA 的程序输出相同的程序，而不是正确的程序。**

# 输入格式

第一行三个正整数 $n,q,K$，表示序列长度，操作数和进制的基数。**序列初始全为 0，LCA 的 s 数组也会初始化为全 0**。  
接下来 $q$ 行每行格式是下列之一：  
* $\texttt{1 x v}$ 给 $A_x$ 的值异或上 $v$。LCA 会调用 $\mathrm{add}(x,v)$。
* $\texttt{2 x}$ 查询 $\mathop{\oplus}\limits_{i\in (0,x]} A_i$。LCA 会输出一行一个整数，为调用 $\mathrm{query}(x)$ 的结果。


# 输出格式

对于每个 2 操作，输出一个整数表示 **LCA 程序的输出**。

**注意，你的任务是写一个和 LCA 的程序输出相同的程序，而不是正确的程序。**

# 样例

#### 样例输入
```plain
7 16 5
1 1 10
2 1
1 4 15
2 4
1 6 10
1 4 15
2 6
2 6
1 6 5
1 5 12
2 3
1 2 5
1 4 5
2 5
1 6 0
1 5 5
```

#### 样例输出
```plain
10
5
10
10
0
12
```

#### 更多样例
见附加文件或[备用网盘链接](https://pan.baidu.com/s/1bo2ydeJ)（提取码：`q5bs`）

# 数据范围与提示

对于 $100\%$ 的数据，$1\leq x\leq n\leq 10^9,1\leq q\leq 2\times 10^5,2\leq K\leq 2\times 10^5,0\leq v\leq 10^9$。

**注意，你的任务是写一个和 LCA 的程序输出相同的程序，而不是正确的程序。**

<!-- BEGIN: Migrated markdown table -->

| Subtask # | 分值 | $n,q$ 的限制 | $K$ 的限制 |
|:-:|:-:|:-:|:-:|
| 1 | $17$ | $1 \leq n, q \leq 3000 $ | $2 \leq K \leq 3000 $ |
| 2 | $15$ | $1 \leq n \leq 2\times 10^5$ | $K=2 $ |
| 3 | $19$ | $1 \leq n \leq 2\times 10^5$ | $K$ 是奇数 |
| 4 | $24$ | $1 \leq n \leq 2\times 10^5$ | 无 |
| 5 | $25$ | 无 | 无 |

<!-- Migrated from original HTML table:
<table class='ui table'>
    <thead>
        <tr>
            <th style='text-align: center'>Subtask #</th>
            <th style='text-align: center'> 分值 </th>
            <th style='text-align: center'> $n,q$ 的限制 </th>
            <th style='text-align: center'> $K$ 的限制 </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>1</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $17$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $1 \leq n, q \leq 3000 $ </td>
            <td style='text-align: center'> $2 \leq K \leq 3000 $ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>2</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $15$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='3'> $1 \leq n \leq 2\times 10^5$ </td>
            <td style='text-align: center' rowspan='1'> $K=2 $ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>3</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $19$ </td>
            <td style='text-align: center' rowspan='1'> $K$ 是奇数 </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>4</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $24$ </td>
            <td style='text-align: center' rowspan = '2'> 无 </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>5</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $25$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='1'> 无 </td>
        </tr>
    </tbody>
</table>
-->

<!-- END: Migrated markdown table -->

