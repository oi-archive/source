
# Description

<div class="content"><div align="center"></div>
<div style="text-indent: 21pt"><span style="font-size: medium">绿色游戏是一种两人游戏，双方分别称Ann和Billy。游戏的内容主要是轮流在棋盘上移动一颗棋子。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">棋盘上的点一部分是绿色的，其余是白色的；全部从1至a+b编号。编号1至a的点属于Ann，编号(a+1)至(a+b)的点属于Billy。每个点都有一些后继点，均可一步到达。属于Ann的点的后继点一定属于Billy，反之亦然。所有的点都至少有一个后继点，这样总可以往下走一步。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">游戏开始时把棋子放在任意的一点P上，然后双方轮流移动棋子至当前所在点（属于移动方）的一个后继点上（属于对手）。游戏由点P的拥有者开始，结束时棋子第二次到达了某一点，称点Q。如果在从点Q至点Q的一连串移动中，棋子至少一次被放到绿色点上，则Ann赢。若从点P开始，不管Billy如何移动，Ann总能保证赢得这次游戏，则称Ann对起始点P有必胜的策略。</span></div>
<div><span style="font-size: medium"><b>任务：</b></span></div>
<div><span style="font-size: medium">       编写一个程序，完成下列工作：</span></div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"><span style="font-size: medium">1、 读入对棋盘的描述；</span></div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"><span style="font-size: medium">2、 算出Ann有必胜策略的起始点；</span></div></div>

# Input

<div class="content"><div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"><span style="font-size: medium">首行有两个整数a和b，两个整数之间用一个空格分开，分别表示属于Ann和Billy的点数(1≤a，b≤3000)。以下a+b行是对各点的描述，先描述Ann的点，再描述Billy的点。第i+1行（1≤i≤a+b）以整数z，k开始：z表示点i的颜色(O－白色，I－绿色)，k表示后继点的数目。然后是K个整数（1≤k＜a+b），写在同一行，代表点i后继点的编号，这些整数均用一个空格分开。绿点的个数不超过100，所有点的后继点的个数之和不超过30000。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">首行仅一个整数L，代表Ann有L个有必胜策略的起始点。以下L行按升序顺序依次给出这些点的编号。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
0 2 6 7<br/>
0 3 6 7 8<br/>
0 1 8<br/>
1 1 7<br/>
1 1 8<br/>
1 2 1 2<br/>
0 2 1 2<br/>
0 2 3 4 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
1<br/>
2<br/>
4<br/>
6<br/>
7</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

