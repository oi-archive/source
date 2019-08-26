
# Description

<div class="content"><p><span style="font-size: medium"><img height="321" width="777" alt="" src="source/bzoj/3317/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMxMS9mcHJvYi5qcGc=.jpg"/></span></p>
<p></p>
<div class="O" v:shape="_x0000_s1026">
<div style="mso-line-spacing: &#39;100 -48 0&#39;; mso-margin-left-alt: 230; mso-text-indent-alt: 52; mso-char-wrap: 1; mso-kinsoku-overflow: 1"><span style="font-size: medium"><span style="left: -2.91%; color: #3891a7; font-family: &#34;Wingdings 2&#34;; position: absolute; top: 0.22em; mso-special-format: bullet; mso-color-index: 4"></span><span style="font-family: 宋体; mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial">一个</span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial; mso-fareast-language: ZH-CN"><i>m</i></span><span lang="EN-US" style="font-family: 宋体; mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial; mso-fareast-language: ZH-CN">×</span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial; mso-fareast-language: ZH-CN"><i>n</i></span><span style="font-family: 宋体; mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial">的棋盘，左上至右下编号为</span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial; mso-fareast-language: ZH-CN">(1, 1)</span><span style="font-family: 宋体; mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial">至</span><span style="mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial"> </span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial; mso-fareast-language: ZH-CN">(</span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial; mso-fareast-language: ZH-CN"><i>m</i></span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial; mso-fareast-language: ZH-CN">, </span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial; mso-fareast-language: ZH-CN"><i>n</i></span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial; mso-fareast-language: ZH-CN">)</span><span style="font-family: 宋体; mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial">，并给定每个格子到周围四个格子的概</span><span style="font-family: 宋体; mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial">率　　。 </span></span></div>
<div style="mso-line-spacing: &#39;100 -48 0&#39;; mso-margin-left-alt: 230; mso-text-indent-alt: 52; mso-char-wrap: 1; mso-kinsoku-overflow: 1"><span style="font-size: medium"><span style="left: -2.82%; color: #3891a7; font-family: &#34;Wingdings 2&#34;; position: absolute; top: 0.22em; mso-special-format: bullet; mso-color-index: 4"></span><span style="font-family: 宋体; mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial">一个骑士从</span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial; mso-fareast-language: ZH-CN">(1, 1)</span><span style="font-family: 宋体; mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial">开始，按照给定概率走，问到</span><span style="font-family: 宋体; mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial">达</span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial; mso-fareast-language: ZH-CN">(</span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial; mso-fareast-language: ZH-CN"><i>m</i></span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial; mso-fareast-language: ZH-CN">, </span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial; mso-fareast-language: ZH-CN"><i>n</i></span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial; mso-fareast-language: ZH-CN">)</span><span style="font-family: 宋体; mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial">的期望步数。 </span></span></div>
<div style="mso-line-spacing: &#39;100 -48 0&#39;; mso-margin-left-alt: 230; mso-text-indent-alt: 52; mso-char-wrap: 1; mso-kinsoku-overflow: 1"><span style="font-size: medium"><span style="left: -2.8%; color: #3891a7; font-family: &#34;Wingdings 2&#34;; position: absolute; top: 0.22em; mso-special-format: bullet; mso-color-index: 4"></span><span style="font-family: 宋体; mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial">题目保证从任一格开始到</span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial; mso-fareast-language: ZH-CN">(m, n)</span><span style="font-family: 宋体; mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial">的概率均为</span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial; mso-fareast-language: ZH-CN">1 </span><span style="font-family: 宋体; mso-fareast-font-family: 宋体; mso-hansi-font-family: Arial">。</span></span></div>
</div></div>

# Input

<div class="content"><p><img height="456" width="781" alt="" src="source/bzoj/3317/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMxMS9maW4uanBn.jpg"/></p></div>

# Output

<div class="content"><p><img height="78" alt="" width="779" src="source/bzoj/3317/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMxMS9mb3V0LmpwZw==.jpg"/></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 2<br/>
0.01 0.50<br/>
0.00 0.00<br/>
0.99 0.00<br/>
0.50 0.00<br/>
0.00 0.00<br/>
0.50 0.00<br/>
0.00 0.50<br/>
0.00 0.00<br/>
1 5<br/>
0.0 0.0 0.0 0.0 0.0<br/>
1.0 0.1 0.7 0.5 0.0<br/>
0.0 0.0 0.0 0.0 0.0<br/>
0.0 0.9 0.3 0.5 0.0<br/>
3 3<br/>
0.000001 0.0 1.0<br/>
0.0 1.0 1.0<br/>
0.0 0.0 0.0<br/>
0.999999 1.0 0.0<br/>
1.0 0.0 0.0<br/>
0.000001 0.000001 0.0<br/>
0.0 0.0 0.0<br/>
0.0 0.0 0.0<br/>
0.999999 0.0 0.0<br/>
0.0 0.0 0.0<br/>
0.0 0.0 0.0<br/>
0.0 0.999999 0.0<br/>
0 0<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4.0<br/>
41.142857142857146<br/>
7.999994000002</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=WCMG提供SPJ">WCMG提供SPJ</a></p></div>

