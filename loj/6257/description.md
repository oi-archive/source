
# 题目描述

“codeplus比赛的时候在做什么？有没有空？能来解决丢番图方程问题吗？”sublinekelzrip这样问qmqmqm。

当然，qmqmqm并不会丢番图方程问题，所以sublinekelzrip改为提出了另一个题目，现在请你帮助qmqmqm解决这个题目。

<hr style='color: #ddd; margin-bottom: 1em'>

这个问题是这样的：

若一个数列$a$满足条件$a_n=a_{n-1}+a_{n-2},n \geq 3$,而$a_1,a_2$为任意实数，则我们称这个数列为广义斐波那契数列。

现在请你求出满足条件$a_1=i$，$a_2$为区间$[l,r]$中的整数，且$a_k \bmod p=m$的广义斐波那契数列有多少个。

# 输入格式

从标准输入读入数据。

本题包含多组数据，输入第一行包含一个正整数$T$，表示数据组数。对于每组数据：

一行六个用空格隔开的整数$i,l,r,k,p,m$，意义如「题目描述」所示。

# 输出格式

输出到标准输出。

输出共$T$行，每行一个数表示该组数据的答案。

# 样例

##### 样例输入

```plain
6
2 17 68 3 23 1
1 17 68 3 57 1
5 17 68 10 11 9
5 17 68 10 71 9
10 17 68 11 12 3
10 17 68 8 6 4

```

##### 样例输出

```plain
3
1
4
1
5
9

```

# 数据范围与提示

<!-- BEGIN: Migrated markdown table -->

| 测试点 | $k$ | $r$ | 其他 |
|-|-|-|-|
| 1 | $\leq 100$ | $\leq 100$ | 无 |
| 2 | $\leq 10^5$ | $\leq 10^5$ | 无 |
| 3 | $\leq 10^5$ | $\leq 10^5$ | 无 |
| 4 | $\leq 10^{18}$ | $\leq 10^5$ | 无 |
| 5 | $\leq 10^{18}$ | $\leq 10^5$ | 无 |
| 6 | $\leq 10^5$ | $\leq 10^{18}$ | $p$为质数 |
| 7 | $\leq 10^5$ | $\leq 10^{18}$ | $p$为质数 |
| 8 | $\leq 10^{18}$ | $\leq 10^{18}$ | $p$为质数 |
| 9 | $\leq 10^{18}$ | $\leq 10^{18}$ | 无 |
| 10 | $\leq 10^{18}$ | $\leq 10^{18}$ | 无 |

<!-- Migrated from original HTML table:
<table class="ui center aligned celled table"><thead><tr><th rowspan="1">测试点</th><th rowspan="1">$k$ </th><th rowspan="1">$r$ </th><th rowspan="1">其他</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">$\leq 100$ </td><td rowspan="1">$\leq 100$ </td><td rowspan="5">无</td></tr><tr><td rowspan="1">2</td><td rowspan="2">$\leq 10^5$ </td><td rowspan="4">$\leq 10^5$ </td></tr><tr><td rowspan="1">3</td></tr><tr><td rowspan="1">4</td><td rowspan="2">$\leq 10^{18}$ </td></tr><tr><td rowspan="1">5</td></tr><tr><td rowspan="1">6</td><td rowspan="2">$\leq 10^5$ </td><td rowspan="5">$\leq 10^{18}$ </td><td rowspan="3">$p$为质数</td></tr><tr><td rowspan="1">7</td></tr><tr><td rowspan="1">8</td><td rowspan="3">$\leq 10^{18}$ </td></tr><tr><td rowspan="1">9</td><td rowspan="2">无</td></tr><tr><td rowspan="1">10</td></tr></tbody></table>
-->

<!-- END: Migrated markdown table --> 

对于所有数据，$0 \leq l \leq r$,$1 \leq p \leq 10^9$,$0 \leq m < p$,$T=10$,$0 \leq i \leq 10^{18}$,$k \geq 3$。

<hr style='color: #ddd; margin-bottom: 1em'>

来自 CodePlus 2017 12 月赛，清华大学计算机科学与技术系学生算法与竞赛协会 荣誉出品。  
Credit：idea/卢政荣　命题/卢政荣　验题/吕时清，茹逸中，王聿中  
Git Repo：https://git.thusaac.org/publish/CodePlus201712  
感谢腾讯公司对此次比赛的支持。

