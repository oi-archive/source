
# Description

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-weight: bold; font-size: 14pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">对于一本小说来说，Y&amp;Y元素是很重要的。对于某一个深谙此道的人来说，Y&amp;Y更是一种符号，一种象征。</span><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">在研究一棵树的时候，他惊喜的发现了这种象征。于是他希望在这棵树中找到最大的两个Y</span><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">在树中的一个Y定义为一个中心点，以及与之相连的3条非空的链，且这三条链除了中心点之外没有其他的公共点。也就是说，一个Y最少有4个点。当然每一条链可以不断延长。一个Y的权值定义为这个Y包含的所有边的边权之和。</span><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">你的任务是对于输入的树，在其中找到两个不相交（既没有公共点，也没有公共边）Y，使两个Y的权值之和最大。</span><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: justify"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;Cambria Math&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<!--EndFragment--></div>

# Input

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">本题含有多组数据。</span><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">文件的第一行有一个正整数T，表示数据组数</span><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">接下来一共会有T个输入块</span><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">对于每一个数据块：</span><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; margin-left: 21pt; text-indent: 21pt"><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第一行有两个正整数N,M，表示这棵树的节点数和边数。</span><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; margin-left: 21pt; text-indent: 21pt"><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">接下来的M行，每行3个数</span><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">i,j,k,</span><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">分别表示一条边的两个节点编号（i,j）以及边的权值K</span><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; margin-left: 21pt; text-indent: 21pt"><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; margin-left: 21pt; text-indent: 21pt"><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">对于每一组数据，输出一行：</span><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; margin-left: 21pt; text-indent: 11.88pt"></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; margin-left: 21pt; text-indent: 11.88pt"><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">最大的Y&amp;Y权值之和，或者，如果不能找到两个不相交的Y，输出‘POOR BB</span><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">’</span><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">（不含引号）</span><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 11pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">输入样例<br/>
<br/>
1 <br/>
<br/>
9 8<br/>
<br/>
1 2 6<br/>
<br/>
2 3 5<br/>
<br/>
2 4 5<br/>
<br/>
4 5 3<br/>
<br/>
4 6 4<br/>
<br/>
6 7 3<br/>
<br/>
7 8 9<br/>
<br/>
7 9 7<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
38<br/>
<br/>
<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
T&lt;= 10 100% N&lt;=250000<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

