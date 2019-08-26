
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">22世纪，3013年，在专制的统治和残酷的生存竞争下，回忆早已被人们所抛弃。本该有感情、有灵魂的人们已经彻底沦为统治者的血肉机器，如傀儡一般日夜工作着，如傀儡一般走向战场，如傀儡一般出生，也如傀儡一般死亡。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">“……抛弃了回忆的人，是没有未来的。”</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">魔法结社，一群觉醒了意识的人们为了反抗霸权统治而组成的团体，致力于唤醒人们的灵魂。经过超过10年的努力，终于掌握了能够改变世界的终极魔法——回忆之殿。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">秋，魔法结社的首席魔法师，将要启动回忆之殿。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">回忆之殿由一个回路构成，回路上等距离地环状分布着m个结界。每个结界的中心是一个巨大的魔法柱，结界的周围由不超过n个魔法晶石等距离排列环绕而成。每个原始结界上的魔法晶石都和中间的魔法柱之间有魔法通路，同时也和相邻的魔法晶石之间有魔法通路（特别的，如果结界的周围只有1个魔法晶石，那么该魔法晶石有1条绕过魔法柱一圈并连向自己的魔法通路，如果结界的周围只有2个魔法晶石，那么这两个魔法晶石之间有2条魔法通路分别绕过魔法柱的两侧）。那么显然，由x个魔法晶石组成的原始结界有2x条魔法通路。当然，一个原始结界也可以仅由魔法柱组成，此时魔法柱没有任何连出的魔法通路。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"><img height="129" alt="" width="511" src="source/bzoj/3271/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwOC8xKDQpLmpwZw==.jpg"/></span></div>
<div style="text-indent: 21pt">
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt; mso-char-indent-count: 2.0; mso-pagination: widow-orphan"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">对于成型的结界，中心的魔法柱和周围的每个魔法晶石之间都有且只有</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">条通路，也就是说，由</span><span lang="EN-US"><font face="Times New Roman">x</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个魔法晶石组成的成型的结界是由原始结界中删除</span><span lang="EN-US"><font face="Times New Roman">x</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">条魔法通路，使结界成为一个“树形”连通结构形成，我们称这个连通结构为“魔法阵”。由于魔法晶石是环绕魔法柱分布的，所以两个魔法阵是不同的魔法阵，当且仅当其中一个魔法阵不能通过旋转的方式与另一个魔法阵相同。</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt; mso-char-indent-count: 2.0; mso-pagination: widow-orphan"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><img height="124" alt="" width="547" src="source/bzoj/3271/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwOC8yKDEpLmpwZw==.jpg"/></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt; mso-char-indent-count: 2.0; mso-pagination: widow-orphan"></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt; mso-char-indent-count: 2.0; mso-pagination: widow-orphan"></p>
<span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt; mso-char-indent-count: 2.0; mso-pagination: widow-orphan"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">回忆之殿的魔法一共需要启动</span><span lang="EN-US"><font face="Times New Roman">t</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">次，第</span><span lang="EN-US"><font face="Times New Roman">i</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">次启动需要布置一个由</span><span lang="EN-US"><font face="Times New Roman">m</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个魔法阵总共</span><span lang="EN-US"><font face="Times New Roman">i-1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个魔法晶石构成的回路。同样的，由于回路是环状分布的，所以两个回忆之殿不同当且仅当其中一个回忆之殿的魔法阵不能通过旋转的方式与另一个回忆之殿对应魔法阵全部相同。</span></p>
</span></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt; mso-char-indent-count: 2.0; mso-pagination: widow-orphan"></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt; mso-char-indent-count: 2.0; mso-pagination: widow-orphan"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><img height="132" alt="" width="558" src="source/bzoj/3271/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwOC8zKDIpLmpwZw==.jpg"/></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt; mso-char-indent-count: 2.0; mso-pagination: widow-orphan"></p>
<span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt; mso-char-indent-count: 2.0; mso-pagination: widow-orphan"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">现在，在秋酱施展魔法之前，他想要知道，对于每一次启动回忆之殿，总共有几种可能的本质不同的魔法晶石布置方案满足条件，由于方案可能很多，只要输出答案模</span><span lang="EN-US"><font face="Times New Roman">12289</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的结果就可以了。</span></p>
</span></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt; mso-char-indent-count: 2.0; mso-pagination: widow-orphan"></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt; mso-char-indent-count: 2.0; mso-pagination: widow-orphan"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">“嗯</span><span lang="EN-US"><font face="Times New Roman">~</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">果然，还是不能忘记啊。”</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt; mso-char-indent-count: 2.0; mso-pagination: widow-orphan"></p>
</span></span></div></div>

# Input

<div class="content"><div>包括1行3个正整数m,n,t，意义如题所述。</div>
<div>m,n&lt;=4000,n&lt;=4000,t&lt;=4000;</div>
<div>t&lt;=m*n</div>
<p></p>
<p></p></div>

# Output

<div class="content"><p class="MsoNormalIndent" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">包括</span><span lang="EN-US"><font face="Times New Roman">t+1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行，对于第</span><span lang="EN-US"><font face="Times New Roman">i</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行应该包含</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个非负整数表示由</span><span lang="EN-US"><font face="Times New Roman">i-1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个魔法结晶启动的回忆之殿可能的形态数。</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; mso-pagination: widow-orphan"></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
1<br/>
4<br/>
7<br/>
12</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

