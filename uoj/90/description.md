# 题目描述

<p>Sone 有一只调皮的宠物 Jie。</p>
<p>某天，Sone 在研究串匹配问题。</p>
<p>在他出门的时候在桌子上放了两个字符串：一个长度为 $n$ 的字符串 $a$ 和一个长度为 $m$ 的字符串 $b$。设 $\Sigma$ 为字符串的字符集大小，即字符串中每个字符都是 $1$ 到 $\Sigma$ 之间的整数。</p>
<p>在走之前，Sone 严肃地警告 Jie：你不准动 $b$串，那个串很重要！</p>
<p>于是，Jie 就只能调戏 $a$ 串。</p>
<p>设 $a[l:r]$ 表示 $a$ 串第 $l$ 个字符到第 $r$ 个字符之间的子串。特别地，当 $l&gt;r$ 时，$a[l:r]$ 表示空串。</p>
<p>Jie 定义了一个关于 $s$ 串和 $t$ 串的函数：</p>
<p>$$f(s,t)=\max_{s[1:k]=t[1:k]}k$$</p>
<p>即 $s$ 和 $t$ 的最长公共前缀的长度。</p>
<p>Jie 又定义了一个关于 $a$ 串和 $b$ 串的函数 $F(a,b)$。$F(a,b)$ 的值是一个二元组 $(x,y)$，其中 $x$ 为：</p>
<p>$$x=\max_{i=1}^{\lvert a \rvert} f(a[i:\lvert a \rvert],b)$$</p>
<p>而 $y$ 表示满足 $f(a[i:\lvert a \rvert], b) = x$ 的 $i$ 的个数。</p>
<p>本来问题很简单的，但由于 Jie 太调皮了，一共有 $q$ 个时刻，每个时刻他会有四种行为：</p>
<ol><li>他会修改 $a$ 串的某一位，然后询问 $F(a,b)$。（操作后 $a$ 不会还原）</li>
<li>他会选择 $a$ 串中的一个子串 $c$，询问 $F(c,b)$。</li>
<li>他会选择 $b$ 串的两个后缀，并询问这两个后缀的最长公共前缀的长度。</li>
<li>他会选择 $b$ 串的两个子串 $s_1,s_2$，并询问把 $s_1$ 和 $s_2$ 串联起来得到的字符串是否是 $b$ 串的子串，是的话输出 “<samp>yes</samp>”，否则输出 “<samp>no</samp>”（不含引号）。</li>
</ol><p>于是，Jie 困扰了，希望聪明的你能解决这个问题。</p>

# 输入格式


<p>设 $\Sigma$ 为字符串的字符集大小，即字符串中每个字符都是 $1$ 到 $\Sigma$ 之间的整数。</p>
<p>第一行一个整数表示测试点编号。（样例和 Extra Test 中测试点编号为 $0$  到 $20$ 间的任意整数）</p>
<p>第二行一个正整数表示 $a$ 串的长度 $n$。</p>
<p>第三行 $n$ 个 $1$ 到 $\Sigma$ 间的整数表示 $a$ 串。</p>
<p>第四行一个正整数表示 $b$ 串的长度 $m$。</p>
<p>第五行 $m$ 个 $1$ 到 $\Sigma$ 间的整数表示 $b$ 串。</p>
<p>第六行一个正整数表示询问个数 $q$。</p>
<p>接下来 $q$ 行表示操作，每行包含若干个整数。第一个整数 $x$ 表示操作类型：</p>
<ol><li>若 $x=1$ 则后面有两个整数 $y,z$，表示把 $a$ 串中的第 $y$ 位改成 $z$。$1 \leq y \leq n$，$1 \leq z \leq \Sigma$。</li>
<li>若 $x=2$ 则后面有两个整数 $y,z$，表示询问的子串在 $a$ 串中的区间 $[y, z]$。$1 \leq y \leq z \leq n$。</li>
<li>若 $x=3$ 则后面有两个整数 $y,z$，表示询问的两个后缀的第一个字符在 $b$ 串中的位置。$1 \leq y, z \leq m$。</li>
<li>若 $x=4$ 则后面有四个整数 $l_1,r_1,l_2,r_2$，表示询问的两个子串在 $b$ 串中的区间 $[l_1,r_1]$ 和 $[l_2,r_2]$。$1 \leq l_1 \leq r_1 \leq m$，$1 \leq l_2 \leq r_2 \leq m$。</li>
</ol>
# 输出格式


<p>有 $q$ 行，每行对应每种操作的答案。</p>

# 样例一


<h4>input</h4>
<pre>0
10
1 2 3 3 3 1 2 3 2 1
3
1 3 1
10
3 1 3
4 3 3 2 2
2 2 10
1 3 2
2 7 9
2 7 10
2 3 9
2 2 8
1 7 1
1 4 2

</pre>

<h4>output</h4>
<pre>1
yes
1 2
1 3
0 3
1 1
1 1
1 1
2 1
2 1

</pre>



# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$m$</th>
<th>$q$</th>
<th>$\Sigma$</th>
<th>备注</th>
</tr></thead><tbody><tr><td>1,2</td><td>$= 1000$</td><td>$\leq 100$</td><td>$= 1000$</td><td rowspan="5">$\leq 100000$</td><td>无</td></tr><tr><td>3,4</td><td>$= 100000$</td><td>$\leq 100$</td><td>$= 100000$</td><td>无操作二</td></tr><tr><td>5,6</td><td>$= 100000$</td><td>$\leq 30$</td><td>$= 100000$</td><td>无</td></tr><tr><td>7,8</td><td rowspan="7">$= 100000$</td><td rowspan="7">$\leq 100000$</td><td rowspan="7">$= 100000$</td><td>只有操作三</td></tr><tr><td>9,10</td><td>只有操作四</td></tr><tr><td>11,12</td><td rowspan="3">$\leq 5$</td><td rowspan="3">$b$ 串的生成方式是：人工确定每种字符出现的比例，<br/> 然后均匀随机选取一个满足这一比例的字符串作为 $b$</td></tr><tr><td>13,14</td></tr><tr><td>15,16</td></tr><tr><td>17,18</td><td rowspan="2">$\leq 100000$</td><td rowspan="2">无</td></tr><tr><td>19,20</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 来源


<p>中国国家集训队互测2015 - By 王鉴浩</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=90">样例数据下载</a></p>
