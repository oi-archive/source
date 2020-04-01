
# Description

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">You must have heard of the Knight&#39;s Tour problem. In that problem, a knight is placed on an empty chess board and you are to determine whether it can visit each square on the board exactly once. <br/>
<br/>
Let&#39;s consider a variation of the knight&#39;s tour problem. In this problem, a knight is place on an infinite plane and it&#39;s restricted to make certain moves. For example, it may be placed at (0, 0) and can make two kinds of moves: Denote its current place as (x,y), it can only move to (x+1,y+2) or (x+2,y+1). The goal of this problem is to make the knight reach a destination position as quickly as possible (i.e. make as less moves as possible).</span></div></div>

# Input

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">The first line contains an integer T ( T &lt; 20) indicating the number of test cases. <br/>
Each test case begins with a line containing four integer: fx fy tx ty(-5000&lt;=fx,fy,tx,ty&lt;=5000). The knight is originally placed at (fx, fy) and (tx, ty) is its destination. <br/>
<br/>
The following line contains an integer m(0 &lt; m &lt;= 10), indicating how many kinds of moves the knight can make. <br/>
<br/>
Each of the following m lines contains two integer mx my(-10&lt;=mx,my&lt;=10; |mx|+|my|&gt;0), which means that if a knight stands at (x,y), it can move to (x+mx,y+my).</span></div></div>

# Output

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">Output one line for each test case. It contains an integer indicating the least number of moves needed for the knight to reach its destination. Output &#34;IMPOSSIBLE&#34; if the knight may never gets to its target position.</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
0 0 6 6<br/>
5<br/>
1 2<br/>
2 1<br/>
2 2<br/>
1 3<br/>
3 1<br/>
0 0 5 5<br/>
2<br/>
1 2<br/>
2 1<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
IMPOSSIBLE<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

