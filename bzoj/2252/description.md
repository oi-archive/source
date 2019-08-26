
# Description

<div class="content"><p> </p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">假设我们有矩阵</span><span lang="EN-US"><font face="Times New Roman">,</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">其元素值非零即</span><span lang="EN-US"><font face="Times New Roman">1<o:p></o:p></font></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">a11…… a<st1:chmetcnv w:st="on" tcsc="0" numbertype="1" negative="False" hasspace="False" sourcevalue="1" unitname="m">1m</st1:chmetcnv><o:p></o:p></font></font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font face="Times New Roman" size="3">…………….</font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">an1…….anm<o:p></o:p></font></font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><o:p><font face="Times New Roman" size="3"> </font></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Times New Roman"></font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">定义</span><span lang="EN-US"><font face="Times New Roman">aij</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">与</span><span lang="EN-US"><font face="Times New Roman">akl</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">之间的距离为</span><span lang="EN-US"><font face="Times New Roman">D(aij,akl)=abs(i-k)+abs(j-L) <o:p></o:p></font></span></font></p></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">输入文件的第一行为两个整数，分别代表n和m。 <br/>
接下来的n行，第i行的第 j个字符代表aij<br/>
</span></font></p></div>

# Output

<div class="content"><p>输出包含N行，每行M个用空格分开的数字，其中第i行第J个数字代表<br/>
Min(D(aij,axy) 1&lt;=x&lt;=N 1&lt;=y&lt;m,且axy=1</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4 <br/>
0001 <br/>
0011 <br/>
0110 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 2 1 0 <br/>
2 1 0 0 <br/>
1 0 0 1 </span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，满足 0 &lt;  m n &lt;=1000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

