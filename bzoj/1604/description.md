
# Description

<div class="content"><div><span style="font-size: medium">了解奶牛们的人都知道，奶牛喜欢成群结队．观察约翰的N(1≤N≤100000)只奶牛，你会</span><span style="font-size: medium">发现她们已经结成了几个“群”．每只奶牛在吃草的时候有一个独一无二的位置坐标Xi，Yi(l≤Xi，Yi≤[1．.10^9]；Xi，Yi∈整数．当满足下列两个条件之一，两只奶牛i和j是属于同一个群的：</span></div>
<div><span style="font-size: medium">  1．两只奶牛的曼哈顿距离不超过C(1≤C≤10^9)，即lXi - xil+IYi - Yil≤C.</span></div>
<div><span style="font-size: medium">  2．两只奶牛有共同的邻居．即，存在一只奶牛k，使i与k，j与k均同属一个群．</span></div>
<div><span style="font-size: medium">    给出奶牛们的位置，请计算草原上有多少个牛群，以及最大的牛群里有多少奶牛</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium"><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">   </span><span style="font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;">第</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">1</span><span style="font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;">行输入</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">N</span><span style="font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">C</span><span style="font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;">，之后</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">N</span><span style="font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;">行每行输入一只奶牛的坐标．</span></span></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><span style="font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;">仅一行，先输出牛群数，再输出最大牛群里的牛数，用空格隔开．</span></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 2<br/>
1 1<br/>
3 3<br/>
2 2<br/>
10 10<br/>
<br/>
* Line 1: A single line with a two space-separated integers: the<br/>
        number of cow neighborhoods and the size of the largest cow<br/>
        neighborhood.<br/>
<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 3<br/>
<br/>
OUTPUT DETAILS:<br/>
There are 2 neighborhoods, one formed by the first three cows and<br/>
the other being the last cow. The largest neighborhood therefore<br/>
has size 3.<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

