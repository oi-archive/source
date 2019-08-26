
# Description

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">志向远大的</span><span lang="EN-US"><font face="Times New Roman">YY</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">小朋友在学完快速排序之后决定学习平衡树，左思右想再加上</span><span lang="EN-US"><font face="Times New Roman">SY</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的教唆，</span><span lang="EN-US"><font face="Times New Roman">YY</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">决定学习</span><span lang="EN-US"><font face="Times New Roman">Treap</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。友爱教教父</span><span lang="EN-US"><font face="Times New Roman">SY</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">如砍瓜切菜般教会了</span><span lang="EN-US"><font face="Times New Roman">YY</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">小朋友</span><span lang="EN-US"><font face="Times New Roman">Treap</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">（<b style="mso-bidi-font-weight: normal">一种平衡树，通过对每个节点随机分配一个</b></span><span class="word"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><font face="Times New Roman">priority</font></span></b></span><span class="word"><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，同时保证这棵平衡树关于</span><span lang="EN-US"><font face="Times New Roman">priority</font></span></b></span><span class="word"><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">是一个小根堆以保证效率</span></b></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">）。这时候不怎么友爱的</span><span lang="EN-US"><font face="Times New Roman">510</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">跑了出来，他问了</span><span lang="EN-US"><font face="Times New Roman">YY</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">小朋友一个极不和谐的问题：<b style="mso-bidi-font-weight: normal">怎么求</b></span><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><font face="Times New Roman">Treap</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">中两个点之间的路径长度。</span></b><span lang="EN-US"><font face="Times New Roman">YY</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">秒了之后决定把这个问题交给你来做，但只要求出树中两点的</span><span lang="EN-US"><font face="Times New Roman">LCA</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span lang="EN-US"><o:p><font face="Times New Roman" size="3"> </font></o:p></span></p>
<p></p></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第一行两个整数</span><span lang="EN-US"><font face="Times New Roman">n</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">m</font></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第二行</span><span lang="EN-US"><font face="Times New Roman">n</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个整数表示每个元素的</span><span lang="EN-US"><font face="Times New Roman">key</font></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第三行</span><span lang="EN-US"><font face="Times New Roman">n</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个整数表示每个元素的</span><span class="word"><span lang="EN-US"><font face="Times New Roman">priority<o:p></o:p></font></span></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><span class="word"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">接下</span><span lang="EN-US"><font face="Times New Roman">m</font></span></span><span class="word"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行，每行一条命令</span><span lang="EN-US"><o:p></o:p></span></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><span class="word"><span lang="EN-US"><font face="Times New Roman">I A B</font></span></span><span class="word"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，插入一个元素，</span></span><span lang="EN-US"><font face="Times New Roman">key</font></span><span class="word"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">为</span><span lang="EN-US"><font face="Times New Roman">A, priority</font></span></span><span class="word"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">为</span><span lang="EN-US"><font face="Times New Roman">B<o:p></o:p></font></span></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><span class="word"><span lang="EN-US"><font face="Times New Roman">D A</font></span></span><span class="word"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，删除一个元素，</span></span><span lang="EN-US"><font face="Times New Roman">key</font></span><span class="word"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">为</span><span lang="EN-US"><font face="Times New Roman">A<o:p></o:p></font></span></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><span class="word"><span lang="EN-US"><font face="Times New Roman">Q A B</font></span></span><span class="word"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，询问</span><span lang="EN-US"><font face="Times New Roman">key</font></span></span><span class="word"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">分别为</span><span lang="EN-US"><font face="Times New Roman">A</font></span></span><span class="word"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><font face="Times New Roman">B</font></span></span><span class="word"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的</span><span lang="EN-US"><font face="Times New Roman">LCA</font></span></span><span class="word"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的</span><span lang="EN-US"><font face="Times New Roman">key</font></span></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span lang="EN-US"><o:p><font face="Times New Roman" size="3"> </font></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><o:p></o:p></span></b></font></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">对于每个</span><span lang="EN-US"><font face="Times New Roman">Q</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">输出一个整数。</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span lang="EN-US"><o:p><font face="Times New Roman" size="3"> </font></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><o:p></o:p></span></b></font></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 2<br/>
<br/>
1 2<br/>
<br/>
4 5<br/>
<br/>
Q 1 2<br/>
<br/>
I 3 3<br/>
<br/>
 <br/>
<br/>
 <br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
数据保证n&lt;=10^5,m&lt;=3*10^5</p><br/>
<p>其余整数均不超过long的范围</p><br/>
<p>数据保证任意时刻树中key和priority均不相同<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

