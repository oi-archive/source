
# 题目描述

> 「Mix it well!」
>
> 对于 Alice 来说，与 Shinobu 的初识，以及一同制作的曲奇饼，都将是她永远珍藏的回忆。
>
> 而 Shinobu 对于外国文化的强烈憧憬总能使她与 Alice 找到更多新奇的活动 —— 这次，是来自邻居国度的「花煎游戏」。
>
> 「花煎」来自于朝鲜半岛传统，以米饼上放置可食用的时花制成，而「花煎游戏」是指郊游踏青时采花制作花煎的活动，后来渐渐与源自中国的「重阳」习俗结合。
>
> 两人很快便兴致勃勃地开始了制作，不过 Alice 似乎很想在 Shinobu 面前展示自己最好的一面……
>
> Alice 希望将自己制作的所有花煎摆成一个圆环形，并且使它们的色彩尽可能地丰富。由于 Alice 还要忙着制作，所以她把问题进行了一些抽象，希望擅长程序设计的你可以为她解决。

一个环由 $n$ 个元素组成，顺时针标号为 $1$ 至 $n$，其中 $n$ 为**不小于 $\mathbf{4}$ 的偶数**。每个元素都有一个颜色，且第 $i$ 个元素的颜色居下列二者之一：
1. 除元素 $i$ 外的其他元素均与 $i$ 不同色，Alice 称元素 $i$ 为「独立」的；
2. 除元素 $i$ 外有且仅有元素 $i + \frac n 2$ 或 $i - \frac n 2$（其中恰有一个在编号范围内）与 $i$ 同色，Alice 称元素 $i$ 为「对立」的。

定义一个环的**色彩值**为**所有被「对立」元素分开的子段的长度乘积**。换言之，将所有的「对立」元素移除，色彩值等于剩余的环上连续子段（包括长度为 $0$ 的子段 —— 出现在两个「对立」元素相邻的情况下）的长度乘积。特别地，如果环上没有「对立」元素，那么其色彩值为 $0$。

<center><img alt='legend_scaled.png' src="/source/loj/533/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTcvMTAvMjEvNTllYWNiNDUzMTg2ZC5wbmc=.png" width='300px' /></center>
<div style='text-align: center; color: #999'>
    一个 <img src="/source/loj/533/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNC8zMC81Y2M3ZmExYWQzNDU2LnN2Zw==.svg" alt="svg_n_18.svg" title="svg_n_18.svg" /> 的例子。移除「对立」元素后剩余的子段有 <img width=20% src="/source/loj/533/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNC8zMC81Y2M3ZmI4NDZkMGMxLnN2Zw==.svg" alt="svg_longf_.svg" title="svg_longf_.svg" />，其色彩值为 <img src="/source/loj/533/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNC8zMC81Y2M3ZmExOWViYTY1LnN2Zw==.svg" alt="svg_multi.svg" title="svg_multi.svg" />。


有些颜色似乎很像…… 不过确实是不同的。
</div>




<br>
现在 Alice 想获得一个色彩值**不小于** $m$ 的环。Alice 想请你帮忙计算这样一个环的最小大小 —— Alice 仍旧犹豫不定，因此你需要对于 $T$ 个这样的 $m$ 分别进行计算。

# 输入格式

输入的第一行包含一个正整数 $T$ —— 需要计算的 $m$ 的个数。

接下来 $T$ 行，每行包含一个正整数 $k$ —— 由于 $m$ 可能很大，输入的值表示它的**正平方根**，即 $m = k^2$。

# 输出格式

输出 $T$ 行 —— 对于每个输入的 $k$ 输出一行，包含一个整数，表示色彩值不小于 $k^2$ 的环最少包含的元素个数。当然啦，一定是个偶数。

# 样例

#### 样例输入
```plain
4
5
10
221
1317
```

#### 样例输出
```plain
12
18
40
54
```

#### 样例解释

<center><img alt='sample_1_scaled.png' src='https://i.loli.net/2017/10/21/59eae33ebe668.png' width='300px' /></center>
<br>
<div style='text-align: center; color: #999'><img src="/source/loj/533/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNC8zMC81Y2M3ZmExOThhNzEyLnN2Zw==.svg" alt="svg_k5.svg" title="svg_k5.svg" /> 即 
<img src="/source/loj/533/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNC8zMC81Y2M3ZmExOTRmMjcwLnN2Zw==.svg" alt="svg_m25.svg" title="svg_m25.svg" />。</div>

<br>

<center><img alt='sample_2_scaled.png' src="/source/loj/533/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTcvMTAvMjEvNTllYWUzM2VjNWUzZi5wbmc=.png" width='300px' /></center>
<br>
<div style='text-align: center; color: #999'>
<img src="/source/loj/533/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNC8zMC81Y2M3ZmExYTg5M2E3LnN2Zw==.svg" alt="svg_k10.svg" title="svg_k10.svg" /> 即 
<img src="/source/loj/533/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNC8zMC81Y2M3ZmExOWMwZjhlLnN2Zw==.svg" alt="svg_m100.svg" title="svg_m100.svg" />。如果能看见这个色彩值为 <img src="/source/loj/533/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNC8zMC81Y2M3ZmE4MzdkNzU5LnN2Zw==.svg" alt="svg_144.svg" title="svg_144.svg" /> 的环，Shinobu 会不会对 Alice 更加欣赏呢 (๑´ω\`๑)</div>

# 数据范围与提示

对于所有数据，有 $1 \leq k \leq 10^{18}$，$1 \leq T \leq 10^6$。

| Subtask # | 分值 | $k$ 的限制 | $T$ 的限制 |
|:--:|:--:|:--:|:--:|
| 1 | $25$ | $k \leq 10$ | $T \leq 10$ |
| 2 | $25$ | $k \leq 500$ | $T \leq 10$ |
| 3 | $15$ | $k \leq 5000$ | $T \leq 10^4$ |
| 4 | $15$ | $k \leq 10^{18}$，且 $k = 2^e$，其中 $e$ 为正整数 | $T \leq 10^4$ |
| 5 | $15$ | $k \leq 10^{18}$ | $T \leq 10^4$ |
| 6 | $5$ | $k \leq 10^{18}$ | $T \leq 10^6$ |

