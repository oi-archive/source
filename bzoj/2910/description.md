
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium"><span style="color: black">众所周知，涉及数独的题都不会是很难的题目，所以这道题也很简单。</span></span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"><span style="color: black">3*3 </span>Sudoku Puzzle<span style="color: black">: </span><span style="color: black">每行,每列,9个3*3的子矩阵中1~9的每个数恰好出现一次.现在给一个正确的</span>Sudoku Puzzle<span style="color: black">和一个</span>Unsolved Puzzle<span style="color: black">,</span><span style="color: black">问是否可以将</span>Unsolved Puzzle<span style="color: black">空的格子填满后通过给定的5种操作得到那个</span>Sudoku Puzzle<span style="color: black">。操作共有5种：</span></span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"><span style="color: black">1.</span><span style="color: black">顺时针或逆时针旋转整个9*9方格</span></span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"><span style="color: black">2.</span><span style="color: black">交换任一个column segment中的任意两列</span></span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"><span style="color: black">3.</span><span style="color: black">交换任意个row segment中的任意两行</span></span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"><span style="color: black">4.</span><span style="color: black">交换任意两个row segments或column segments</span></span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"><span style="color: black">5.1~9</span><span style="color: black">的数字作一个置换</span></span></div>
<p><img height="252" width="315" alt="" src="/source/bzoj/2910/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIxMi8xMS5qcGc=.jpg"/></p></div>

# Input

<div class="content"><div style="margin: 13pt 0cm"><span style="font-size: medium"><b><span style="font-weight: normal; line-height: 172%">                                                                          </span></b></span></div>
<div style="text-indent: 24pt"><span style="font-size: medium"><span style="color: black">第一行T为测试组数，对于每组数据会先输出9*9的</span>Sudoku Puzzle，<span style="color: black">再输出9*9的</span>Unsolved Puzzle，<span style="color: black">每组测试数据之间有一空行。</span></span></div></div>

# Output

<div class="content"><div style="margin: 13pt 0cm"> </div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium"><span style="color: black">如可行输出一行“Yes”，不可行输出“No”。引号不用输出。</span></span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
963174258<br/>
178325649<br/>
254689731<br/>
821437596<br/>
496852317<br/>
735961824<br/>
589713462<br/>
317246985<br/>
642598173<br/>
060104050<br/>
200000001<br/>
008305600<br/>
800407006<br/>
006000300<br/>
700901004<br/>
500000002<br/>
040508070<br/>
007206900<br/>
 <br/>
534678912<br/>
672195348<br/>
198342567<br/>
859761423<br/>
426853791<br/>
713924856<br/>
961537284<br/>
287419635<br/>
345286179<br/>
010900605<br/>
025060070<br/>
870000902<br/>
702050043<br/>
000204000<br/>
490010508<br/>
107000056<br/>
040080210<br/>
208001090<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Yes<br/>
No<br/>
【数据规模】<br/>
100%：T&lt;=5.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

