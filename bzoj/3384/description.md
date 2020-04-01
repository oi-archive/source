
# Description

<div class="content"><div><span style="font-size: medium">    很少有人知道奶牛爱吃苹果．农夫约翰的农场上有两棵苹果树（编号为1和2），每一棵树上都长满了苹果．奶牛贝茜无法摘下树上的苹果，所以她只能等待苹果从树上落下．但是，由于苹果掉到地上会摔烂，贝茜必须在半空中接住苹果（没有人爱吃摔烂的苹果）．贝茜吃东西很快，所以她接到苹果后仅用几秒钟就能吃完．每一分钟，两棵苹果树其中的一棵会掉落一个苹果．贝茜已经过了足够的训练，只要站在树下就一定能接住这棵树上掉落的苹果．同时，贝茜能够在两棵树之间快速移动（移动时间远少于1分钟），因此当苹果掉落时，她必定站在两棵树其中的一棵下面．此外，奶牛不愿意不停地往返于两棵树之间，因此会错过一些苹果, 苹果每分钟掉落一个，共T(1≤T≤1000)分钟，贝茜最多愿意移动W(I≤w≤30)次．现给</span></div>
<div><span style="font-size: medium">出每分钟掉落苹果的树的编号，要求判定贝茜能够接住的最多苹果数．开始时贝茜在1号树下．</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第1行：由空格隔开的两个整数T和W.</span></div>
<div><span style="font-size: medium">    第2到T+1行：1或2（每分钟掉落苹果的树的编号）．</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">    在贝茜移动次数不超过W的前提下她能接到的最多苹果数</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">7 2<br/>
2<br/>
1<br/>
1<br/>
2<br/>
2<br/>
1<br/>
1</span></div>

# Sample Output

<div class="content"><span class="sampledata">6</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Times New Roman">  7</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">分钟内共掉落</span><span lang="EN-US"><font face="Times New Roman">7</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个苹果一一第</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个从第</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">棵树上掉落，接下来的</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个苹果从第</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">棵树上掉落，再接下来的</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个从第</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">棵树上掉落，最后</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个从第</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">棵树上掉落．</span><span lang="EN-US"><font face="Times New Roman">   </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">贝茜不移动直到接到从第</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">棵树上掉落的两个苹果，然后移动到第</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">棵树下，直到接到从第</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">棵</span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">树上掉落的两个苹果，最后移动到第</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">棵树下，接住最后两个从第</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">棵树上掉落的苹果．这样贝茜共接住</span><span lang="EN-US"><font face="Times New Roman">6</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个苹果．</span></font></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

