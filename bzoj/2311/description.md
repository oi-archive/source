
# Description

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">小Z一觉醒来，发现自己在了一个迷宫之中，苦心探索了若干次，却仍然回到了起点。小Z绝望无比，此时，他决定听天由命。</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">具体来说，这个迷宫有n行m列，小Z现在位于(1,1)，只要走到(n,m)就可以马上离开迷宫。某些格子间有墙而无法通过，迷宫的周围也有一圈墙。而对于可以通过的地方，小Z决定按下述规则移动：在每个格子中，随机选择上下左右四个方向移动，概率由小Z按照自己的方向感确定，当然这个概率会满足下述要求：</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; margin-left: 39pt; text-indent: -18pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">1.</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">有墙的方向概率为0。</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; margin-left: 39pt; text-indent: -18pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">2.</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">除了(n,m)，每个格子往四个方向的概率加起来等于1。</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; margin-left: 39pt; text-indent: -18pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">3.</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">一旦到了(n,m)就马上离开迷宫，故从(n,m)往任意方向的概率均为0。</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-align: left"><span style="font-weight: bold; font-size: 12pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">Your Task</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">求出小Z离开迷宫的期望步数。</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;Cambria Math&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<!--EndFragment--></div>

# Input

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第一行n m表示迷宫大小</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">接下来4个n*m的矩阵，第k个矩阵的第i行第j列的数表示了在格子(i,j)时往k方向移动的概率，k=1为向下(i+1,j)，k=2为向右(i,j+1)，k=3为向上(i-1,j)，k=4为向左(i,j-1)</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">由(n,m)往任意方向走的概率均为0</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;Cambria Math&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">输出一个数表示答案，保留三位小数</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-align: justify"><span style="font-weight: bold; font-size: 12pt; color: rgb(255,255,255); font-family: &#39;幼圆&#39;; mso-spacerun: &#39;yes&#39;">样例输入一</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-weight: normal; font-size: 10pt; color: rgb(255,255,255); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">2 </span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;Cambria Math&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">样例输入一<br/>
	2 2<br/>
	0.1 0.1<br/>
	0 0<br/>
	0.9 0<br/>
	0.1 0<br/>
	0 0<br/>
	0.9 0<br/>
	0 0.9<br/>
	0 0<br/>
样例输出一<br/>
	20.000<br/>
样例输入二<br/>
	1 5<br/>
	0.0 0.0 0.0 0.0 0.0<br/>
	1.0 0.1 0.7 0.5 0.0<br/>
	0.0 0.0 0.0 0.0 0.0<br/>
	0.0 0.9 0.3 0.5 0.0<br/>
样例输出二<br/>
	41.143</span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
100%：1≤n,m≤50，迷宫合法，一定可以走到终点，答案不超过10^7<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

