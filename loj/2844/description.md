
# 题目描述

**译自 [ROI 2018](http://neerc.ifmo.ru/school/archive/2017-2018.html) Day1 T2.** ***[Вирусы](http://neerc.ifmo.ru/school/archive/2017-2018/ru-olymp-roi-2018-day1.pdf) ([Viruses](http://codeforces.com/gym/102147/problem/D))***

现在有 $n$ 只使魔与 $n$ 个饲主，$i$ 号使魔的初始饲主的序号也为 $i$ ，每个使魔心中对每位饲主都有一定的好感度。

使魔之间可以互相攻击，如果使魔甲攻击了使魔乙，且乙「对甲现在的饲主的好感度」比「对自家饲主的好感度」高，那么乙就会被甲的饲主拐走。

使魔们可以任意安排攻击顺序。当且仅当没有使魔可以被任意一名饲主拐走时，游戏宣告结束。

如果存在一种攻击顺序，使得饲主 $i$ 最终拥有一只或以上的使魔，那么我们则称饲主 $i$ 为「有希望的」。  
如果对于任意一种攻击顺序，都使得饲主 $i$ 最终拥有一只或以上的使魔，那么我们则称饲主 $i$ 为「人生赢家」。

现在饲主们想知道，有多少个有希望的饲主与人生赢家。

# 输入格式

第一行一个正整数 $n$ ，表示使魔与饲主的数量。

下面 $n$ 行，每行一个 $n$ 个正整数，表示每名饲主按当前使魔心中的好感度降序排列后的饲主编号序列。

比如输入了 $\texttt{2 1 3}$，则表示该使魔对 $2$ 号饲主的好感度最高，对 $1$ 号饲主的好感度第二高，对 $3$ 号饲主的好感度最差。

最后一行一个整数 $p$ 。

# 输出格式

第一行，一个整数 $x$ 。如果 $p=1$ ，输出人生赢家的数量；如果 $p=2$ ，输出有希望的饲主的数量。

下面一行， $x$ 个整数，表示这 $x$ 个饲主的编号，按升序排列。

# 样例

<table class="ui very basic table">
<thead>
<tr>
<th></th>
<th>1</th>
<th>2</th>
<th>3</th>
<th>4</th>
<th>5</th>
<th>6</th>
<th>7</th>
<th>8</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>输入</strong></td>
<td><div class="ui existing segment"><pre style="margin-top: 0; margin-bottom: 0; "><code>2<br>1 2<br>2 1<br>1</code></pre></div></td>
<td><div class="ui existing segment"><pre style="margin-top: 0; margin-bottom: 0; "><code>2<br>1 2<br>2 1<br>2</code></pre></div></td>
<td><div class="ui existing segment"><pre style="margin-top: 0; margin-bottom: 0; "><code>2<br>2 1<br>1 2<br>1</code></pre></div></td>
<td><div class="ui existing segment"><pre style="margin-top: 0; margin-bottom: 0; "><code>2<br>2 1<br>1 2<br>2</code></pre></div></td>
<td><div class="ui existing segment"><pre style="margin-top: 0; margin-bottom: 0; "><code>2<br>1 2<br>1 2<br>1</code></pre></div></td>
<td><div class="ui existing segment"><pre style="margin-top: 0; margin-bottom: 0; "><code>2<br>1 2<br>1 2<br>2</code></pre></div></td>
<td><div class="ui existing segment"><pre style="margin-top: 0; margin-bottom: 0; "><code>4<br>3 2 4 1<br>1 4 2 3<br>3 1 2 4<br>1 4 2 3<br>1</code></pre></div></td>
<td><div class="ui existing segment"><pre style="margin-top: 0; margin-bottom: 0; "><code>4<br>3 2 4 1<br>1 4 2 3<br>3 1 2 4<br>1 4 2 3<br>2</code></pre></div></td>
</tr>
<tr>
<td><strong>输出</strong></td>
<td><div class="ui existing segment"><pre style="margin-top: 0; margin-bottom: 0; "><code>2<br>1 2</code></pre></div></td>
<td><div class="ui existing segment"><pre style="margin-top: 0; margin-bottom: 0; "><code>2<br>1 2</code> </pre></div></td>
<td><div class="ui existing segment"><pre style="margin-top: 0; margin-bottom: 0; "><code>0</code></pre></div></td>
<td><div class="ui existing segment"><pre style="margin-top: 0; margin-bottom: 0; "><code>2<br>1 2</code></pre></div></td>
<td><div class="ui existing segment"><pre style="margin-top: 0; margin-bottom: 0; "><code>1<br>1</code></pre></div></td>
<td><div class="ui existing segment"><pre style="margin-top: 0; margin-bottom: 0; "><code>1<br>1</code> </pre></div></td>
<td><div class="ui existing segment"><pre style="margin-top: 0; margin-bottom: 0; "><code>1<br>3</code></pre></div></td>
<td><div class="ui existing segment"><pre style="margin-top: 0; margin-bottom: 0; "><code>3<br>1 3 4</code></pre></div></td>
</tr>
</tbody>
</table>

# 数据范围与提示

|任务编号|$n$|$p$|分值|
|:-:|:-:|:-:|:-:|
|$1$|$1 \leq n \leq 5$|$p=1$|$11$|
|$2$|$1 \leq n \leq 500$|$p=1$|$21$|
|$3$|$1 \leq n \leq 5$|$p=1,2$|$22$|
|$4$|$1 \leq n \leq 50$|$p=1,2$|$31$|
|$5$|$1 \leq n \leq 500$|$p=1,2$|$15$|

> 修题者：由于原译者好这口，所以上面的是魔改版题面。  
> 原文标题：病毒  
> 原文用语：使魔 -> 细胞，饲主 -> 病毒，好感度 -> 易感染度（一种细胞是否容易被某种病毒感染），有希望的 -> 可行的，人生赢家 -> 稳定的。  

