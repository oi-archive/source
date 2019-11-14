
# Description

<div class="content"><p><span style="font-size: medium">贝茜是一只非常努力工作的奶牛，她总是专注于提高自己的产量。为了产更多的奶，她预计好了接下来的N (1 ≤ N ≤ 1,000,000)个小时，标记为0..N-1。 Farmer John 计划好了 M (1 ≤ M ≤ 1,000) 个可以挤奶的时间段。每个时间段有一个开始时间(0 ≤ 开始时间 ≤ N), 和一个结束时间 (开始时间 &lt; 结束时间 ≤ N), 和一个产量 (1 ≤ 产量 ≤ 1,000,000) 表示可以从贝茜挤奶的数量。Farmer John 从分别从开始时间挤奶，到结束时间为止。每次挤奶必须使用整个时间段。 但即使是贝茜也有她的产量限制。每次挤奶以后，她必须休息 R (1 ≤ R ≤ N) 个小时才能下次挤奶。给定Farmer John 计划的时间段，请你算出在 N 个小时内，最大的挤奶的量。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: 10.5pt; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">第</span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体">1</span><span style="font-size: 10.5pt; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">行三个整数</span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体">N</span><span style="font-size: 10.5pt; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">，</span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体">M</span><span style="font-size: 10.5pt; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">，</span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体">R.</span><span style="font-size: 10.5pt; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">接下来</span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体">M</span><span style="font-size: 10.5pt; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">行，每行三个整数</span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体">Si</span><span style="font-size: 10.5pt; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">，</span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体">Ei</span><span style="font-size: 10.5pt; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">，</span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体">Pi</span><span style="font-size: 10.5pt; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">．</span></p></div>

# Output

<div class="content"><p><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体"> </span><span style="font-size: 10.5pt; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">最大产奶量．</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">12 4 2<br/>
1 2 8<br/>
10 12 19<br/>
3 6 24<br/>
7 10 31<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">43</span></div>

# Hint

<div class="content"><p></p><p>注意：结束时间不挤奶</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

