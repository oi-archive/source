
# Description

<div class="content"><div><span style="font-size: medium">    约翰有N(1≤N≤50000)头牛，约翰的草地可以认为是一条直线．每只牛只喜欢在某个特定的范围内吃草．第i头牛喜欢在区间(Si，Ei)吃草，1≤Si&lt;Ei≤1,000,000,00.</span></div>
<div><span style="font-size: medium">    奶牛们都很自私，他们不喜欢和其他奶牛共享自己喜欢吃草的领域，因此约翰要保证任意</span></div>
<div><span style="font-size: medium">两头牛都不会共享他们喜欢吃草昀领域．如果奶牛i和奶牛J想要同时吃草，那么要满足：Si&gt;=Ej或者Ei≤Sj．约翰想知道在同一时刻，最多可以有多少头奶牛同时吃草？</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第1行：一个整数N．</span></div>
<div><span style="font-size: medium">    第2到N+1行：第i+l行有两个整数Si，Ei．</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">    一个整数，最多可以有多少头牛同时吃草．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
2 4<br/>
1 12<br/>
4 5<br/>
7 10<br/>
7 8</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">  </span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">第</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">1</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">3</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">4</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">共</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">3</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">只奶牛可以同时吃草，第</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">1</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">3</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">5</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">也可以．</span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

