# 题目描述

<p>实力强大的小 A 被选为了 ION2018 的出题人，现在他需要解决题目的命名问题。</p>

# 题目描述


<p>小 A 被选为了 ION2018 的出题人，他精心准备了一道质量十分高的题目，且已经把除了题目命名以外的工作都做好了。</p>
<p>由于 ION 已经举办了很多届，所以在题目命名上也是有规定的，ION 命题手册规定：每年由命题委员会规定一个小写字母字符串，我们称之为那一年的命名串，<strong>要求每道题的名字必须是那一年的命名串的一个非空连续子串</strong>，<strong>且不能和前一年的任何一道题目的名字相同</strong>。</p>
<p>由于一些特殊的原因，小 A 不知道 ION2017 每道题的名字，但是他通过一些特殊手段得到了 ION2017 的命名串，现在小 A 有 Q 次询问：每次给定 ION2017 的命名串和 ION2018 的命名串，求有几种题目的命名，使得这个名字一定满足命题委员会的规定，即是 ION2018的命名串的一个非空连续子串且一定不会和ION2017的任何一道题目的名字相同。</p>
<p>由于一些特殊原因，所有询问给出的 ION2017 的命名串都是某个串的连续子串，详细可见输入格式。</p>

# 输入格式


<p>第一行一个字符串 $S$ ，之后询问给出的 ION2017 的命名串都是 $S$ 的连续子串。</p>
<p>第二行一个正整数 $Q$，表示询问次数。</p>
<p>接下来 $Q$ 行，每行有一个字符串 $T$ 和两个正整数 $l,r$，表示询问如果 ION2017 的命名串是 $S[l..r]$，ION2018 的命名串是 $T$ 的话，有几种命名方式一定满足规定。 </p>
<p>保证输入中给出的字符串都是由小写字母构成的。</p>

# 输出格式


<p>输出 $Q$ 行，第 $i$ 行一个非负整数表示第 $i$ 个询问的答案。</p>

# 样例一


<h4>input</h4>
<pre>scbamgepe
3
smape 2 7
sbape 3 8
sgepe 1 9
</pre>



<h4>output</h4>
<pre>12
10
4
</pre>



# 样例二


<p>见<a href="/download.php?type=problem&amp;id=395">下载目录</a>下的 <em>ex_2.in</em> 与 <em>ex_2.ans</em>。</p>

# 子任务


<div class="table-responsive"><table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点</th><th rowspan="1">$|S|\leq$</th><th rowspan="1">$Q\leq $</th><th rowspan="1">$\sum |T|\leq $</th><th rowspan="1">询问限制</th><th rowspan="1">其他限制 </th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">$200$</td><td rowspan="5">$200$</td><td rowspan="3">$40000$</td><td rowspan="17">$\text{对于所有询问有}~l=1,r=|S|$</td><td rowspan="3">$|T|\leq 200$</td></tr><tr><td rowspan="1">2</td><td rowspan="4">$1000$</td></tr><tr><td rowspan="1">3</td></tr><tr><td rowspan="1">4</td><td rowspan="4">$5\times10^5$</td><td rowspan="5">$\text{无}$</td></tr><tr><td rowspan="1">5</td></tr><tr><td rowspan="1">6</td><td rowspan="2">$5\times10^5$</td><td rowspan="2">$1$</td></tr><tr><td rowspan="1">7</td></tr><tr><td rowspan="1">8</td><td rowspan="2">$10^5$</td><td rowspan="18">$10^5$</td><td rowspan="2">$2\times10^5$</td></tr><tr><td rowspan="1">9</td><td rowspan="1">$\text{字符串随机}$</td></tr><tr><td rowspan="1">10</td><td rowspan="2">$2\times10^5$</td><td rowspan="2">$4\times10^5$</td><td rowspan="1">$\text{无}$</td></tr><tr><td rowspan="1">11</td><td rowspan="1">$\text{字符串随机}$</td></tr><tr><td rowspan="1">12</td><td rowspan="2">$3\times10^5$</td><td rowspan="2">$6\times10^5$</td><td rowspan="1">$\text{无}$</td></tr><tr><td rowspan="1">13</td><td rowspan="1">$\text{字符串随机}$</td></tr><tr><td rowspan="1">14</td><td rowspan="2">$4\times10^5$</td><td rowspan="2">$8\times10^5$</td><td rowspan="1">$\text{无}$</td></tr><tr><td rowspan="1">15</td><td rowspan="1">$\text{字符串随机}$</td></tr><tr><td rowspan="1">16</td><td rowspan="2">$5\times10^5$</td><td rowspan="10">$10^6$</td><td rowspan="1">$\text{无}$</td></tr><tr><td rowspan="1">17</td><td rowspan="1">$\text{字符串随机}$</td></tr><tr><td rowspan="1">18</td><td rowspan="1">$2\times10^5$</td><td rowspan="8">$\text{无}$</td><td rowspan="8">$\text{无}$</td></tr><tr><td rowspan="1">19</td><td rowspan="1">$3\times10^5$</td></tr><tr><td rowspan="1">20</td><td rowspan="1">$4\times10^5$</td></tr><tr><td rowspan="1">21</td><td rowspan="5">$5\times10^5$</td></tr><tr><td rowspan="1">22</td></tr><tr><td rowspan="1">23</td></tr><tr><td rowspan="1">24</td></tr><tr><td rowspan="1">25</td></tr></tbody></table></div> 

<p>对于所有数据，保证 $1\leq l \leq r \leq |S|$,$1\leq |T|\leq 5\times10^5$</p>
<p><strong>Update: 由于配置差异，时间限制进行了一些调整，已重测</strong></p>
<p><strong>时间限制：</strong><del>4s</del> $7\texttt{s}$</p>
<p><strong>空间限制：</strong>$1\texttt{GB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=395">样例数据下载</a></p>
