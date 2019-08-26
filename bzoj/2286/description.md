
# Description

<div class="content"><div>在一场战争中，战场由n个岛屿和n-1个桥梁组成，保证每两个岛屿间有且仅有一条路径可达。现在，我军已经侦查到敌军的总部在编号为1的岛屿，而且他们已经没有足够多的能源维系战斗，我军胜利在望。已知在其他k个岛屿上有丰富能源，为了防止敌军获取能源，我军的任务是炸毁一些桥梁，使得敌军不能到达任何能源丰富的岛屿。由于不同桥梁的材质和结构不同，所以炸毁不同的桥梁有不同的代价，我军希望在满足目标的同时使得总代价最小。</div>
<div>侦查部门还发现，敌军有一台神秘机器。即使我军切断所有能源之后，他们也可以用那台机器。机器产生的效果不仅仅会修复所有我军炸毁的桥梁，而且会重新随机资源分布（但可以保证的是，资源不会分布到1号岛屿上）。不过侦查部门还发现了这台机器只能够使用m次，所以我们只需要把每次任务完成即可。</div></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第一行一个整数</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;">n</span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，代表岛屿数量。</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">接下来</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;">n-1</span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行，每行三个整数</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;">u,v,w</span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，代表</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;">u</span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">号岛屿和</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;">v</span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">号岛屿由一条代价为</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;">c</span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的桥梁直接相连，保证</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;">1&lt;=u,v&lt;=n</span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">且</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;">1&lt;=c&lt;=100000</span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;">n+1</span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行，一个整数</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;">m</span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，代表敌方机器能使用的次数。</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">接下来</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;">m</span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行，每行一个整数</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;">k<sub>i</sub></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，代表第</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;">i</span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">次后，有</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;">k<sub>i</sub></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个岛屿资源丰富，接下来</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;">k</span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个整数</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;">h<sub>1</sub>,h<sub>2</sub>,…h<sub>k</sub></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，表示资源丰富岛屿的编号。</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span style="font-size: 12pt; font-family: 宋体;">输出有</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;">m</span><span style="font-size: 12pt; font-family: 宋体;">行，分别代表每次任务的最小代价。</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;"> </span></p>
<p class="NOI" style="margin: 13pt 0cm"><a name="OLE_LINK5"></a><a name="OLE_LINK4"></a><a name="OLE_LINK3"></a><a name="OLE_LINK2"></a></p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
1 5 13<br/>
1 9 6<br/>
2 1 19<br/>
2 4 8<br/>
2 3 91<br/>
5 6 8<br/>
7 5 4<br/>
7 8 31<br/>
10 7 9<br/>
3<br/>
2 10 6<br/>
4 5 7 8 3<br/>
3 9 4 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">12<br/>
32<br/>
22</span></div>

# Hint

<div class="content"><p></p><p> 对于100%的数据，2&lt;=n&lt;=250000,m&gt;=1,sigma(ki)&lt;=500000,1&lt;=ki&lt;=n-1</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Stage2 day2">Stage2 day2</a></p></div>

