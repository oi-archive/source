
# Description

<div class="content"><p align="left" style="margin-bottom: 18.7pt;" class="MsoNormal">After trying hard for many years, Byteasar has finally received a pilot license. To celebrate the fact, he intends to buy himself an airplane and fly around the planet 3-SATurn (as you may have guessed, this is the planet on which Byteotia is located). Specifically, Byteasar plans to fly along the equator. Unfortunately, the equator is rather long, necessitating refuels. The flight range (on full tank) of each aircraft is known. There is a number of airports along the equator, and a plane can be refueled when it lands on one. Since buying an airplane is a big decision, Byteasar asks your help. He is about to present you with a list of different plane models he is considering. Naturally, these differ in their flight range. For each plane model, he would like to know the minimum number of landings (including the final one) he would have to make in order to complete the journey. Note that for each airplane model, the journey may start at a different airport.</p>
<p align="left" style="margin-bottom: 18.7pt;" class="MsoNormal"><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">通过几年的努力，</span><span lang="EN-US">Byteasar</span><span style="font-family:宋体;mso-ascii-font-family:
Calibri;mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">最终拿到了飞行员驾驶证。为了庆祝这一事实，他打算买一架飞机并且绕</span><span lang="EN-US">Byteotia</span><span style="font-family:宋体;mso-ascii-font-family:
Calibri;mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">星球赤道飞行一圈。但不幸的是赤道非常长所以需要中途加几次油。现在已知赤道上面所有飞机场，所有飞机从飞机场起飞降落也可以加油。因为买飞机是个十分重大的决定，</span><span lang="EN-US">Byteasar</span><span style="font-family:宋体;mso-ascii-font-family:
Calibri;mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">决定寻求你的帮助。他将会让你模拟不同的飞行路线。自然这些飞机一次能走的航程是不同的。对于每次模拟，他想要知道最少需要降落多少次（包括最后一次）。需要注意的是起点可以任意选取。</span><span lang="EN-US"><br/>
</span></p>
<p align="left" class="MsoNormal"></p>
<p class="MsoNormal"></p>
<p></p></div>

# Input

<div class="content"><div>The second line contains  N positive integers L1,L2…Ln(L1+L2+..+Ln&lt;=10^9), separated by single spaces, specifying the distances between successive airports along the equator. The number Li is the distance between the i-th and (i+1)-st (or N-th and first if i=N) in kilometers.</div>
<div><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">第一行有两个正整数</span><span lang="EN-US">n</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">和</span><span lang="EN-US">s</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">（</span><span lang="EN-US">2&lt;=n&lt;=1000000</span><span style="font-family:宋体;mso-ascii-font-family:
Calibri;mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">，</span><span lang="EN-US">1&lt;=s&lt;=100</span><span style="font-family:宋体;mso-ascii-font-family:
Calibri;mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">）分别代表赤道上面的飞机场个数和询问的航班数</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">第二行有</span><span lang="EN-US">n</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">个正整数</span><span lang="EN-US">L1,L2…Ln</span><span style="font-family:宋体;mso-ascii-font-family:
Calibri;mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">（</span><span lang="EN-US">L1+L2+…+Ln&lt;=10^9</span><span style="font-family:宋体;mso-ascii-font-family:
Calibri;mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">）按顺序给出了</span><span lang="EN-US">n</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">个相邻机场之间的距离。其中</span><span lang="EN-US">Li</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">是第</span><span lang="EN-US">i</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">个与第</span><span lang="EN-US">i+1</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">个机场之间的距离，</span><span lang="EN-US">Ln</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">是第</span><span lang="EN-US">n</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">个和第</span><span lang="EN-US">1</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">个之间的距离。</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">第三行给出了</span><span lang="EN-US">n</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">个正整数</span><span lang="EN-US">di</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">（</span><span lang="EN-US">1&lt;=di&lt;=L1+L2+</span><span style="font-family:宋体;mso-ascii-font-family:
Calibri;mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">…</span><span lang="EN-US">+Ln</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">）。其中</span><span lang="EN-US">di</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">代表第</span><span lang="EN-US">i</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">个飞机一次能走的航程。</span></div>
<div></div>
<div></div>
<div></div>
<div>
<p align="left" class="MsoNormal"></p>
</div>
<p></p></div>

# Output

<div class="content"><div>Your program should print S lines to the standard output: the i-th of these should contain a single integer, namely, the minimum lumber of flight segments (and thus also landings) necessary to fly the i-th airplane around the planet 3-SATurn along the equator, starting at an airport of choice, or the word NIE (Polish for no) if it is impossible to complete the journey with this airplane.</div>
<div><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">输出</span><span lang="EN-US">s</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">行每行一个整数代表最小降落次数或者一个字符串</span><span lang="EN-US">“NIE”</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:
minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin">代表不能到达</span></div>
<div></div>
<div></div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 4<br/>
2 2 1 3 3 1<br/>
3 2 4 11</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
NIE<br/>
3<br/>
2<br/>
</span></div>

# Hint

<div class="content"><p></p><div>The thick solid line shows the optimal journey of the plane with flight range 4, whereas the dashed line the optimal journey of the plane with flight range 3.</div><br/>
<div></div><br/>
<div> </div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

