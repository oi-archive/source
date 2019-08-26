
# 题目描述

**原版见 [LOJ #6185](https://loj.ac/problem/6185)**  
众所周知，大连 24 中是一所神奇的学校，在那里，化竞的同学很多都擅长写代码。

有一天，化学不及格的胡小兔向化竞巨佬晴岚请教化学题：

**「$n$ 个碳原子的烷基共有多少种同分异构体？」**

刚刚得了化竞全市第一的晴岚听了，认为这道题十分简单，建议胡小兔写个程序解决这个问题。但胡小兔弱得连什么是同分异构体都不知道，于是晴岚给胡小兔画了个图——例如 $n = 4$ 时（即丁基），有 $4$ 种同分异构体：

![chem.png](source/loj/6538/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNC8wMi81Y2EyZjY1NDgyNjYzLnBuZw==.png)

同理，其他常见烷基同分异构体数目如下表：

<!-- BEGIN: Migrated markdown table -->

|$n$|同分异构体数目|
|:-:|:-:|
|$1$|<!--qwq-->$1$|
|$2$|<!--quq-->$1$|
|$3$|$2$|
|$4$|<!--quq-->$4$|
|$5$|$8$|
|$6$|$17$|

<!-- Migrated from original HTML table:
<table class="ui center aligned definition table">
        <tbody>
            <tr>
                <td style="width: 20%; ">
                    $ n $
                </td>
                <td>
                    $ 1 $
                </td>
                <td>
                    $ 2 $
                </td>
                <td>
                    $ 3 $
                </td>
                <td>
                    $ 4 $
                </td>
                <td>
                    $ 5 $
                </td>
                <td>
                    $ 6 $
                </td>
            </tr>
            <tr>
                <td>
                    同分异构体数目
                </td>
                <td>
                    $ 1 $
                </td>
                <td>
                    $ 1 $
                </td>
                <td>
                    $ 2 $
                </td>
                <td>
                    $ 4 $
                </td>
                <td>
                    $ 8 $
                </td>
                <td>
                    $ 17 $
                </td>
            </tr>
        </tbody>
    </table>
-->

<!-- END: Migrated markdown table -->

现在已知碳原子个数 $n$，求对应的烷基有多少种同分异构体。

注意：这里的烷基计数不用考虑空间异构，能否稳定存在等各种特殊情况。也就是说，你要求的是 $n$ **个点的每个点度数不超过 $4$ 且根的度数不超过 $3$ 的有根树的数目。**

P.S. 2017.11.30 更新：化竞巨佬晴岚高二进国集保送北大了……

# 输入格式

输入一行，一个整数 $ n $，表示烷基中碳原子的数目。

# 输出格式

作为良心出题人，本题只要求输出该烷基同分异构体的数目 $\text{mod}\;998244353$。

# 样例

#### 样例输入
```plain
6
```

#### 样例输出
```plain
17
```

# 数据范围与提示

$1\le n\le 10^5$  



