
# Description

<div class="content"><p></p><p></p>
<p></p>
<p class="MsoBodyTextIndent" style="margin: 6pt 0cm 0pt; text-indent: 24pt"></p>
<p class="MsoBodyTextIndent" style="margin: 6pt 0cm 0pt; text-indent: 24pt"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">有一个仓库被分成</span><span lang="EN-US"><font face="Times New Roman">n*m </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个矩形区域，如果两个区域有一条公共边，则被认为这两个区域相邻。包裹都放在一个区域中，剩余的区域或者空闲或者被集装箱占有，这是因为集装箱太重，仓库管理员不能将集装箱搬走。仓库管理员目是是要将包裹从开始的</span><span lang="EN-US"><font face="Times New Roman">P</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">区域移动到最后的</span><span lang="EN-US"><font face="Times New Roman">K</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">区域。他可以从空区域走到与之相邻的一个空区域。当仓库管理员走到与包裹相邻的区域时，它可以推动包裹，具体的推动方法如下所示：</span></p>
<p class="MsoBodyTextIndent" style="margin: 6pt 0cm 0pt; text-indent: 24pt"></p>
<p></p>
<p></p>
<p><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><img alt="" src="/source/bzoj/2574/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTExMi8xKDEwKS5qcGc=.jpg"/></span></p>
<p></p>
<p></p>
<p><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"> </span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">读入一个储藏表，开始位置为仓库管理员，最后位置为包裹移动的位置</span><span lang="EN-US"><font face="Times New Roman"> </font></span></p>
<p></p></div>

# Input

<div class="content"><p></p>
<p></p>
<p class="MsoBodyTextIndent" style="margin: 6pt 0cm 0pt; text-indent: 24pt"><span style="font-size: large"><span lang="EN-US"><font face="Times New Roman">S – </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">集装箱</span><span lang="EN-US"><font face="Times New Roman">, </font></span></span></p>
<p class="MsoBodyTextIndent" style="margin: 6pt 0cm 0pt; text-indent: 24pt"><span style="font-size: large"><span lang="EN-US"><font face="Times New Roman">M –</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">仓库管理员的位置</span><span lang="EN-US"><font face="Times New Roman">, </font></span></span></p>
<p class="MsoBodyTextIndent" style="margin: 6pt 0cm 0pt; text-indent: 24pt"><span style="font-size: large"><span lang="EN-US"><font face="Times New Roman">P –</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">包裹开始的位置</span><span lang="EN-US"><font face="Times New Roman">, </font></span></span></p>
<p class="MsoBodyTextIndent" style="margin: 6pt 0cm 0pt; text-indent: 24pt"><span style="font-size: large"><span lang="EN-US"><font face="Times New Roman">K –</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">包裹最后的位置</span><span lang="EN-US"><font face="Times New Roman">, </font></span></span></p>
<p class="MsoBodyTextIndent" style="margin: 6pt 0cm 0pt; text-indent: 24pt"><span style="font-size: large"><span lang="EN-US"><font face="Times New Roman">w –</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">空区域</span><span lang="EN-US"><font face="Times New Roman">.  </font></span></span></p>
<p class="MsoBodyTextIndent" style="margin: 6pt 0cm 0pt; text-indent: 24pt"><span style="font-size: large"><span lang="EN-US"><font face="Times New Roman">S, M, P </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><font face="Times New Roman"> K </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">在文件</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">中只出现一次</span><span lang="EN-US"><font face="Times New Roman">.</font></span></span></p>
<p></p>
<p> </p>
<p><span style="font-size: large"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第一行有两个用单个空格分隔的正整数</span><span lang="EN-US"><font face="Times New Roman">n,m&lt;=100. </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">接下来是货物存放二维表</span><span lang="EN-US"><font face="Times New Roman">.</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">共</span><span lang="EN-US"><font face="Times New Roman">N</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行，每行为</span><span lang="EN-US"><font face="Times New Roman">M </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个字母组成的单词，字母分别是</span><span lang="EN-US"><font face="Times New Roman">S, M, P, K, w. </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第</span><span lang="EN-US"><font face="Times New Roman">i</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">单词的第</span><span lang="EN-US"><font face="Times New Roman">j</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个位置表示第</span><span lang="EN-US"><font face="Times New Roman">i</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行第</span><span lang="EN-US"><font face="Times New Roman">j</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">列区域的信息，可能是如下内容</span><span lang="EN-US"><font face="Times New Roman">: </font></span></span></p></div>

# Output

<div class="content"><p class="MsoBodyTextIndent" style="margin: 6pt 0cm 0pt; text-indent: 24pt"><span style="font-size: large"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">如果包裹不能移动到目的位置，则写入</span><span lang="EN-US"><font face="Times New Roman">NO</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。</span></span></p>
<p class="MsoBodyTextIndent" style="margin: 6pt 0cm 0pt; text-indent: 24pt"><span style="font-size: large"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">如果包裹能移动到目的位置，则写入最小的移动次数。</span></span></p>
<p class="MsoBodyTextIndent" style="margin: 6pt 0cm 0pt; text-indent: 21pt"></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 12<br/>
<br/>
SSSSSSSSSSSS<br/>
<br/>
SwwwwwwwSSSS<br/>
<br/>
SwSSSSwwSSSS<br/>
<br/>
SwSSSSwwSKSS<br/>
<br/>
SwSSSSwwSwSS<br/>
<br/>
SwwwwwPwwwww<br/>
<br/>
SSSSSSSwSwSw<br/>
<br/>
SSSSSSMwSwww<br/>
<br/>
SSSSSSSSSSSS<br/>
<br/>
SSSSSSSSSSSS<br/>
<br/>
<br/>
<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

