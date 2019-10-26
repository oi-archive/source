
# Description

<div class="content"><div><span style="font-size: medium">    农夫约翰有N(2≤N≤40000)个农场，标号1到N,M(2≤M≤40000)条的不同的垂直或水</span></div>
<div><span style="font-size: medium">平的道路连结着农场，道路的长度不超过1000.这些农场的分布就像下面的地图一样，</span></div>
<div><span style="font-size: medium"><img height="250" width="231" alt="" src="/source/bzoj/3362/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS8yMigxKS5qcGc=.jpg"/></span></div>
<div><span style="font-size: medium">图中农场用F1..F7表示, 每个农场最多能在东西南北四个方向连结4个不同的农场．此外，农场只处在道路的两端．道路不会交叉且每对农场间有且仅有一条路径．邻居鲍伯要约翰来导航，但约翰丢了农场的地图，他只得从电脑的备份中修复了．每一条道路的信息如下：</span></div>
<div><span style="font-size: medium">从农场23往南经距离10到达农场17</span></div>
<div><span style="font-size: medium">从农场1往东经距离7到达农场17</span></div>
<div><span style="font-size: medium">    当约翰重新获得这些数据时，他有时被的鲍伯的问题打断：“农场1到农场23的曼哈顿距离是多少？”所谓在(XI，Yi)和(X2，y2)之间的“曼哈顿距离”，就是lxl - X21+lyl - y21．如果已经有足够的信息，约翰就会回答这样的问题（在上例中答案是17），否则他会诚恳地抱歉并回答-1.</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第1行：两个分开的整数N和M.</span></div>
<div><span style="font-size: medium">    第2到M+1行：每行包括4个分开的内容，F1，F2，三，D分别描述两个农场的编号，道路的长度，F1到F2的方向N，E，S，w．</span></div>
<div><span style="font-size: medium">    第M+2行：一个整数，K(1≤K≤10000)，表示问题个数．</span></div>
<div><span style="font-size: medium">    </span><span style="font-size: medium">第M+3到M+K+2行：每行表示一个问题，由3部分组成：Fi，F2，，．其中Fi和F2表示两个被问及的农场．而/(1≤J≤M)表示问题提出的时刻．J为1时，表示得知信息1但未得知信息2时．</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">    第1到K行：每行一个整数，回答问题．表示两个农场间的曼哈顿距离．不得而知则输出-1.</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">7 6<br/>
1 6 13 E<br/>
6 3 9 E<br/>
3 5 7 S<br/>
4 1 3 N<br/>
2 4 20 W<br/>
4 7 2 S<br/>
3<br/>
1 6 1<br/>
1 4 3<br/>
2 6 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">13<br/>
-1<br/>
10</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Times New Roman">   </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">在时刻</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，约翰知道</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">到</span><span lang="EN-US"><font face="Times New Roman">6</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的距离为</span><span lang="EN-US"><font face="Times New Roman">13;</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">在时刻</span><span lang="EN-US"><font face="Times New Roman">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">到</span><span lang="EN-US"><font face="Times New Roman">4</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的距离仍然不知道；在时刻</span><span lang="EN-US"><font face="Times New Roman">6</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，位置</span><span lang="EN-US"><font face="Times New Roman">6</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">向</span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">北</span><span lang="EN-US"><font face="Times New Roman">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个距离，向西</span><span lang="EN-US"><font face="Times New Roman">7</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个距离于位置</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，所以距离为</span><span lang="EN-US"><font face="Times New Roman">10.</font></span></font></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Green">Green</a></p></div>

