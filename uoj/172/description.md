# 题目描述

<p>这是一个美好的下午，小 W 和小 C 在竹林里切磋捆竹竿的技艺。</p>
<p>竹林里有无数根完全一样的短竹子，每一根竹子由 $n$ 节组成。</p>
<p>这些竹子比较特别，每一节都被染上了颜色。可能的颜色一共 $26$ 种，分别用小写英文字母 <samp>a</samp> 到 <samp>z</samp> 表示。也就是说，如果把竹子的底端到顶端的颜色按顺序写出来可以排成一个由小写英文字母组成的字符串。</p>
<p>小 W 和小 C 都是捆竹竿的高手，他们知道怎样才能把零散的短竹子捆成一整根长竹竿。初始时你拿着一根短竹子作为当前的竹竿。每次你可以选择一根短竹子，短竹子底端若干节（可以是 $0$ 节）与竹竿的最上面若干节对应地一节一节捆起来，而短竹子前面剩下的节伸出去，这样就得到了一根更长的竹竿。注意，竹子的底端是靠近根部的那一端，不可以颠倒。</p>
<p>小 W 对竹竿的审美要求很高，他捆竹竿时有一个癖好：如果两根竹子的某两节被捆在了一起，那么它们的颜色必须相同。</p>
<p>我们假设一根短竹子从底端到顶端每节的颜色为 <samp>aba</samp>。</p>
<p>那么两根竹子可以首尾捆在一起，可以得到一根颜色为 <samp>abaaba</samp> 的竹竿；也可以将第一根顶端的一节 <samp>a</samp> 与第二根底端的一节 <samp>a</samp> 捆在一起，得到一根颜色为 <samp>ababa</samp> 的竹竿；还可以直接将每一节都对应起来，捆成一根颜色为 <samp>aba</samp> 的竹竿。</p>
<p>假设我们在颜色为 <samp>ababa</samp> 的竹竿顶端再捆一根竹子，则可以捆成 <samp>ababaaba</samp>，<samp>abababa</samp> 和 <samp>ababa</samp> 三种不同的情况。</p>
<p>但是小 C 在这个问题上有不同的看法，他认为小 W 捆不出很多种长度不同的竹竿。小 W 非常不服，于是他找到了你——现在请你求出在竹竿长度不超过 $w$ 的情况下，小 W 可以捆出多少种长度不同的竹竿。其中，竹竿的长度指从底端到顶端的竹子的节的个数。</p>
<p>注意：如果 $w &lt; n$，则没有合法的长度，此时答案为 $0$。</p>

# 输入格式


<p>第一行包含 $1$ 个正整数 $T$，为数据组数。</p>
<p>每组数据的第一行包含 $2$ 个正整数 $n$ 和 $w$，表示短竹子的长度和竹竿的长度上限。</p>
<p>每组数据的第二行包含一个长度为 $n$ 的字符串，该字符串仅由小写英文字母构成，表示短竹子从底端到顶端每节的颜色。</p>

# 输出格式


<p>输出共 $T$ 行，每行包含一个整数表示捆成竹竿的不同长度种数。</p>

# 样例一


<h4>input</h4>
<pre>1
4 11
bbab

</pre>

<h4>output</h4>
<pre>5

</pre>

<h4>explanation</h4>
<p>可以捆成长度不超过 $11$ 的竹竿有 $6$ 种不同的情况:</p>
<ol><li><samp>bbab</samp></li>
<li><samp>bbabbab</samp></li>
<li><samp>bbabbbab</samp></li>
<li><samp>bbabbabbab</samp></li>
<li><samp>bbabbabbbab</samp></li>
<li><samp>bbabbbabbab</samp></li>
</ol><p>后两种竹竿长度相同,因此不同长度的竹竿共有 $5$ 种。长度分别为：$4, 7, 8, 10, 11$。</p>

# 样例二


<h4>input</h4>
<pre>2
44 1000
baaaaaabaabbaaabbbbabbbaaabbbababaaabaaabaaa
41 1000
abaabbabaaabaabbbbbbbbbbbababbbbaaabaabbb

</pre>

<h4>output</h4>
<pre>195
24

</pre>


# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<p>对于所有的测试数据,保证所有的字符串均由小写字母构成，保证 $T = 5$。</p>
<p>各测试点满足以下约定：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$w$</th>
<th>约束</th>
</tr></thead><tbody><tr><td>1</td><td>$\leq 10$</td><td>$\leq 10$</td><td rowspan="2">$s$ 仅包含字母 <samp>a</samp> 和 <samp>b</samp></td></tr><tr><td>2</td><td>$\leq 20$</td><td>$\leq 20$</td></tr><tr><td>3</td><td rowspan="2">$\leq 100$</td><td rowspan="4">$\leq 10^{18}$</td><td rowspan="18">无</td></tr><tr><td>4</td></tr><tr><td>5</td><td rowspan="2">$\leq 10^3$</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="4">$\leq 5 \times 10^4$</td><td rowspan="4">$\leq 10^5$</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr><tr><td>11</td><td rowspan="2">$\leq 7 \times 10^4$</td><td rowspan="10">$\leq 10^{18}$</td></tr><tr><td>12</td></tr><tr><td>13</td><td rowspan="4">$\leq 10^5$</td></tr><tr><td>14</td></tr><tr><td>15</td></tr><tr><td>16</td></tr><tr><td>17</td><td rowspan="4">$\leq 5 \times 10^5$</td></tr><tr><td>18</td></tr><tr><td>19</td></tr><tr><td>20</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=172">样例数据下载</a></p>
