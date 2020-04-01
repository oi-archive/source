
# Description

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">考虑两个数列整数列</span><span class="apple-style-span"><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt">A = {a[1], a[2], …, a[n]} and B = {b[1], b[2], …, b[n]},</span></span><span class="apple-style-span"><span style="color: #333333; font-family: 宋体; mso-ascii-font-family: Helvetica; mso-hansi-font-family: Helvetica; mso-bidi-font-size: 10.5pt">如果从两个数列中各取一项</span></span><span class="apple-style-span"><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt">a[i]</span></span><span class="apple-style-span"><span style="color: #333333; font-family: 宋体; mso-ascii-font-family: Helvetica; mso-hansi-font-family: Helvetica; mso-bidi-font-size: 10.5pt">和</span></span><span class="apple-style-span"><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt">b[j]</span></span><span class="apple-style-span"><span style="color: #333333; font-family: 宋体; mso-ascii-font-family: Helvetica; mso-hansi-font-family: Helvetica; mso-bidi-font-size: 10.5pt">，其和各不相同且全部在</span></span><span class="apple-style-span"><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt">[1,n*n]</span></span><span class="apple-style-span"><span style="color: #333333; font-family: 宋体; mso-ascii-font-family: Helvetica; mso-hansi-font-family: Helvetica; mso-bidi-font-size: 10.5pt">内，则称</span></span><span class="apple-style-span"><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt">(A,B)</span></span><span class="apple-style-span"><span style="color: #333333; font-family: 宋体; mso-ascii-font-family: Helvetica; mso-hansi-font-family: Helvetica; mso-bidi-font-size: 10.5pt">是一个数列对。求本质不同的数列对数。</span></span></span><font size="3"><span class="apple-style-span"><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt"><o:p></o:p></span></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span class="apple-style-span"><span style="color: #333333; font-family: 宋体; mso-ascii-font-family: Helvetica; mso-hansi-font-family: Helvetica; mso-bidi-font-size: 10.5pt">如果两个数列对在进行以下操作或以下若干操作的组合后相同，那么则认为他们是本质相同的：</span></span></span><font size="3"><span class="apple-style-span"><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt"><o:p></o:p></span></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span class="apple-style-span"><span style="color: #333333; font-family: 宋体; mso-ascii-font-family: Helvetica; mso-hansi-font-family: Helvetica; mso-bidi-font-size: 10.5pt">交换</span><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt">A</span></span><span class="apple-style-span"><span style="color: #333333; font-family: 宋体; mso-ascii-font-family: Helvetica; mso-hansi-font-family: Helvetica; mso-bidi-font-size: 10.5pt">和</span></span><span class="apple-style-span"><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt">B</span></span><span class="apple-style-span"><span style="color: #333333; font-family: 宋体; mso-ascii-font-family: Helvetica; mso-hansi-font-family: Helvetica; mso-bidi-font-size: 10.5pt">；</span></span></span><font size="3"><span class="apple-style-span"><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt"><o:p></o:p></span></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span class="apple-style-span"><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt">A</span><span style="color: #333333; font-family: 宋体; mso-ascii-font-family: Helvetica; mso-hansi-font-family: Helvetica; mso-bidi-font-size: 10.5pt">的每个数减一常数，</span></span><span class="apple-style-span"><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt">B</span></span><span class="apple-style-span"><span style="color: #333333; font-family: 宋体; mso-ascii-font-family: Helvetica; mso-hansi-font-family: Helvetica; mso-bidi-font-size: 10.5pt">的每个数加一常数；</span></span></span><font size="3"><span class="apple-style-span"><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt"><o:p></o:p></span></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span class="apple-style-span"><span style="color: #333333; font-family: 宋体; mso-ascii-font-family: Helvetica; mso-hansi-font-family: Helvetica; mso-bidi-font-size: 10.5pt">交换</span><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt">A</span></span><span class="apple-style-span"><span style="color: #333333; font-family: 宋体; mso-ascii-font-family: Helvetica; mso-hansi-font-family: Helvetica; mso-bidi-font-size: 10.5pt">中或</span></span><span class="apple-style-span"><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt">B</span></span><span class="apple-style-span"><span style="color: #333333; font-family: 宋体; mso-ascii-font-family: Helvetica; mso-hansi-font-family: Helvetica; mso-bidi-font-size: 10.5pt">中任意两个数。</span></span></span><font size="3"><span class="apple-style-span"><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt"><o:p></o:p></span></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span class="apple-style-span"><span style="color: #333333; font-family: 宋体; mso-ascii-font-family: Helvetica; mso-hansi-font-family: Helvetica; mso-bidi-font-size: 10.5pt">所以，你可以认为</span><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt">a[1]=0</span></span><span class="apple-style-span"><span style="color: #333333; font-family: 宋体; mso-ascii-font-family: Helvetica; mso-hansi-font-family: Helvetica; mso-bidi-font-size: 10.5pt">，</span></span><span class="apple-style-span"><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt">b[1]=1</span></span><span class="apple-style-span"><span style="color: #333333; font-family: 宋体; mso-ascii-font-family: Helvetica; mso-hansi-font-family: Helvetica; mso-bidi-font-size: 10.5pt">，</span></span><span class="apple-style-span"><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt">A,B</span></span><span class="apple-style-span"><span style="color: #333333; font-family: 宋体; mso-ascii-font-family: Helvetica; mso-hansi-font-family: Helvetica; mso-bidi-font-size: 10.5pt">均按升序排列。</span></span></span><font size="3"><span class="apple-style-span"><span lang="EN-US" style="color: #333333; font-family: Helvetica; mso-bidi-font-size: 10.5pt"><o:p></o:p></span></span></font></p>
<p></p></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第一行一个整数</span><span lang="EN-US"><font face="Calibri">T</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">表示测试数据个数；</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">以下</span><span lang="EN-US"><font face="Calibri">T</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">行每行一个整数</span><span lang="EN-US"><font face="Calibri">n</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">表示序列的长度。</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><o:p></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">对于每个测试数据输出一行，表示本质不同的数列对个数。</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><o:p></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
<br/>
1<br/>
<br/>
2<br/>
<br/>
3<br/>
<br/>
4<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
1<br/>
<br/>
1<br/>
<br/>
1<br/>
<br/>
3<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
N=4时，本质不同的数列对有3个：</p><br/>
<p>(A={0,1,2,3}, B={1,5,9,13})<br/><br/>
(A={0,1,4,5}, B={1,3,9,11})<br/><br/>
(A={0,1,8,9}, B={1,3,5,7})</p><br/>
<p>【数据规模及约定】</p><br/>
<p>对于100%的数据，n&lt;=1000。</p><br/>
<p> <br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

