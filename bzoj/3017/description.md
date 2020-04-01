
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">Farmer John usually brands his cows with a circular mark, but his branding iron is broken, so he instead must settle for branding each cow with a mark in the shape of a parenthesis -- (. He has two breeds of cows on his farm: Holsteins and Guernseys. He brands each of his cows with a parenthesis-shaped mark. Depending on which direction the cow is facing, this might look like either a left parenthesis or a right parenthesis.</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">FJ&#39;s N cows are all standing in a row, each facing an arbitrary direction, so the marks on the cows look like a string of parentheses of length N. Looking at this lineup, FJ sees a remarkable pattern: if he scans from left to right through just the Holsteins (in the order they appear in the sequence), this gives a balanced string of parentheses; moreover, the same is true for the Guernseys! To see if this is truly a rare event, please help FJ compute the number of possible ways he could assign breeds to his N cows so that this property holds.</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">There are several ways to define what it means for a string of parentheses to be &#34;balanced&#34;. Perhaps the simplest definition is that there must be the same total number of (&#39;s and )&#39;s, and for any prefix of the string, there must be at least as many (&#39;s as )&#39;s. For example, following strings are all balanced: </span></div>
<div><span style="font-size: medium">()</span></div>
<div><span style="font-size: medium">(())</span></div>
<div><span style="font-size: medium">()(()()) </span></div>
<div><span style="font-size: medium">while these are not: </span></div>
<div><span style="font-size: medium">)(</span></div>
<div><span style="font-size: medium">())(</span></div>
<div><span style="font-size: medium">((())))</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">问题描述</span></div>
<div style="text-indent: 17.95pt"><span style="font-size: medium">给定一个长度为<i>n</i>的括号序列，每个要么是’(‘，要么是’)’。你可以把每个位置的括号编号为H，或者是编号为G，要求编号后的括号序列所有编号为H的括号连在一起是合法的，所有编号为G的括号连在一起也是合法的。</span></div>
<div style="margin: 0cm 0cm 0pt 17.95pt"><span style="font-size: medium">其中：</span></div>
<div style="margin: 0cm 0cm 0pt 35.95pt; text-indent: -18pt"><span style="font-size: medium">①<span style="font: 7pt &#39;Times New Roman&#39;">     </span>()是合法的；</span></div>
<div style="margin: 0cm 0cm 0pt 35.95pt; text-indent: -18pt"><span style="font-size: medium">②<span style="font: 7pt &#39;Times New Roman&#39;">     </span>若<i>A</i>是合法的，则(<i>A</i>)是合法的；</span></div>
<div style="margin: 0cm 0cm 0pt 35.95pt; text-indent: -18pt"><span style="font-size: medium">③<span style="font: 7pt &#39;Times New Roman&#39;">     </span>若<i>A</i>，<i>B</i>都是合法的，则<i>AB</i>是合法的。</span></div>
<div><span style="font-size: medium">那么不同的编号方式有多少种？答案对2012取模。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">       一个长度为<i>n</i>的括号序列。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">       不同的编号方式对2012取模后的值。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
       (())<br/>
 </span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
       6<br/>
 <br/>
样例说明<br/>
(())<br/>
HHHH<br/>
(())<br/>
GGGG<br/>
(())<br/>
HGGH<br/>
(())<br/>
GHHG<br/>
(())<br/>
HGHG<br/>
(())<br/>
GHGH<br/>
 <br/>
数据范围<br/>
       对于100%的数据满足：1 &lt;= n &lt;= 1,000。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

