
# Description

<div class="content"><div>Nothing is more beautiful than square! So, given a grid of cells, each cell being black or white, it is reasonable to evaluate this grid’s beautifulness by the side length of its maximum continuous subsquare which fully consists of white cells.<br/>
Now you’re given an N × N grid, and the cells are all black. You can paint some cells white. But other cells are broken in the sense that they cannot be paint white. For each integer i between 0 and N inclusive, you want to find the number of different painting schemes such that the beautifulness is exactly i. Two painting schemes are considered different if and only if some cells have different colors. Painting nothing is considered to be a scheme.</div>
<div><img width="820" height="324" src="/source/bzoj/3905/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwMy92MS5qcGc=.jpg" alt=""/><br/>
For example, N = 3 and there are 4 broken cells as shouwn in Fig. J(a). There are 2 painting schemes for i=2 as shown in Fig. J(b) and J(c).<br/>
You just need to output the answer modulo 10^9 + 7.</div>
<div>给你一个n * n(n &lt;= 8)的棋盘，上面有一些格子必须是黑色，其它可以染<br/>
黑或者染白，对于一个棋盘，定义它的优美度为它上面最大的连续白色<br/>
子正方形的边长，对于每个0 &lt;= i &lt;= n，问有多少种染色方案使得棋盘的<br/>
优美度为i？</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line contains an integer T (T ≤ 10) denoting the number of the test cases.<br/>
For  each test case, the first line contains an integer N (1 ≤ N ≤ 8),  denoting the size of the grid is N × N . Then N lines follow, each line  containing an N-character string of “o” and “*”, where “o” stands for a  paintable cell and “*” for a broken cell.</div>
<div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>For each test case, for each integer i between 0 and N inclusive, output the answer in a single line.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3<br/>
oo*<br/>
ooo<br/>
***<br/>
8<br/>
oooooooo<br/>
oooooooo<br/>
oooooooo<br/>
oooooooo<br/>
oooooooo<br/>
oooooooo<br/>
oooooooo<br/>
oooooooo</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
29<br/>
2<br/>
0<br/>
1<br/>
401415247<br/>
525424814<br/>
78647876<br/>
661184312<br/>
550223786<br/>
365317939<br/>
130046<br/>
1</span></div>

# Hint

<div class="content"><p></p><p></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2014 Asia AnShan Regional Contest ">2014 Asia AnShan Regional Contest </a></p></div>

