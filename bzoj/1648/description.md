
# Description

<div class="content"><p><span style="font-size: medium">The cows are having a picnic! Each of Farmer John&#39;s K (1 &lt;= K &lt;= 100) cows is grazing in one of N (1 &lt;= N &lt;= 1,000) pastures, conveniently numbered 1...N. The pastures are connected by M (1 &lt;= M &lt;= 10,000) one-way paths (no path connects a pasture to itself). The cows want to gather in the same pasture for their picnic, but (because of the one-way paths) some cows may only be able to get to some pastures. Help the cows out by figuring out how many pastures are reachable by all cows, and hence are possible picnic locations. </span></p>
<p></p>
<div>  K(1≤K≤100)只奶牛分散在N(1≤N≤1000)个牧场．现在她们要集中起来进餐．牧场之间有M(1≤M≤10000)条有向路连接，而且不存在起点和终点相同的有向路．她们进餐的地点必须是所有奶牛都可到达的地方．那么，有多少这样的牧场呢？</div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Three space-separated integers, respectively: K, N, and M * Lines 2..K+1: Line i+1 contains a single integer (1..N) which is the number of the pasture in which cow i is grazing. * Lines K+2..M+K+1: Each line contains two space-separated integers, respectively A and B (both 1..N and A != B), representing a one-way path from pasture A to pasture B. </span></p>
<p><span style="font-size: medium"><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN"> </span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">第</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">1</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">行输入</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">K</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">，</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">N</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">，</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">M.</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">接下来</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">K</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">行，每行一个整数表示一只奶牛所在的牧场编号．接下来</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">M</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">行，每行两个整数，表示一条有向路的起点和终点</span></span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: The single integer that is the number of pastures that are reachable by all cows via the one-way paths. </span></p>
<p><span style="font-size: medium"><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">    </span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-bidi-language: AR-SA; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN">所有奶牛都可到达的牧场个数</span></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 4 4<br/>
2<br/>
3<br/>
1 2<br/>
1 4<br/>
2 3<br/>
3 4<br/>
<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
4&lt;--3<br/>
^   ^<br/>
|   |<br/>
|   |<br/>
1--&gt;2<br/>
<br/>
The pastures are laid out as shown above, with cows in pastures 2 and 3.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
<br/>
   牧场3，4是这样的牧场．</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

