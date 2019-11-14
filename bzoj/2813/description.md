
# Description

<div class="content"><p class="NOI1" style="margin: 0cm 0cm 0pt"></p>
<div>Fibonacci数列是这样一个数列：</div>
<div>F1 = 1， F2 = 1， F3 = 2 . . .</div>
<div>Fi = Fi-1 + Fi-2 (当 i &gt;= 3)</div>
<div>pty忽然对这个古老的数列产生了浓厚的兴趣，他想知道：对于某一个Fibonacci数Fi，</div>
<div>有多少个Fj能够整除Fi (i可以等于j)，他还想知道所有j的平方之和是多少。</div>
<p></p></div>

# Input

<div class="content"><p class="NOI1" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第一行一个整数</span><span lang="EN-US"><font face="Times New Roman">Q,</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">表示</span><span lang="EN-US"><font face="Times New Roman">Q</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个询问。</span></span></p>
<p class="NOI1" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第二行四个整数</span><span lang="EN-US"><font face="Times New Roman">:Q<sub>1</sub>, A, B, C</font></span></span></p>
<p class="NOI1" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第</span><span lang="EN-US"><font face="Times New Roman">i</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个询问</span><span lang="EN-US"><font face="Times New Roman">Q<sub>i</sub> = (Q<sub>i-1</sub> * A + B) mod C + 1(</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">当</span><span lang="EN-US"><font face="Times New Roman">i &gt;= 2)</font></span></span></p>
<p class="NOI1" style="margin: 0cm 0cm 0pt"></p></div>

# Output

<div class="content"><p class="NOI1" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">Ai</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">代表第</span><span lang="EN-US"><font face="Times New Roman">i</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个询问有多少个</span><span lang="EN-US"><font face="Times New Roman">F<sub>j</sub></font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">能够整除</span><span lang="EN-US"><font face="Times New Roman">F<sub>Qi</sub></font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。</span></span></p>
<p class="NOI1" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">Bi</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">代表第</span><span lang="EN-US"><font face="Times New Roman">i</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个询问所有</span><span lang="EN-US"><font face="Times New Roman">j</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的平方之和。</span></span></p>
<p class="NOI1" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">输出包括两行：</span></span></p>
<p class="NOI1" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第一行是所有的</span><span lang="EN-US"><font face="Times New Roman">Ai</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">之和。</span></span></p>
<p class="NOI1" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第二行是所有的</span><span lang="EN-US"><font face="Times New Roman">Bi</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">之和。</span></span></p>
<p class="NOI1" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">由于答案过大，只需要输出除以</span><span lang="EN-US"><font face="Times New Roman">1000000007</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">得到的余数即可。</span></span></p>
<p class="NOI1" style="margin: 0cm 0cm 0pt"></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
2  2  1  8<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
55<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据保证：Q &lt;= 3*10^6，C &lt;= 10^7，A &lt;= 10^7，B &lt;= 10^7，1 &lt;= Q1&lt;= C</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

