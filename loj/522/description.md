
# 题目描述

IOI 的比赛开始了。Jsp 和 Rlc 坐在一个角落，这时他们听到了一个异样的声音 ……

![黑恶势力登场](/source/loj/522/img/aHR0cDovL2ltZy51b2ouYWMvcHJvYmxlbS8yNDEvZGFyay5qcGc=.jpg)

接着他们发现自己收到了一封电子邮件：  

> 我们在考场上放置了 $N$ 个炸弹。如果建立一个直线坐标系（数轴）的话，第 $i$ 个炸弹的坐标是 $X_i$，爆炸半径是 $R_i$，当一个炸弹爆炸时，如果另一个炸弹所在位置 $X_j$ 满足：
> $$
> X_i-R_i\leq X_j\leq X_i+R_i
> $$
> 那么，炸弹 $j$ 也会被引爆。
>
> 若 $i$ 和 $j$ 满足上述关系式，称 $i$ 能直接引爆 $j$。若 $i$ 不能直接引爆 $j$，但引爆 $i$ 会导致 $j$ 爆炸，则称 $i$ 能间接引爆 $j$。
>
> 我可以告诉你们，这些炸弹满足一个性质：**若引爆炸弹 $A$ 会直接或间接地引爆炸弹 $B$，则引爆炸弹 $B$ 一定不会直接或间接地引爆炸弹 $A$。**
>
> 有能耐就拆掉炸弹吧！记住，如果其它选手有所动作的话，后果你们应该知道！

吃惊的 Jsp 和 Rlc 开始了调（报）查（警）。之后，这些话被证实了。并且两人还发现了另一个性质：

> 定义炸弹 $A$ 到 $B$ 的“引爆距离”（用 $d(A,B)$ 表示）为最长的满足以下条件的序列 $a_1,a_2,...,a_n$ 的长度：

> 1. $a_i$ 互不相同，且为 $[1,N]$ 中的整数；
> 2. $a_i$ 能**直接**引爆 $a_{i+1}$；
> 3. $a_1=A,a_n=B$。

> 那么这个性质可以表述为：若 $d(A,B)=3$，$A$ 一定能直接引爆 $B$。

经过进一步研究，Rlc 发现最为安全的方法是这样：首先选出若干个关键炸弹安装监测器，然后慢慢拆除。

因为炸弹的某些特性，安装监测器的炸弹必须组成一个有序序列 $a_1,a_2,...,a_n$，且满足：

1. $a_i$ 互不相同，且为 $[1,N]$ 中的整数。
2. $a_i$ 能**直接或间接**引爆 $a_{i+1}$。

Rlc 设计了一个衡量监测器安装方案的安全程度的方法：  

首先可以测出每个炸弹的特征值 $v_i$。  
那么监测器安装方案的安全程度为：$\sum_{i=1}^{n-1}F(v_{a_i},v_{a_{i+1}})$，其中 $F(x,y)=(x\oplus y+xy)\bmod 998244353$（$\oplus$ 表示二进制按位异或，**本题中按位异或的优先级高于乘法和加法**）。

现在她想知道，对于 $[1,N]$ 中的每个整数 $i$，如果她安装监测器的最后一个炸弹是 $i$（即 $a_n=i$），安全程度最大是多少。

**请特别注意，题面中大写的 $N$ 表示炸弹总数，小写 $n$ 表示上下文中的序列长度，请勿混淆。**

# 输入格式

第一行一个整数 $N$ 表示炸弹个数。  
第二行 $N$ 个整数 $X_1,X_2,...,X_N$，表示炸弹的坐标。  
第三行 $N$ 个整数 $R_1,R_2,...,R_N$，表示炸弹的爆炸半径。  
第四行 $N$ 个整数 $v_1,v_2,...,v_N$，表示炸弹的特征值。

# 输出格式

输出 $N$ 行，每行一个整数，第 $i$ 行表示拆除的最后一个炸弹是 $i$ 时的最大安全程度。

# 样例

#### 样例输入
```plain
6
-3 -2 0 2 3 4
0 1 4 1 0 1
4 1 3 4 2 0
```

#### 样例输出
```plain
19
5
0
19
33
3
```

#### 样例解释
以 $1$ 结尾的最优监测器安装序列：$3,1$  
以 $2$ 结尾的最优监测器安装序列：$3,2$  
以 $3$ 结尾的最优监测器安装序列：$3$  
以 $4$ 结尾的最优监测器安装序列：$3,4$  
以 $5$ 结尾的最优监测器安装序列：$3,4,5$  
以 $6$ 结尾的最优监测器安装序列：$3,6$  

![](https://ooo.0o0.ooo/2017/06/22/594b1ce84ad04.png)

# 数据范围与提示

对于所有数据，$1\leq N\leq 3\times 10^5,0\leq v_i<998244353,0\leq R_i\leq 10^{18},|X_i|\leq 10^{18}$。

**请特别注意，题面中大写的 $N$ 表示炸弹总数，小写 $n$ 表示上下文中的序列长度，请勿混淆。**

<!-- BEGIN: Migrated markdown table -->

| Subtask # | 分值 | $N$ 的限制 | $v$ 的限制 | $R$ 的限制 |
|:-:|:-:|:-:|:-:|:-:|
| 1 | $10$ | $1 \leq N \leq 10 $ | 无 | 无 |
| 2 | $10$ | $1 \leq N \leq 300$ | 无 | 无 |
| 3 | $10$ | $1 \leq N \leq 3000$ | 无 | 无 |
| 4 | $10$ | $1 \leq N \leq 3\times 10^5$ | $v_i=1$ | 无 |
| 5 | $15$ | $1 \leq N \leq 3\times 10^5$ | $v_i\in\{0,1\}$ | 无 |
| 6 | $15$ | $1 \leq N \leq 3\times 10^5$ | 无 | $R_i\leq 10^4$ |
| 7 | $30$ | $1 \leq N \leq 3\times 10^5$ | 无 | 无 |

<!-- Migrated from original HTML table:
<table class='ui table'>
    <thead>
        <tr>
            <th style='text-align: center'>Subtask #</th>
            <th style='text-align: center'> 分值 </th>
            <th style='text-align: center'> $N$ 的限制 </th>
            <th style='text-align: center'> $v$ 的限制 </th>
            <th style='text-align: center'> $R$ 的限制 </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>1</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $10$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $1 \leq N \leq 10 $ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='3'> 无 </td>
            <td style='text-align: center' rowspan='5'> 无 </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>2</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $10$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='1'> $1 \leq N \leq 300$ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>3</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $10$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='1'> $1 \leq N \leq 3000$ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>4</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $10$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='4'> $1 \leq N \leq 3\times 10^5$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='1'> $v_i=1$ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>5</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $15$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='1'> $v_i\in\{0,1\}$ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>6</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $15$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> 无 </td>
            <td style='text-align: center' rowspan='1'> $R_i\leq 10^4$ </td>
        </tr>
        <tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>7</td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $30$ </td>
            <td style='text-align: center' rowspan='1'> 无 </td>
        </tr>
    </tbody>
</table>
-->

<!-- END: Migrated markdown table -->

