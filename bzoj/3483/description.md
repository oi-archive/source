
# Description

<div class="content"><p></p>
<p class="MsoNormal" style="text-indent:21.0pt;line-height:150%"><span style="font-size: medium; "><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">GAL</span><span style="font-family: 宋体; ">发现了</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">N</span><span style="font-family: 宋体; ">个特殊的字母序列，由小写字母组成。小</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">L</span><span style="font-family: 宋体; ">认为，对于两个字符串</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">s1,s2</span><span style="font-family: 宋体; ">，若</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">s1</span><span style="font-family: 宋体; ">是某个特殊序列的前缀，</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">s2</span><span style="font-family: 宋体; ">是该特殊序列的后缀，则称</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">s1,s2</span><span style="font-family: 宋体; ">被这个序列拥有。</span></span><span lang="EN-US" style="font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:Calibri"><o:p></o:p></span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span style="font-family: 宋体; ">现在小</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">L</span><span style="font-family: 宋体; ">给出</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">M</span><span style="font-family: 宋体; ">对</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">s1,s2</span><span style="font-family: 宋体; ">，对于每对字符串，问它们被几个特殊序列拥有。</span></span><span lang="EN-US" style="font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:Calibri"><o:p></o:p></span></p>
<p class="MsoNormal" style="text-indent:21.0pt;line-height:150%"></p></div>

# Input

<div class="content"><p> <span style="font-size: medium; line-height: 18px; text-indent: 21pt; font-family: 宋体; ">第</span><span lang="EN-US" style="font-size: medium; line-height: 18px; text-indent: 21pt; font-family: &#39;Times New Roman&#39;; ">1</span><span style="font-size: medium; line-height: 18px; text-indent: 21pt; font-family: 宋体; ">行一个整数</span><span lang="EN-US" style="font-size: medium; line-height: 18px; text-indent: 21pt; font-family: &#39;Times New Roman&#39;; ">N</span><span style="font-size: medium; line-height: 18px; text-indent: 21pt; font-family: 宋体; ">。</span></p>
<p class="MsoNormal" style="text-indent: 21pt; line-height: 18px; "><span style="font-size: medium; "><span style="font-family: 宋体; ">接下来</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">N</span><span style="font-family: 宋体; ">行，每行一个字符串，代表</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">N</span><span style="font-family: 宋体; ">个特殊序列。</span></span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; "><o:p></o:p></span></p>
<p class="MsoNormal" style="text-indent: 21pt; line-height: 18px; "><span style="font-size: medium; "><span style="font-family: 宋体; ">第</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">N+2</span><span style="font-family: 宋体; ">行一个整数</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">M</span><span style="font-family: 宋体; ">。</span></span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; "><o:p></o:p></span></p>
<p class="MsoNormal" style="text-indent: 21pt; line-height: 18px; "><span style="font-size: medium; "><span style="font-family: 宋体; ">接下来</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">M</span><span style="font-family: 宋体; ">行每行一对</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">s1,s2</span><span style="font-family: 宋体; ">用空格隔开。</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">S1,s2</span><span style="font-family: 宋体; ">是经过加密的。</span></span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; "><o:p></o:p></span></p>
<p class="MsoNormal" style="text-indent: 21pt; line-height: 18px; "><span style="font-size: medium; "><span style="font-family: 宋体; ">设上一问的答案为</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">lastans</span><span style="font-family: 宋体; ">。解密方法是将</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">s1,s2</span><span style="font-family: 宋体; ">所有字母向后移动</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">lastans</span><span style="font-family: 宋体; ">个单位，这时你要把小写字母表当作一个环，比如</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">z</span><span style="font-family: 宋体; ">的下一个字母是</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">a</span><span style="font-family: 宋体; ">。</span></span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; "><o:p></o:p></span></p>
<p class="MsoNormal"></p>
<p class="MsoNormal" style="text-indent: 21pt; line-height: 18px; "></p></div>

# Output

<div class="content"><p><span style="font-size: medium; "> </span></p>
<div><span style="font-size: medium; "><br/>
</span></div>
<div><span style="font-size: medium; "><span style="font-family: 宋体; line-height: 18px; text-indent: 28px; ">对于每次询问操作，输出一个非负整数表示答案。</span></span></div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
aaaaa<br/>
abacabaa<br/>
avtobus<br/>
6<br/>
a a<br/>
y yy<br/>
yy y<br/>
zzzzz zzzz<br/>
zazb bzaz<br/>
abac a<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
2<br/>
1<br/>
1<br/>
0<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium; "> </span><a id="fck_paste_padding"><span style="font-size: medium; ">﻿</span></a><span style="font-size: medium; "><span style="font-family: 宋体; ">设</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">N</span><span style="font-family: 宋体; ">个特殊序列总长为</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">L1</span><span style="font-family: 宋体; ">，所有</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">M</span><span style="font-family: 宋体; ">组询问总长为</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">L2</span><span style="font-family: 宋体; ">。</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">L1</span><span style="font-family: 宋体; ">，</span><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">L2&lt;=</span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; ">2000000.N&lt;=2000,M&lt;=100000</span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Hta">By Hta</a></p></div>

