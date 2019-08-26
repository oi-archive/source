
# Description

<div class="content"><p class="NOI1" style="margin: 13pt 0cm"><a name="OLE_LINK7"></a><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">从</span><span lang="EN-US"><font face="Times New Roman">APIO</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">回来之后，</span><span lang="EN-US"><font face="Times New Roman">XX</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">便迷上了“战火星空”这个游戏。</span></font></p>
<p class="NOI" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">原版战火星空中，有一架小飞机和一个</span><span lang="EN-US"><font face="Times New Roman">Boss</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，玩家控制小飞机来对</span><span lang="EN-US"><font face="Times New Roman">Boss</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">进行射击。然而，这种“一对一”的游戏已经让</span><span lang="EN-US"><font face="Times New Roman">XX</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">乏味，于是</span><span lang="EN-US"><font face="Times New Roman">XX</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">基于原版战火星空，将其加强创造了一款新版战火星空。</span></font></p>
<p class="NOI" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">新版战火星空中，有</span><span lang="EN-US"><font face="Times New Roman">N</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个</span><span lang="EN-US"><font face="Times New Roman">Boss</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><font face="Times New Roman">M</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">架小飞机。在游戏过程中，</span><span lang="EN-US"><font face="Times New Roman">Boss</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的位置不会改变，而小飞机在从</span><span lang="EN-US"><font face="Times New Roman">(Sx, Sy)</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">到</span><span lang="EN-US"><font face="Times New Roman">(Ex, Ey)</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的线段以速度</span><span lang="EN-US"><font face="Times New Roman">V</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">匀速飞行，并在到达终点后从地图上消失；小飞机的子弹具有</span><span lang="EN-US"><font face="Times New Roman">R</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的射程，在任意时刻，小飞机可以向在射程内的</span><span lang="EN-US"><font face="Times New Roman">Boss</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">射击；而为了使实力更加均衡，游戏还规定在任意时刻，每个</span><span lang="EN-US"><font face="Times New Roman">Boss</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">只能被一架小飞机作为目标射击；每架小飞机也有一个能量值</span><span lang="EN-US"><font face="Times New Roman">E</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的限制，若某时刻小飞机向</span><span lang="EN-US"><font face="Times New Roman">K</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个</span><span lang="EN-US"><font face="Times New Roman">Boss</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">射击，则每秒需要消耗</span><span lang="EN-US"><font face="Times New Roman">K</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个单位的能量，所有能量消耗完之后小飞机不再能够进行射击。</span></font></p>
<p class="NOI" style="margin: 0cm 0cm 0pt; text-indent: 21pt; mso-char-indent-count: 0"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">在游戏开始前，</span><span lang="EN-US"><font face="Times New Roman">XX</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">知道了所有</span><span lang="EN-US"><font face="Times New Roman">Boss</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的位置，以及每架小飞机的飞行路线以及各项属性，他想知道所有</span><span lang="EN-US"><font face="Times New Roman">Boss</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">被攻击的总时间最大是多少，你能帮助他吗？</span></font></p>
<p></p></div>

# Input

<div class="content"><p class="NOI" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第一行包含两个整数</span><span lang="EN-US"><font face="Times New Roman">N</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">M</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，分别表示</span><span lang="EN-US"><font face="Times New Roman">Boss</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和小飞机的个数。</span></font></p>
<p class="NOI" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">接下来</span><span lang="EN-US"><font face="Times New Roman">N</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行，每行一个正整数点坐标</span><span lang="EN-US"><font face="Times New Roman">(x, y)</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，表示</span><span lang="EN-US"><font face="Times New Roman">Boss</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">所在的位置。</span></font></p>
<p class="NOI" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">接下来</span><span lang="EN-US"><font face="Times New Roman">M</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行，每行七个正整数：</span><span lang="EN-US"><font face="Times New Roman">Sx, Sy, Ex, Ey, V, R, E</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，表示每架小飞机的运动路线、速度、射程以及能量值。</span></font></p>
<p class="NOI" style="margin: 0cm 0cm 0pt"></p></div>

# Output

<div class="content"><p class="NOI" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">输出一个实数，表示所有</span><span lang="EN-US"><font face="Times New Roman">Boss</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">被攻击的最大总时间，保留</span><span lang="EN-US"><font face="Times New Roman">6</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">位小数。</span></font></p>
<p class="NOI0" style="margin: 13pt 0cm"></p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
样例1：<br/>
<br/>
1 1<br/>
<br/>
2 2<br/>
<br/>
1 1 5 3 2 1 2<br/>
<br/>
 <br/>
<br/>
样例2：<br/>
<br/>
2 4<br/>
<br/>
12 10<br/>
<br/>
7 5<br/>
<br/>
10 10 12 10 1 1 3<br/>
<br/>
6 1 8 10 1 2 3<br/>
<br/>
3 6 8 2 5 3 1<br/>
<br/>
42 42 42 42 6 6 6<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例1：<br/>
<br/>
0.894427<br/>
<br/>
 <br/>
<br/>
样例2：<br/>
<br/>
4.983771<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
对于30%的数据，保证每个Boss在任意时刻只在最多一架小飞机的射程范围内。对于100%的数据，1≤N，M≤20，输入的所有数均为正整数，且不超过1000。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

