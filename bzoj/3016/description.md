
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">Bessie the cow is trying to type a balanced string of parentheses into her new laptop, but she is sufficiently clumsy (due to her large hooves) that she keeps mis-typing characters. Please help her by computing the minimum number of characters in the string that one must reverse (e.g., changing a left parenthesis to a right parenthesis, or vice versa) so that the string would become balanced. There are several ways to define what it means for a string of parentheses to be &#34;balanced&#34;. Perhaps the simplest definition is that there must be the same total number of (&#39;s and )&#39;s, and for any prefix of the string, there must be at least as many (&#39;s as )&#39;s. For example, the following strings are all balanced: </span></div>
<div><span style="font-size: medium">()</span></div>
<div><span style="font-size: medium">(())</span></div>
<div><span style="font-size: medium">()(()()) </span></div>
<div><span style="font-size: medium">while these are not: </span></div>
<div><span style="font-size: medium">)(</span></div>
<div><span style="font-size: medium">())(</span></div>
<div><span style="font-size: medium">((())))</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">问题描述</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">给定长度为<i>n</i>的一个括号序列，每次修改可以修改一个位置的括号，若这个括号为’(‘，则修改为’)’，若这个括号为’)’，则修改为’(‘，问最少修改多少个使得原括号序列合法。</span></div>
<div style="margin: 0cm 0cm 0pt 17.95pt"><span style="font-size: medium">其中：</span></div>
<div style="margin: 0cm 0cm 0pt 35.95pt; text-indent: -18pt"><span style="font-size: medium">①<span style="font: 7pt &#39;Times New Roman&#39;">     </span>()是合法的；</span></div>
<div style="margin: 0cm 0cm 0pt 35.95pt; text-indent: -18pt"><span style="font-size: medium">②<span style="font: 7pt &#39;Times New Roman&#39;">     </span>若<i>A</i>是合法的，则(<i>A</i>)是合法的；</span></div>
<div style="margin: 0cm 0cm 0pt 35.95pt; text-indent: -18pt"><span style="font-size: medium">③<span style="font: 7pt &#39;Times New Roman&#39;">     </span>若<i>A</i>，<i>B</i>都是合法的，则<i>AB</i>是合法的。</span></div>
<div style="margin: 0cm 0cm 0pt 18pt"><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium"> 一个长度为<i>n</i>个括号序列。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">最少的修改次数。</span></div>
<div><span style="font-size: medium"> </span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">  ())(</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 2<br/>
 样例说明<br/>
       修改为()()，其中红色部分表示修改的括号。<br/>
 <br/>
数据范围<br/>
       100%的数据满足：1 &lt;= n &lt;= 100,000。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

