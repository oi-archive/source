
# 题目描述

最近，神犇在未来交通工具展览会上购买了一辆「$m$ 循环车」。这种交通工具的特点是：车门每行驶 $m$ 米才能开启一次。

展会结束后他准备回家，然而插入钥匙后，车内的一切突然扭曲了起来 …… 接着他发现自己到了一个奇怪的地方。这时空中传来一个声音：
  
> 哈哈哈 …… 我请你们来这里，就是为了考验一下你们的水平。这个世界是一张无向图，有 $n$ 个点，暂时还没有边。等一会我把边加上之后，每条边会有一个长度，第 $i$ 条边长 $w_i$ 米。  
> 你们的车一旦驶上一条边，就必须开到这条边的尽头，中途没有回转的余地。   
>
> 现在你们将要接受 $q$ 次考验。考验有两种：
>
> 1. 告诉你们三个整数 $u,v,w$ 表示我在 $u$ 和 $v$ 之间加了一条长 $w$ 米的边；
> 2. 告诉你们五个整数 $u,v,x,b,c \ (u\neq v)$，其中 $x,b$ 描述了一个伪随机数生成器，它第一次的返回值 $f_1=x\bmod m$，以后每次的返回值 $f_{i+1}=(f_i+b)\bmod m$。你们要回答，对于 $i=1,2,\ldots,c$，有多少个 $i$ 满足：如果你的车离最近一次能够开门的机会还有 $f_i$ 米，那么存在一条路径使你能从 $u$ 出发到 $v$ 下车。
>
> 除非你们的回答全部正确且快速，否则我是不会放你们离开这里的 …… 哈哈哈 ……  

按照套路，神犇自然是一眼秒掉了这个问题。不过为了不让黑恶势力白白出场，他想请你也解决一下这个问题。

<hr/>

**简略题意**：一个带边权无向图，有两种操作：加边以及询问在 $x,x+b,...,x+(c-1)b$ 这些数中，有多少存在一条与之模 $m$ 同余的从 $u$ 到 $v$ 的路径（可以不是简单路径）。


# 输入格式

第一行三个整数 $n,m,q$。  
接下来 $q$ 行，每行描述一次考验，内容如下：

* $\texttt{1 u v w}$ 表示 $u$ 和 $v$ 之间加了一条长 $w$ 米的边；
* $\texttt{2 u v x b c}$ 表示询问对于 $i=1,2,\ldots,c$，有多少个 $i$ 满足：如果你的车离最近一次能够开门的机会还有 $f_i$ 米，那么存在一条路径使你能从 $u$ 出发到 $v$ 下车。

# 输出格式

对于每个第二种考验，输出一行一个整数表示答案。

# 样例

#### 样例输入 1
```plain
6 6 10
1 1 2 3
2 1 2 0 0 1
1 2 3 3
1 1 3 3
2 1 2 0 0 1
1 4 5 6
1 5 6 4
2 4 6 2 0 1
1 3 4 6
2 1 6 0 1 6 
```

#### 样例输出 1
```plain
0
1
1
6
```

#### 样例解释 1
![sample1.png](/source/loj/508/img/aHR0cHM6Ly9vb28uMG8wLm9vby8yMDE3LzA3LzA2LzU5NWU0MTkwOGVmMDgucG5n.png)

#### 更多样例
见附加文件或[备用网盘链接](https://pan.baidu.com/s/1hswytLi)（提取码：`a795`）

# 数据范围与提示

对于 $100\%$ 的数据，$1\leq n,q\leq 10^6,1< m\leq 10^9,1\leq w\leq m,0\leq x,b< m,1\leq c\leq 10^9$。**操作 2 中保证 $u\neq v$**。

当车离最近一次能够开门的机会还有 $r$ 米时，「存在一条路径使你能从 $u$ 出发到 $v$ 下车」的意思是 $u$ 和 $v$ 之间存在一条路径（可以不是简单路径）长度模 $m$ 为 $r$。 

**注意，路径可以不是简单路径。**

**出题人的关怀：由于输入规模较大，建议使用读入优化；请相信 LibreOJ 测评机的速度。**

<!-- BEGIN: Migrated markdown table -->

| Subtask # | 分值 | $n, q$ 的限制 | $m$ 的限制 | $c$ 的限制 | 附加限制 |
|:-:|:-:|:-:|:-:|:-:|:-:|
| 1 | $11$ | $1 \leq n, q \leq 100 $ | $1 < m \leq 100 $ | $1 \leq c \leq 5 $ | 无 |
| 2 | $21$ | $1 \leq n, q \leq 2\times 10^5$ | $m=2 $ | $1 \leq c \leq 5 $ | 无 |
| 3 | $13$ | $1 \leq n, q \leq 2\times 10^5$ | $m$ 是质数 | $1 \leq c \leq 5 $ | 无 |
| 4 | $7$ | $1 \leq n, q \leq 2\times 10^5$ | $m$ 是奇数 | $1 \leq c \leq 5 $ | 图中任何时刻都不会出现简单环 |
| 5 | $10$ | $1 \leq n, q \leq 2\times 10^5$ | $m$ 是奇数 | 无 | 无 |
| 6 | $5$ | $1 \leq n, q \leq 2\times 10^5$ | 无 | $1 \leq c \leq 5 $ | 图中任何时刻不会有度数大于 $2$ 的点 |
| 7 | $13$ | $1 \leq n, q \leq 2\times 10^5$ | 无 | $1 \leq c \leq 5 $ | 无 |
| 8 | $20$ | $1 \leq n, q \leq 10^6 $ | 无 | 无 | 无 |

<!-- Migrated from original HTML table:
<table class='ui table'>
    <thead>
        <tr>
            <th style='text-align: center'>Subtask #</th>
            <th style='text-align: center'> 分值 </th>
            <th style='text-align: center'> $n, q$ 的限制 </th>
            <th style='text-align: center'> $m$ 的限制 </th>
            <th style='text-align: center'> $c$ 的限制 </th>
            <th style='text-align: center'>附加限制</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>1</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $11$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $1 \leq n, q \leq 100 $ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $1 < m \leq 100 $ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='4'> $1 \leq c \leq 5 $ </td>
            <td style='text-align: center' rowspan='3'>无</td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>2</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $21$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='6'> $1 \leq n, q \leq 2\times 10^5$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='1'> $m=2 $ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>3</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $13$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='1'> $m$ 是质数 </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>4</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $7$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> $m$ 是奇数 </td>
            <td style='text-align: center' rowspan='1'> 图中任何时刻都不会出现简单环 </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>5</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $10$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='1'> 无 </td>
            <td style='text-align: center' > 无 </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>6</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $5$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='3'> 无 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> $1 \leq c \leq 5 $ </td>
            <td style='text-align: center' rowspan='1'> 图中任何时刻不会有度数大于 $2$ 的点 </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>7</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $13$ </td>
            <td style='text-align: center' rowspan='2'> 无 </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>8</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $20$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='1'> $1 \leq n, q \leq 10^6 $ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='1'> 无 </td>
        </tr>
    </tbody>
</table>
-->

<!-- END: Migrated markdown table -->

