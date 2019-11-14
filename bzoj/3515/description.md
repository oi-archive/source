
# Description

<div class="content"><div style="margin: 0cm 0cm 10pt; line-height: 115%" align="left"><span style="font-size: medium"><span style="line-height: 115%">有一个迷宫，迷宫由房间和单向的走廊组成。每条走廊都是从一个房间单向走向另一个房间。房间编号为0到N-1。迷宫有一个性质，对于每个房间，一旦通过走廊离开房间，则无法再回到这个房间。</span></span></div>
<div style="margin: 0cm 0cm 10pt; line-height: 115%" align="left"><span style="font-size: medium"><span style="line-height: 115%">每个房间可能或者不可能包含一个障碍物。有障碍物的房间则无法通过。</span></span></div>
<div style="margin: 0cm 0cm 10pt; line-height: 115%" align="left"><span style="font-size: medium"><span style="line-height: 115%">如果有K个房间可能包含障碍物，则整个迷宫有2^K种状态。问在这些状态中，有多少种状态，从0号房间到1号房间有偶数条路径。</span></span></div></div>

# Input

<div class="content"><div style="margin: 0cm 0cm 10pt; line-height: 115%" align="left"><span style="font-size: medium"><span style="line-height: 115%">第一行一个整数N。</span></span></div>
<div style="margin: 0cm 0cm 10pt; line-height: 115%" align="left"><span style="font-size: medium"><span style="line-height: 115%">第二行一个长度为N的字符串，第i个字符为-或?。-表示第i-1个房间不含有障碍物，?表示第i-1个房间可能含有障碍物。</span></span></div>
<div style="margin: 0cm 0cm 10pt; line-height: 115%" align="left"><span style="font-size: medium"><span style="line-height: 115%">第三行至结束是一个邻接矩阵，第i行第j列为Y则表示房间i到j有一条单向走廊。</span></span></div></div>

# Output

<div class="content"><div style="margin: 0cm 0cm 10pt; line-height: 115%" align="left"> </div>
<div style="margin: 0cm 0cm 10pt; line-height: 115%" align="left"><span style="font-size: medium"><span style="line-height: 115%">一个整数，如题目中描述。</span></span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
--???<br/>
NYYNN<br/>
NNNNY<br/>
NYNNN<br/>
YNNNN<br/>
NNNNN<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" align="left" style="margin: 0cm 0cm 10pt; line-height: 115%; text-align: left; mso-layout-grid-align: none"><span style="font-size: 11pt; line-height: 115%; font-family: 宋体; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: 宋体; mso-font-kerning: 0pt; mso-ansi-language: ZH-CN">对于100%的数据，1&lt;=N&lt;=50，邻接矩阵中最多有500个Y，?最多有32个，0号和1号房间不会有可能有障碍物。<o:p></o:p></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

