
# Description

<div class="content"><div><span style="font-size: medium">我们考虑的序列满足下列条件: </span></div>
<ul type="disc">
    <li style="text-align: left"><span style="font-size: medium">序列长度为 <i>c</i>, </span></li>
    <li style="text-align: left"><span style="font-size: medium">序列中的每个元素都为 1-9, </span></li>
    <li style="text-align: left"><span style="font-size: medium">序列中每个元素不重复出现. </span></li>
</ul>
<div><span style="font-size: medium">一个单独的序列将被称为一个<em>code</em>. </span></div>
<div><span style="font-size: medium">当对给定的两个codes 估计他们的兼容性时，我们主要看两个值。第一个就是 (column A) 所有同时出现在两个codes 中且出现在同一位置的数字的和, 第二个就是(column B) 所有同时出现在两个codes 但出现在不同位置的数字和。</span></div>
<div><span style="font-size: medium">当我们给定<i>c</i> 个codes 和他们于某个未知code的兼容性信息时. 我们可以找到并把未知code表示出来. 下面是一个<i>c</i> = 3 的例子.</span></div>
<div><span style="font-size: medium"><img height="214" width="347" alt="" src="/source/bzoj/2604/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIwMy8xKDEpLmpwZw==.jpg"/></span></div>
<div></div></div>

# Input

<div class="content"><p><span style="font-size: 9pt; font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">第一行只有一个整数</span><span style="font-size: 9pt; font-family: Verdana; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA"> <i><span lang="EN-US">c</span></i><span lang="EN-US">, 1 &lt;= <i>c</i> &lt;= 9. </span></span><span style="font-size: 9pt; font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">接下来</span><i><span lang="EN-US" style="font-size: 9pt; font-family: Verdana; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">c</span></i><span lang="EN-US" style="font-size: 9pt; font-family: Verdana; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA"> </span><span style="font-size: 9pt; font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">行每行给出了一个</span><span lang="EN-US" style="font-size: 9pt; font-family: Verdana; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">code</span><span style="font-size: 9pt; font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">和未知</span><span lang="EN-US" style="font-size: 9pt; font-family: Verdana; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">code</span><span style="font-size: 9pt; font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">的兼容信息，每行一个。每行都有</span><i><span lang="EN-US" style="font-size: 9pt; font-family: Verdana; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">c</span></i><span lang="EN-US" style="font-size: 9pt; font-family: Verdana; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">+2 </span><span style="font-size: 9pt; font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">非负整数，第一个和第二个表示兼容信息，后面</span><span lang="EN-US" style="font-size: 9pt; font-family: Verdana; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">c</span><span style="font-size: 9pt; font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">个数表示这个</span><span lang="EN-US" style="font-size: 9pt; font-family: Verdana; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">code</span><span style="font-size: 9pt; font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">。</span><span lang="EN-US" style="font-size: 9pt; font-family: Verdana; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">.</span></p></div>

# Output

<div class="content"><p><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">输出合法的未知</span><span lang="EN-US"><font face="Verdana">code</font></span><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">，数据保证一定有解，如果有多解，输出任意一个。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
4 0 4 9 7<br/>
0 10 6 7 4<br/>
0 5 9 4 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4 1 6</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">请不要提交，希望有人提供SPJ</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

