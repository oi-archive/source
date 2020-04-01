
# Description

<div class="content"><p class="NormalText" align="center" style="margin: 0cm 0cm 0pt; text-indent: 0cm; text-align: center; mso-char-indent-count: 0"><b><span lang="EN-US" style="font-size: 16pt; mso-bidi-font-size: 12.0pt"><o:p></o:p></span></b></p>
<p class="NormalText" style="margin: 0cm 0cm 0pt; text-indent: 21.75pt; mso-char-indent-count: 0"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">你一个人去保龄球馆去打保龄球。总共有</span><span lang="EN-US"><font face="Times New Roman">k</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个球可用。每个球的宽度为</span><span lang="EN-US"><font face="Times New Roman">w</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。在你前方有</span><span lang="EN-US"><font face="Times New Roman">n</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个球棒要打。这</span><span lang="EN-US"><font face="Times New Roman">n</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">球棒紧密的排成一行，且第</span><span lang="EN-US"><font face="Times New Roman">i</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个球棒宽度为</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，价值为</span><span lang="EN-US"><font face="Times New Roman">x<sub>i</sub></font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。你的每个球恰能击中第</span><span lang="EN-US"><font face="Times New Roman">a</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个</span><span lang="EN-US"><font face="Times New Roman">~</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第</span><span lang="EN-US"><font face="Times New Roman">a+w-1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个的球棒（如果此球棒存在的话）。球棒被打到就倒了，且互不影响。你可以向任意方向击球，甚至球的一部分可以越过最左、最右边球棒所构成的边界。求最大价值。</span></font></p>
<p class="NormalText" style="margin: 0cm 0cm 0pt; text-indent: 21.75pt; mso-char-indent-count: 0"><span lang="EN-US"><o:p><font face="Times New Roman" size="3"> </font></o:p></span></p>
<p></p></div>

# Input

<div class="content"><p class="NormalText" style="margin: 0cm 0cm 0pt; text-indent: 21.75pt; mso-char-indent-count: 0"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">文件第一行是三个整数</span><span lang="EN-US"><font face="Times New Roman">n,k,w</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。以下</span><span lang="EN-US"><font face="Times New Roman">n</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行是</span><span lang="EN-US"><font face="Times New Roman">n</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个整数，第</span><span lang="EN-US"><font face="Times New Roman">I</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个代表</span><span lang="EN-US"><font face="Times New Roman">x<sub>i</sub></font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。</span></font></p>
<p class="NormalText" style="margin: 0cm 0cm 0pt; text-indent: 21.75pt; mso-char-indent-count: 0"><span lang="EN-US"><o:p><font face="Times New Roman" size="3"> </font></o:p></span></p>
<p class="NormalText" style="margin: 0cm 0cm 0pt; text-indent: 21.75pt; mso-char-indent-count: 0"></p></div>

# Output

<div class="content"><p class="NormalText" style="margin: 0cm 0cm 0pt; text-indent: 21.75pt; mso-char-indent-count: 0"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><font size="3">仅一行，为最大价值。</font></span></p>
<p class="NormalText" style="margin: 0cm 0cm 0pt; text-indent: 21.75pt; mso-char-indent-count: 0"><span lang="EN-US"><o:p><font face="Times New Roman" size="3"> </font></o:p></span></p>
<pre></pre></div>

# Sample Input

<div class="content"><span class="sampledata">9 2 3<br/>
2<br/>
8<br/>
5<br/>
1<br/>
9<br/>
6<br/>
9<br/>
3<br/>
2<br/>
 <br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
39<br/>
<br/>
 <br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>100%的数据满足1≤n≤10000，1≤w≤100，1≤k≤500；<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=CCC2007">CCC2007</a></p></div>

