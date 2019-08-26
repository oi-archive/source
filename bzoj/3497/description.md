
# Description

<div class="content"><p><span style="font-size: medium">一个大小为m的轮盘，上面有a个白棋子，b个黑棋子。<br/>
白棋先行，每次可以走到一个中间没有任何棋子的位<br/>
。例如下图中，8号棋子可以走到1、7、9-个位置。</span></p>
<p><span style="font-size: medium"><img height="159" width="169" alt="" src="source/bzoj/3497/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMy8xMSg0KS5qcGc=.jpg"/></span></p>
<p><span style="font-size: medium">哪方先不能移动就输。问哪方能赢，或者判断游戏永远<br/>
  无法结束。<br/>
 1 &lt; =M&lt;= 1000000000,1&lt;=a+b&lt;= 1000000。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">The first line of the standard input contains one integer t representing the number of boards to be considered. The following lines contain descriptions of respective boards, each of which consists of three lines. In the first line there are three integers m, b and c (1&lt;=M&lt;=10^9,1&lt;=b,c) separated by single spaces and denoting the length of the board, the number of white pieces and the number of black pieces. In the second line there is an increasing sequence of b integers (in the range 1……m) representing the positions of white pieces. In the third line there is an increasing sequence of integers (in the range 1……m) representing the positions of black pieces. The total number of pieces in all boards does not exceed 10^6. </span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">Exactly lines with answers for consecutive boards should be written to the standard output. The answer is always a single character: B, C, or R, depending on whether the white player wins (B), the black player wins (C) or the game never ends (R). <br/>
</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
9 2 3<br/>
3 8<br/>
2 5 6<br/>
6 2 2<br/>
5 6<br/>
2 4<br/>
7 1 1<br/>
3<br/>
4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">C<br/>
B<br/>
R<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

