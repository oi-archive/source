
# 题目描述

广场站着一排人，在观看着挟持小男孩的愤怒司教的演说，一共有 $n$ 个，编号为 $1$ 到 $n$ ，第 $i$ 个人的编号为 $i$ 。  
第 $i$ 个人，有一个恐惧程度值为 $a_i$ 。如果 $[l,r]$ 的人被愤怒司教使用权能链接，那么对于 $l\leq i\leq j\leq r$ ，便会产生 $(\sum_{i=l}^{r}{a_i}) \bmod p$ 那么多的恐惧总值，其中 $p$ 是给定的一个常数。  
为了更好的应战愤怒司教，现在有 $q$ 个询问，每个询问给定区间 $[l,r]$ ，请你找出对于任意 $l\leq i\leq j\leq r$ ， $[i,j]$ 产生恐惧总值的最小值。

# 输入格式

第一行两个正整数表示 $n$，$p$ 。  
接下来一行，$n$ 个整数，表示序列 $a$ 。  
接下来一行一个正整数表示询问个数 $q$ 。  
接下来 $q$ 行，每行两个正整数 $l$，$r$ 表示一次询问。

# 输出格式

 $q$ 行每行一个整数表示答案。

# 样例

#### 样例输入 
```plain
3 3
1 1 2
3
1 2
2 3
3 3 
```

#### 样例输出 
```plain
1
0
2
```

# 数据范围与提示

- 对于 $100\%$ 的数据， $2 \leq p \leq n $  。  
- 所有 $a_i$ 均在 $[0,p-1]$ 中等概率随机生成。  
- 每个测试点有一个对应的常数 $len$ ，对于每组询问，其有 $\frac{3}{4}$ 的概率满足条件 $1$ ，$\frac{1}{4}$ 的概率满足条件 $2$。  
    - 条件 $1$ ：被询问区间的区间大小 $\leq len$。
    - 条件 $2$ ：被询问区间的区间大小$\gt len$。  
- 被询问区间的区间大小 $x$ 在满足条件情况下等概率随机生成，然后等概率随机生成符合条件的右端点，相减得到左端点。
<!-- BEGIN: Migrated markdown table -->

| 子任务 | 分值 | $n$ | $q$ | $len$ |
|:-:|:-:|:-:|:-:|:-:|
| 1 | 40 | $n\leq 50$ | $q\leq 50$ | $len=\frac{3}{4}n$ |
| 2 | 20 | $n\leq 100$ | $q\leq 100$ | $len=\frac{3}{4}n$ |
| 3 | 10 | $n\leq 1000$ | $q\leq 2000$ | $len=\frac{3}{4}n$ |
| 4 | 10 | $n\leq 200000$ | $q\leq 2000$ | $len=2650$ |
| 5 | 5 | $n\leq 2000000$ | $q\leq 2000$ | $len=8500$ |
| 6 | 15 | $n\leq 6000000$ | $q\leq 2000$ | $len=14500$ |

<!-- Migrated from original HTML table:
<table border="1" align="center" width="50%" class="table table-bordered table-condensed">

    <tr>
    	<th width="20%" style="text-align: center;">子任务</th>
    	<th width="20%" style="text-align: center;">分值</th>
        <th width="20%" style="text-align: center;">$n$ </th>
    	<th width="20%" style="text-align: center;">$q$ </th>
        <th width="20%" style="text-align: center;">$len$ </th>
    </tr>
    <tr>
        <td style="text-align: center;">1</td>
        <td style="text-align: center;">40</td>
        <td style="text-align: center;">$n\leq 50$ </td>
        <td style="text-align: center;">$q\leq 50$ </td>
        <td style="text-align: center;"rowspan="3">$len=\frac{3}{4}n$ </td>
    </tr>
    <tr>
        <td style="text-align: center;">2</td>
        <td style="text-align: center;">20</td>
        <td style="text-align: center;">$n\leq 100$ </td>
        <td style="text-align: center;">$q\leq 100$ </td>
    </tr>
    <tr>
        <td style="text-align: center;">3</td>
        <td style="text-align: center;">10</td>
        <td style="text-align: center;">$n\leq 1000$ </td>
        <td style="text-align: center;"rowspan="4">$q\leq 2000$ </td>
    </tr>
    <tr>
        <td style="text-align: center;">4</td>
        <td style="text-align: center;">10</td>
        <td style="text-align: center;">$n\leq 200000$ </td>
        <td style="text-align: center;">$len=2650$ </td>
    </tr>
<tr>
        <td style="text-align: center;">5</td>
        <td style="text-align: center;">5</td>
        <td style="text-align: center;">$n\leq 2000000$ </td>
        <td style="text-align: center;">$len=8500$ </td>
    </tr>
<tr>
        <td style="text-align: center;">6</td>
        <td style="text-align: center;">15</td>
        <td style="text-align: center;">$n\leq 6000000$ </td>
        <td style="text-align: center;">$len=14500$ </td>
    </tr>

</table>
-->

<!-- END: Migrated markdown table -->  


