
# Description

<div class="content"><p><span style="font-size: medium">  </span></p>
<div v:shape="_x0000_s1026"><span style="font-size: medium">给定一个边长为2<span style="position: relative; top: -0.45em">n</span>棋盘，其中有M个格子是坏掉的。一个蚂蚁要从棋盘的左上角开始，遍历整个棋盘。每个点必须且仅允许走一遍。蚂蚁走的时候把棋盘分成了四个2<span style="position: relative; top: -0.45em">n-1</span> 个小棋盘，蚂蚁总是走完其中的一个后再继续走下一个，也就是说，在进入一个小棋盘后，它必须把其中的所有点遍历以后才能走其他的点。</span></div>
<div v:shape="_x0000_s1026"><span style="font-size: medium"><img alt="" src="/source/bzoj/2524/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTExMS8xKDgpLmpwZw==.jpg"/></span></div>
<p></p>
<div class="O" v:shape="_x0000_s1026" style="mso-line-spacing: &#39;100 50 0&#39;; mso-char-wrap: 1; mso-kinsoku-overflow: 1"><span style="font-size: medium"><span style="font-family: SimSun; mso-ascii-font-family: SimSun; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-fareast-font-family: SimSun">对于上下左右四个边界，寻找边界上的一个格子，使得该格可以作为蚂蚁访问路线的终点</span></span></div>
<p></p>
<div class="O" v:shape="_x0000_s1026">
<div style="mso-line-spacing: &#39;100 50 0&#39;; mso-char-wrap: 1; mso-kinsoku-overflow: 1"><span style="font-size: medium"><span style="font-family: SimSun; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana; mso-fareast-font-family: SimSun"><b>其中</b></span><span style="font-family: Verdana; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana; mso-fareast-font-family: SimSun"><b><span style="mso-spacerun: yes">  </span>N &lt;= 30 , M &lt;= 50 </b></span></span></div>
<div style="mso-line-spacing: &#39;100 50 0&#39;; mso-char-wrap: 1; mso-kinsoku-overflow: 1"></div>
</div></div>

# Input

<div class="content"></div>

# Output

<div class="content"></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
17<br/>
2 0<br/>
1 0<br/>
3 0<br/>
6 0<br/>
7 0<br/>
6 1<br/>
7 1<br/>
6 2<br/>
7 2<br/>
6 3<br/>
7 3<br/>
0 2<br/>
0 3<br/>
0 6<br/>
0 7<br/>
1 6<br/>
1 7<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">NIE<br/>
NIE<br/>
NIE<br/>
NIE<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

