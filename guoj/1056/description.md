
# 题目描述

久莲是个爱玩的女孩子。

暑假终于到了，久莲决定请她的朋友们来游泳，她打算先在她家的私人海滩外圈一块长方形的海域作为游泳场。然而大海里有着各种各样的危险，有些地方水太深，有些地方有带毒的水母出没。她想让圈出来的这一块海域都是安全的。

经过初步分析，这块海域可视为一个底边长为 $N$ 米，高为 $1001$ 米的长方形网格。其中网格的底边对应着她家的私人海滩，每一个 $1\:\textrm{m}\times1\:\textrm{m}$ 的小正方形都代表着一个单位海域。她拜托了她爸爸明天去测量每一个小正方形是否安全。在得知了信息之后，她要做的就是圈出她想要的游泳场啦。  

她心目中理想的游泳场满足如下三个条件：
* 必须保证安全性。即游泳场中的每一个单位海域都是安全的。
* 必须是矩形。即游泳场必须是整个网格中的一个 $a\times b$ 的子网格。
* 必须和海滩相邻。即游泳场的下边界必须紧贴网格的下边界。

例如：当 $N = 5$ 时，若测量的结果如下（因为 $1001$ 太大，这儿只画出网格最下面三行的信息，其他部分都是危险的）。      

<img src="/source/guoj/1056/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTcvMDcvMjIvNTk3MmRhOTE4YWEzYy5wbmc=.png" alt="Screen Shot 2017-07-22 at 4.54.14 PM.png"  align = "center" style="display: block; margin: 0 auto;">

那么她可以选取最下面一行的 $1\times4$ 的子海域，也可以选择第三列的 $3\times1$ 的子海域。注意她不能选取最上面一行的 $1\times5$ 的子海域，因为它没有与海滩相邻。

为了让朋友们玩的开心，她想让游泳场的面积尽可能的大。因此她会选取最下面那一行的 $1\times4$ 的子海域作为最终方案。

虽然她要明天才能知道每一个单位海域是否安全，但是她现在就想行动起来估计一下她的游泳场面积有多大。经过简单的估计，她假设每一个单位海域都有独立的 $q$ 的概率是安全的，$1 − q$ 的概率是不安全的。她想要知道她能选择的最大的游泳场的面积__恰好__为 $K$ 的概率是多少。

然而久莲对数学并不感兴趣，因此她想让你来帮她计算一下这个数值。



# 输入格式

输入一行四个正整数 $N,K,x,y$，其中 $1 \leq x < y < 998244353$。$q$ 的取值为 $\frac{x}{y}$。 


# 输出格式

输出一行一个整数表示答案在模 $998244353$ 意义下的取值。

即设答案化为最简分式后的形式为 $\frac{a}{b}$ ，其中 $a$ 和 $b$ 的互质。输出整数 $x$ 使得 $bx \equiv a \mod 998244353$ 且 $0 \leq x < 998244353$。可以证明这样的整数 $x$ 是唯一的。 


# 样例

### 输入

```plain
10 5 1 2

```



### 输出

```plain
342025319

```


# 数据范围与提示

#### 提示

$x^{p-1} \equiv 1 \pmod p$，其中 $p$ 为质数，$x \in [1,p)$。

#### 子任务

 <!-- BEGIN: Migrated markdown table -->

| 测试点编号 | $N$ | $K$ |
|-|-|-|
| 1,2 | $=1$ | $\leq 1000$ |
| 3 | $\leq 10$ | $\leq 8$ |
| 4 | $\leq 10$ | $\leq 9$ |
| 5 | $\leq 10$ | $\leq 10$ |
| 6 | $\leq 1000$ | $\leq 7$ |
| 7 | $\leq 1000$ | $\leq 8$ |
| 8 | $\leq 1000$ | $\leq 9$ |
| 9,10,11 | $\leq 1000$ | $\leq 100$ |
| 12,13,14 | $\leq 1000$ | $\leq 1000$ |
| 15,16 | $\leq 10^9$ | $\leq 10$ |
| 17,18 | $\leq 10^9$ | $\leq 100$ |
| 19,20 | $\leq 10^9$ | $\leq 1000$ |

<!-- Migrated from original HTML table:
<table class="ui celled center aligned table"><thead><tr><th rowspan="1">测试点编号</th><th rowspan="1"> $N$ </th><th rowspan="1"> $K$ </th></tr></thead><tbody><tr><td rowspan="1">1,2</td><td rowspan="1"> $=1$ </td><td rowspan="1"> $\leq 1000$ </td></tr><tr><td rowspan="1">3</td><td rowspan="1"> $\leq 10$ </td><td rowspan="1"> $\leq 8$ </td></tr><tr><td rowspan="1">4</td><td rowspan="1"> $\leq 10$ </td><td rowspan="1"> $\leq 9$ </td></tr><tr><td rowspan="1">5</td><td rowspan="1"> $\leq 10$ </td><td rowspan="1"> $\leq 10$ </td></tr><tr><td rowspan="1">6</td><td rowspan="1"> $\leq 1000$ </td><td rowspan="1"> $\leq 7$ </td></tr><tr><td rowspan="1">7</td><td rowspan="1"> $\leq 1000$ </td><td rowspan="1"> $\leq 8$ </td></tr><tr><td rowspan="1">8</td><td rowspan="1"> $\leq 1000$ </td><td rowspan="1"> $\leq 9$ </td></tr><tr><td rowspan="1">9,10,11</td><td rowspan="1"> $\leq 1000$ </td><td rowspan="1"> $\leq 100$ </td></tr><tr><td rowspan="1">12,13,14</td><td rowspan="1"> $\leq 1000$ </td><td rowspan="1"> $\leq 1000$ </td></tr><tr><td rowspan="1">15,16</td><td rowspan="1"> $\leq 10^9$ </td><td rowspan="1"> $\leq 10$ </td></tr><tr><td rowspan="1">17,18</td><td rowspan="1"> $\leq 10^9$ </td><td rowspan="1"> $\leq 100$ </td></tr><tr><td rowspan="1">19,20</td><td rowspan="1"> $\leq 10^9$ </td><td rowspan="1"> $\leq 1000$ </td></tr></tbody></table>
-->

<!-- END: Migrated markdown table --> 

