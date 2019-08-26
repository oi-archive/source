
# 题目描述

可怜有一个长度为 $n$ 的正整数序列 $A$ ,但是她觉得 $A$ 中的数字太小了,这让她很不开心。  
于是她选择了 $m$ 个区间 $[l_i , r_i]$ 和两个正整数 $a$ , $k$ 。她打算从这 $m$ 个区间里选出**恰好** $k$ 个区间,并对每个区间执行一次区间加 $a$ 的操作。
(每个区间最多只能选择一次。)  

对区间 $[l, r]$ 进行一次加 $a$ 操作可以定义为对于所有 $i \in [l, r]$ ,将 $A_i$ 变成 $A_i + a$ 。   
现在可怜想要知道怎么选择区间才能让操作后的序列的最小值尽可能的大,即最大化 $ \min \{ A_i \} $ 。  
 

# 输入格式

第一行输入一个整数表示数据组数。  
对于每组数据第一行输入四个整数 $n,m,k,a$ 。  
第二行输入 $n$ 个整数描述序列 $A$ 。  
接下来 $m$ 行每行两个整数 $l_i,r_i$ 描述每一个区间。数据保证所有区间两两不同。  


# 输出格式

对于每组数据输出一个整数表示操作后序列最小值的最大值。

# 样例

#### 样例输入
```plain
1
3 3 2 1
1 3 2
1 1
1 3
3 3
```

#### 样例输出
```plain
3
```

#### 样例解释
选择给区间 $[1, 1]$ 和 $[1, 3]$ 加 $1$ 。

# 数据范围与提示

<!-- BEGIN: Migrated markdown table -->

| 测试点编号 | $\sum n$ | $\sum m$ |
|:-:|:-:|:-:|
| $1$ | $\leq 20$ | $\leq 20$ |
| $2$ | $\leq 20$ | $\leq 20$ |
| <p> $3$ </p> | $\leq 2000$ | $\leq 2000$ |
| $4$ | $\leq 2000$ | $\leq 2000$ |
| $5$ | $\leq 2000$ | $\leq 2000$ |
| $6$ | $\leq 2000$ | $\leq 2000$ |
| $7$ | $\leq 2 \times 10^5$ | $\leq 2 \times 10^5$ |
| $8$ | $\leq 2 \times 10^5$ | $\leq 2 \times 10^5$ |
| $9$ | $\leq 2 \times 10^5$ | $\leq 2 \times 10^5$ |
| $10$ | $\leq 2 \times 10^5$ | $\leq 2 \times 10^5$ |

<!-- Migrated from original HTML table:
<table><thead>
    <tr>
     <th style='text-align:center'>测试点编号</td>
     <th style='text-align:center'> $\sum n$ </td>
     <th style='text-align:center'> $\sum m$ </td>
    </tr></thead><tbody>
    <tr>
     <td style='text-align:center'> $1$ </td>
     <td rowspan="2" style='text-align:center'> $\leq 20$ </td>
     <td rowspan="2" style='text-align:center'> $\leq 20$ </td>
    </tr>
    <tr>
     <td style='text-align:center'> $2$ </td>
    </tr>
    <tr>
     <td style='text-align:center'><p>&nbsp;$3$ </p></td>
     <td rowspan="4" style='text-align:center'> $\leq 2000$ </td>
     <td rowspan="4" style='text-align:center'> $\leq 2000$ </td>
    </tr>
    <tr>
     <td style='text-align:center'> $4$ </td>
    </tr>
    <tr>
     <td style='text-align:center'> $5$ </td>
    </tr>
    <tr>
     <td style='text-align:center'> $6$ </td>
    </tr>
    <tr>
     <td style='text-align:center'> $7$ </td>
     <td rowspan="4" style='text-align:center'> $\leq 2 \times 10^5$ </td>
     <td rowspan="4" style='text-align:center'> $\leq 2 \times 10^5$ </td>
    </tr>
    <tr>
     <td style='text-align:center'> $8$ </td>
    </tr>
    <tr>
     <td style='text-align:center'> $9$ </td>
    </tr>
    <tr>
     <td style='text-align:center'> $10$ </td>
    </tr>
   </tbody>
  </table>
-->

<!-- END: Migrated markdown table -->

