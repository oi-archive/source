
# Description

<div class="content"><div style="layout-grid-mode: char; text-indent: 23.65pt"><span style="font-size: medium">Alice和Bob现在要乘飞机旅行，他们选择了一家相对便宜的航空公司。该航空公司一共在n个城市设有业务，设这些城市分别标记为0到n-1，一共有m种航线，每种航线连接两个城市，并且航线有一定的价格。Alice和Bob现在要从一个城市沿着航线到达另一个城市，途中可以进行转机。航空公司对他们这次旅行也推出优惠，他们可以免费在最多k种航线上搭乘飞机。那么Alice和Bob这次出行最少花费多少？</span></div></div>

# Input

<div class="content"><div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium">数据的第一行有三个整数，n,m,k，分别表示城市数，航线数和免费乘坐次数。</span></div>
<div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium">第二行有两个整数，s,t，分别表示他们出行的起点城市编号和终点城市编号。(0&lt;=s,t&lt;n)</span></div>
<div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium">接下来有m行，每行三个整数，a,b,c，表示存在一种航线，能从城市a到达城市b，或从城市b到达城市a，价格为c。(0&lt;=a,b&lt;n,a与b不相等，0&lt;=c&lt;=1000)</span></div>
<div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div style="layout-grid-mode: char"> </div>
<div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium">只有一行，包含一个整数，为最少花费。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 6 1<br/>
0 4<br/>
0 1 5<br/>
1 2 5<br/>
2 3 5<br/>
3 4 5<br/>
2 3 3<br/>
0 2 100<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt 21pt; mso-para-margin-left: 2.0gd"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">对于</span><span lang="EN-US"><font face="Times New Roman">30%</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的数据</span><span lang="EN-US"><font face="Times New Roman">,2&lt;=n&lt;=50,1&lt;=m&lt;=300,k=0;</font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt 21pt; mso-para-margin-left: 2.0gd"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">对于</span><span lang="EN-US"><font face="Times New Roman">50%</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的数据</span><span lang="EN-US"><font face="Times New Roman">,2&lt;=n&lt;=600,1&lt;=m&lt;=6000,0&lt;=k&lt;=1;</font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt 21pt; mso-para-margin-left: 2.0gd"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">对于</span><span lang="EN-US"><font face="Times New Roman">100%</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的数据</span><span lang="EN-US"><font face="Times New Roman">,2&lt;=n&lt;=10000,1&lt;=m&lt;=50000,0&lt;=k&lt;=10.</font></span></font></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

