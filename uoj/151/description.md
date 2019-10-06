# 题目描述

<p><strong>本题开放Hack</strong></p>
<p>牛牛最近迷上了一种叫斗地主的扑克游戏。斗地主是一种使用黑桃、红心、梅花、方片的A到K加上大小王的共54张牌来进行的扑克牌游戏。在斗地主中，牌的大小关 系根据<strong><em>牌的数码</em></strong>表示如下：$3&lt;4&lt;5&lt;6&lt;7&lt;8&lt;9&lt;10&lt;J&lt;Q&lt;K&lt;A&lt;2&lt;\text{小王}&lt;\text{大王}$，而<strong>花色并不对牌的大小产生影响</strong>。每一局游戏中，一副<strong><em>手牌</em></strong>由 $n$ 张牌组成。游戏者每次可以根据规定的<strong><em>牌型</em></strong>进行出牌，首先打光自己的手牌一方取得游戏的胜利。</p>
<p>现在，牛牛只想知道，对于自己的若干组<strong><em>手牌</em></strong>，分别最少需要多少次出牌可以将它们打光。请你帮他解决这个问题。</p>
<p>需要注意的是，本题中游戏者每次可以出手的<strong><em>牌型</em></strong>与一般的斗地主相似而略有不同。具体规则如下：</p>
<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>牌型</th><th>牌型说明</th><th>牌型举例</th></tr></thead><tbody><tr><td>火箭</td><td>即双王（双鬼牌）</td><td>♂ ♀</td></tr><tr><td>炸弹</td><td>四张同点牌。</td><td>♠A ♥A ♣A ♦A</td></tr><tr><td>单张牌</td><td>单张牌</td><td>♠3</td></tr><tr><td>对子牌</td><td>两张码数相同的牌</td><td>♠2 ♥2</td></tr><tr><td>三张牌</td><td>三张码数相同的牌</td><td>♠3 ♥3 ♣3</td></tr><tr><td>三带一</td><td>三张码数相同的牌 + 一张单牌</td><td>♠3 ♥3 ♣3 ♠4</td></tr><tr><td>三带二</td><td>三张码数相同的牌 + 一对牌</td><td>♠3 ♥3 ♣3 ♠4 ♥4</td></tr><tr><td>单顺子</td><td>五张或更多码数连续的单牌（不包括 2 点和双王）</td><td>♠7 ♣8 ♠9 ♣10 ♣J</td></tr><tr><td>双顺子</td><td>三对或更多码数连续的对牌（不包括 2 点和双王）</td><td>♣3 ♥3 ♠4 ♥4 ♠5 ♥5</td></tr><tr><td>三顺子</td><td>二个或更多码数连续的三张牌（不能包括 2 点和双王）</td><td>♠3 ♥3 ♣3 ♠4 ♥4 ♣4 ♠5 ♦5 ♥5</td></tr><tr><td>四带二</td><td>四张码数相同的牌+任意两张单牌（或任意两对牌）</td><td>♠5 ♥5 ♣5 ♦5 ♣3 ♣8</td></tr></tbody></table></div>

<p><strong>在此题中认为两个王不能组成对子牌</strong></p>

# 输入格式


<p>第一行包含用空格隔开的2个正整数 $T,n$ ，表示手牌的组数以及每组手牌的张数。</p>
<p>接下来 $T$ 组数据，每组数据 $n$ 行，每行一个非负整数对 $a_i,b_i$ ，表示一张牌，其中 $a_i$ 表示牌的数码， $b_i$ 表示牌的花色，中间用空格隔开。特别的，我们用 $1$ 来表示数码 A， $11$ 表示数码 J， $12$ 表示数码 Q， $13$ 表示数码 K；黑桃、红心、梅花、方片分别用 <samp>1-4</samp> 来表示；小王的表示方法为 <samp>0 1</samp> ，大王的表示方法为 <samp>0 2</samp> 。</p>

# 输出格式


<p>共 $T$ 行，每行一个整数，表示打光第 $i$ 组手牌的最少次数。</p>

# 样例一


<h4>input</h4>
<pre>1 8
7 4
8 4
9 1
10 4
11 1
5 1
1 4
1 1

</pre>

<h4>output</h4>
<pre>3

</pre>

<h4>explanation</h4>
<p>共有 $1$ 组手牌，包含 $8$ 张牌：方片 7，方片 8，黑桃 9，方片 10，黑桃 J，黑桃 5，方片 A以及黑桃 A。可以通过打单顺子（方片 7，方片 8，黑桃 9，方片 10，黑桃 J），单张牌（黑桃 5）以及对子牌（黑桃 A以及方片 A）在 $3$ 次内打光。</p>

# 样例二


<h4>input</h4>
<pre>1 17
12 3
4 3
2 3
5 4
10 2
3 3
12 2
0 1
1 3
10 1
6 2
12 1
11 3
5 2
12 4
2 2
7 2

</pre>

<h4>output</h4>
<pre>6

</pre>



# 数据规模与约定


<p>对于不同的测试点，我们约定手牌组数 $T$ ，与张数 $n$ 的规模如下:</p>
<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$T$ 的规模</th><th>$n$ 的规模</th><th>测试点编号</th><th>$T$ 的规模</th><th>$n$ 的规模</th></tr></thead><tbody><tr><td>1</td><td>$100$</td><td>$2$</td><td>11</td><td>$100$</td><td>$14$</td></tr><tr><td>2</td><td>$100$</td><td>$2$</td><td>12</td><td>$100$</td><td>$15$</td></tr><tr><td>3</td><td>$100$</td><td>$3$</td><td>13</td><td>$10$</td><td>$16$</td></tr><tr><td>4</td><td>$100$</td><td>$3$</td><td>14</td><td>$10$</td><td>$17$</td></tr><tr><td>5</td><td>$100$</td><td>$4$</td><td>15</td><td>$10$</td><td>$18$</td></tr><tr><td>6</td><td>$100$</td><td>$4$</td><td>16</td><td>$10$</td><td>$19$</td></tr><tr><td>7</td><td>$100$</td><td>$10$</td><td>17</td><td>$10$</td><td>$20$</td></tr><tr><td>8</td><td>$100$</td><td>$11$</td><td>18</td><td>$10$</td><td>$21$</td></tr><tr><td>9</td><td>$100$</td><td>$12$</td><td>19</td><td>$10$</td><td>$22$</td></tr><tr><td>10</td><td>$100$</td><td>$13$</td><td>20</td><td>$10$</td><td>$23$</td></tr></tbody></table></div>

<p><strong>手牌不一定是随机生成的</strong></p>
<p><strong>在此题中认为两个王不能组成对子牌</strong></p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$1\texttt{GB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=151">样例数据下载</a></p>
