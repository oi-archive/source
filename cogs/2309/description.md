# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
   众所周知，香山的红叶非常著名。然而，CTSC举行的时间是在5月，而红叶的季节是秋天，所以这个季节是看不到红叶的，于是我们在CTSC比赛中就只能讨论香山的树了。
</p>
<p>
   s-quark 很喜欢这些树，他计划在每棵树上贴上一个各不相同的标签。每个标签为条形，可以在树干上绕成一圈。为了区分每一棵树，s-quark 在每个标签上印了一个由小写英文字母组成的字符串。由于树干周长的限制，标签的长度也是有限的，因此这个字符串至多只能由 N 个字母组成。
</p>
<p>
   但是，由于标签是在树干上围成一圈的，所以当标签在树上贴好以后，就不再能找到标签的起始位置了。所以，如果两棵树上的标签循环同构，例如分别为 abc 和 cab ，那么这两棵树就不再能通过标签区分了。针对这个问题，s-quark 想了一个巧妙的办法。对于一个已经在树上贴好的标签，s-quark 规定它的起始位置必须是能够使得字符串的字典序最小的起始位，即如果看到的字符串是aba，那么就可以推断出从正确的起始位置开始看到的字符串应为aab。
</p>
<p>
   另外，对于有些标签，例如abab，尽管符合字典序最小的规则，但是这样的起始位置不唯一，s-quark认为这种情况也是不理想的。所以，这样的标签s-quark 也会避免使用。s-quark 已经把所有的树编好了顺序，准备在第一棵树上贴标签a，之后按照字典序给每棵树贴上不同的标签。
</p>
<p>
   以 N = 3 为例，s-quark 将依次使用这些标签来标记这些树木：a,aab,aac,…,aaz,ab,abb,…,abz,ac,…
</p>
<p>
   s-quark 知道，香山上的树总共有 K 棵。他想知道他将在最后一棵树上贴的标签是什么。但是，这个问题显然太简单了。现在，s-quark 要问你，如果他在第一棵树上贴的标签是字符串 S，那么他将在最后一棵树上贴的标签是什么呢?
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
 输入文件为treeabel.in。
</p>
<p>
 输入的第一行两个正整数 N 和 K，分别为字符串的长度和树的总数。
</p>
<p>
 第二行一个由小写英文字母组成的字符串 S，表示在第一棵树上所贴的标签。S 的长度不超过 N，并且保证是一个合法的标签。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
 输出文件为treelabel.out。
</p>
<p>
 输出仅一行，输出一个字符串 T，表示 s-quark 将在最后一棵树上贴的标签，或输出 -1，表示剩余的合法标签数量不足以贴完所有的树。
</p>
<p>
<br/>
</p>
<h3>
【样例输入1】
</h3>
<pre>3 10
a
</pre>
<h3>
【样例输出1】
</h3>
<pre>aaj
</pre>
<h3>
【样例输入2】
</h3>
<pre>3 10
xy
</pre>
<h3>
【样例输出2】
</h3>
<pre>yzz
</pre>
<h3>
【样例输入3】
</h3>
<pre>1 100
</pre>
<h3>
【样例输出3】
</h3>
<pre>-1
</pre>
<h3>
【样例输入4】
</h3>
<pre>25 1000000000000000
u
</pre>
<h3>
【样例输出4】
</h3>
<pre>uuuuuvxzuxvwwyzzuyzvxuvxw
</pre>
<h3>
【子任务】
</h3>
<p>
</p><table style="width:60%;" cellpadding="2" cellspacing="0" border="1" bordercolor="#000000">
<tbody>
<tr>
<td style="text-align:center;">
测试点
</td>
<td style="text-align:center;">
N
</td>
<td style="text-align:center;">
K
</td>
<td style="text-align:center;">
数据特点
</td>
</tr>
<tr>
<td style="text-align:center;">
1
</td>
<td style="text-align:center;">
= 8
</td>
<td style="text-align:center;">
≤ 10^4<br/>
</td>
<td style="text-align:center;">
S 为字符串 &#34;a&#34;<br/>
</td>
</tr>
<tr>
<td style="text-align:center;">
2,3
</td>
<td style="text-align:center;">
= 9
</td>
<td style="text-align:center;">
≤ 10^6<br/>
</td>
<td style="text-align:center;" rowspan="6">
无
</td>
</tr>
<tr>
<td style="text-align:center;">
4
</td>
<td style="text-align:center;">
= 8
</td>
<td style="text-align:center;" rowspan="5">
≤ 10^15<br/>
</td>
</tr>
<tr>
<td style="text-align:center;">
5
</td>
<td style="text-align:center;">
= 9
</td>
</tr>
<tr>
<td style="text-align:center;">
6
</td>
<td style="text-align:center;">
= 10
</td>
</tr>
<tr>
<td style="text-align:center;">
7,8
</td>
<td style="text-align:center;">
≤ 30<br/>
</td>
</tr>
<tr>
<td style="text-align:center;">
9,10
</td>
<td style="text-align:center;">
≤ 50<br/>
</td>
</tr>
</tbody>
</table>
<p></p>
<h3>
【来源】
</h3>
<p>
CTSC2016 D2T2
</p>
