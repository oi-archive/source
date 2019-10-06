# 题目描述

<p>Evan 和 Lyra 都是聪明可爱的孩子，两年前，Evan 开始为一个被称为UOJ的神秘的OI组织工作，在 Evan 与其他小伙伴的努力下，UOJ不仅成了OI界原创比赛的典范，更是因UR这一反人类难度的存在而举世闻名。然而今年，随着 Evan 前往世界彼岸，UOJ一天天减少着他的活力，而就在OI历新年的黎明——NOI的前夕，刚回家不久的Evan听到了清脆的敲门声……</p>
<p>“开门，快递！”</p>
<p>“暗号？”</p>
<p>“3a34be41f8c8796c93b5c9f3b988e0d4”</p>
<p>“收到！”</p>
<p>送走了快递小哥，Evan 拆开包裹，看见一个写着“量子态的巧克力”的小盒子，作为新时代的OI少年，Evan 决定发扬分享的精神，于是他找来 Lyra 一起打开巧克力的盒子。</p>
<p>“砰——”</p>
<p>从量子态坍缩的光芒中回过神来，感受到脚下啫喱状的地板，Evan 叹了一口气——接着突然用把 Lyra 吓了一跳的音量喊了出来：</p>
<p>“竟然把造题的锅塞进巧克力里！！”</p>
<p>而这时，Lyra已经开始观察起了这盒奇特的巧克力，并找到了藏在巧克力盒子里的说明书。</p>
<p>原来，盒子里每个巧克力都有一个味道 $a_i$，Evan 和 Lyra 的舌头上都还没有残留任何味道（用 $0$ 表示），当他们吃下一块巧克力的时候，舌头上的味道 $b$ 便会异或上这个巧克力的美味值，即 $b \leftarrow b ~ \texttt{xor} ~ a$. </p>
<p>Evan 和 Lyra 会各自从盒子中拿一些巧克力吃下去（即各自选择一个集合并吃掉集合中的巧克力），两个人不能吃同一块巧克力（即集合不能相交），可以有一个人选择不吃巧克力，但不能两个人都不吃。Evan 和 Lyra 不需要把盒子里的巧克力都吃完，有剩余也是可以的。</p>
<p>最后如果二人舌头上残留着相同的味道，则称两人是心情契合的。</p>
<p>既然量子态有无数种可能性，走出这巧克力迷局的关键就是，求出有多少种方案使得两人是心情契合的，两种方案不同当且仅当 Evan 或 Lyra 选择吃下的巧克力集合不一样。</p>
<p>你只需要输出方案数对 $998244353$ 取模的结果即可。</p>

# 输入格式


<p>第一行一个正整数 $n$ ，表示巧克力的个数。</p>
<p>第二行 $n$ 个整数 $a_i$ 表示每个巧克力的美味值。</p>

# 输出格式


<p>输出一行一个整数，表示能使得他们心情契合的吃巧克力的方案数对 $998244353$ 取模的结果。</p>

# 样例一


<h4>input</h4>
<pre>3
1 2 3

</pre>

<h4>output</h4>
<pre>8

</pre>


# explanation


<p>无论 Evan 选哪个集合，Lyra 都要选 Evan 的补集。</p>

# 样例二


<h4>input</h4>
<pre>6
1 2 3 4 5 6

</pre>

<h4>output</h4>
<pre>80

</pre>


# 样例三


<p>见样例数据下载，限制与约定跟第 $7$ 个测试点相同。</p>

# 样例四


<p>见样例数据下载，限制与约定跟第 $8$ 个测试点相同。</p>

# 限制与约定


<p>对于全部数据，$1 \leq n \leq 10^6; 0 \leq a_i \leq 10^6.$</p>
<p>各个测试点限制见下表：</p>
<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$</th><th>$a_i$</th></tr></thead><tbody><tr><td>1</td><td rowspan="1">$\leq 15$</td><td rowspan="3">$ \leq 10^6$</td></tr><tr><td>2</td><td rowspan="2">$\leq 25$</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="3">$\leq 10^3$</td><td rowspan="3">$ \leq 10^4$</td></tr><tr><td>5</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="4">$ \leq 10^6$</td><td rowspan="1">$ = 2^k (0 \leq k \leq 18)$</td></tr><tr><td>8</td><td rowspan="1">$ \leq 10^6$，且至多只有$50$个不同的取值</td></tr><tr><td>9</td><td rowspan="2">$ \leq 10^6$，且至多只有$1000$个不同的取值</td></tr><tr><td>10</td></tr><tr><td>11</td><td rowspan="10"> $\leq 10^6$ </td><td rowspan="3">$ \leq 3 \times 10^4$</td></tr><tr><td>12</td></tr><tr><td>13</td></tr><tr><td>14</td><td rowspan="3">$ \leq 2 \times 10^5$</td></tr><tr><td>15</td></tr><tr><td>16</td></tr><tr><td>17</td><td rowspan="4">$ \leq 10^6$</td></tr><tr><td>18</td></tr><tr><td>19</td></tr><tr><td>20</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=310">样例数据下载</a></p>
