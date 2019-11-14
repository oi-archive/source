# 题目描述

<p>如果一个字符串可以被拆分为 $AABB$ 的形式，其中 $A$ 和 $B$ 是任意<strong>非空</strong>字符串，则我们称该字符串的这种拆分是优秀的。</p>
<p>例如，对于字符串 <samp>aabaabaa</samp>，如果令 $A = \mathrm{aab}$，$B = \mathrm{a}$，我们就找到了这个字符串拆分成 $AABB$ 的一种方式。</p>
<p>一个字符串可能没有优秀的拆分，也可能存在不止一种优秀的拆分。比如我们令 $A=\mathrm{a}$，$B=\mathrm{baa}$，也可以用 $AABB$ 表示出上述字符串；但是，字符串 <samp>abaabaa</samp> 就没有优秀的拆分。</p>
<p>现在给出一个长度为 $n$ 的字符串 $S$，我们需要求出，在它<strong>所有子串</strong>的所有拆分方式中，优秀拆分的总个数。这里的子串是指字符串中<strong>连续</strong>的一段。</p>
<p>以下事项需要注意：</p>
<ol><li>出现在不同位置的相同子串，我们认为是不同的子串，它们的优秀拆分均会被记入答案。</li>
<li>在一个拆分中，允许出现 $A=B$。例如 <samp>cccc</samp> 存在拆分 $A=B=\mathtt{c}$。</li>
<li>字符串本身也是它的一个子串。</li>
</ol>
# 输入格式


<p>每个输入文件包含多组数据。输入文件的第一行只有一个整数 $T$，表示数据的组数。保证 $1 \le T \le 10$。</p>
<p>接下来 $T$ 行，每行包含一个仅由英文小写字母构成的字符串 $S$，意义如题所述。</p>

# 输出格式


<p>输出 $T$ 行，每行包含一个整数，表示字符串 $S$ 所有子串的所有拆分中，总共有多少个是优秀的拆分。</p>

# 样例一


<h4>input</h4>
<pre>4
aabbbb
cccccc
aabaabaabaa
bbaabaababaaba

</pre>

<h4>output</h4>
<pre>3
5
4
7

</pre>

<h4>explanation</h4>
<p>我们用 $S[i, j]$ 表示字符串 $S$ 第 $i$ 个字符到第 $j$ 个字符的子串（从 $1$ 开始计数）。</p>
<p>第一组数据中，共有 $3$ 个子串存在优秀的拆分：</p>
<p>$S[1,4] = \mathtt{aabb}$，优秀的拆分为 $A=\mathtt{a}$，$B = \mathtt{b}$；</p>
<p>$S[3,6] = \mathtt{bbbb}$，优秀的拆分为 $A=\mathtt{b}$，$B = \mathtt{b}$；</p>
<p>$S[1,6] = \mathtt{aabbbb}$，优秀的拆分为 $A= \mathtt{a}$，$B = \mathtt{bb}$。</p>
<p>而剩下的子串不存在优秀的拆分，所以第一组数据的答案是 $3$。</p>
<p>第二组数据中，有两类，总共 $4$ 个子串存在优秀的拆分：</p>
<p>对于子串 $S[1,4] = S[2,5] = S[3,6] = \mathrm{cccc}$，它们优秀的拆分相同，均为 $A = \mathrm{c}$，$B = \mathrm{c}$，但由于这些子串位置不同，因此要计算 $3$ 次；</p>
<p>对于子串 $S[1,6] = \mathrm{cccccc}$，它优秀的拆分有 $2$ 种：$A = \mathrm{c}$，$B = \mathrm{cc}$ 和 $A = \mathrm{cc}$，$B = \mathrm{c}$，它们是相同子串的不同拆分，也都要计入答案。</p>
<p>所以第二组数据的答案是 $3 + 2 = 5$。</p>
<p>第三组数据中，$S[1,8]$ 和 $S[4,11]$ 各有 $2$ 种优秀的拆分，其中 $S[1,8]$ 是问题描述中的例子，所以答案是 $2 + 2 = 4$。</p>
<p>第四组数据中，$S[1,4]$，$S[6,11]$，$S[7,12]$，$S[2,11]$，$S[1,8]$ 各有 $1$ 种优秀的拆分，$S[3,14]$ 有 $2$ 种优秀的拆分，所以答案是 $5 + 2 = 7$。</p>

# 样例二


<p>见样例数据下载。</p>

# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<p>对于全部的测试点,保证 $1 \le T \le 10$。以下对数据的限制均是对于单组输入数据而言的，也就是说同一个测试点下的 $T$ 组数据均满足限制条件。</p>
<p>我们假定 $n$ 为字符串 $S$ 的长度，每个测试点的详细数据范围见下表：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>其他约束</th>
</tr></thead><tbody><tr><td>1、2</td><td>$\leq 300$</td><td rowspan="2">$S$中所有字符全部相同</td></tr><tr><td>3、4</td><td>$\leq 2000$</td></tr><tr><td>5、6</td><td>$\leq 10$</td><td rowspan="11">无</td></tr><tr><td>7、8</td><td>$\leq 20$</td></tr><tr><td>9、10</td><td>$\leq 30$</td></tr><tr><td>11、12</td><td>$\leq 50$</td></tr><tr><td>13、14</td><td>$\leq 100$</td></tr><tr><td>15</td><td>$\leq 200$</td></tr><tr><td>16</td><td>$\leq 300$</td></tr><tr><td>17</td><td>$\leq 500$</td></tr><tr><td>18</td><td>$\leq 1000$</td></tr><tr><td>19</td><td>$\leq 2000$</td></tr><tr><td>20</td><td>$\leq 30000$</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1.5\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=219">样例数据下载</a></p>
