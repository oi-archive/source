
# Description

<div class="content"><div>Farmer John is thinking of selling some of his land to earn a bit of extra income. His property cont</div>
<div>ains n trees (3≤N≤300), each described by a point in the 2D plane, no three of which are collinear</div>
<div>. FJ is thinking about selling triangular lots of land defined by having trees at their vertices; th</div>
<div>ere are of course L =C(n,3)such lots he can consider, based on all possible triples of trees</div>
<div> on his property.A triangular lot has value v if it contains exactly v trees in its interior (the tr</div>
<div>ees on the corners do not count, and note that there are no trees on the boundaries since no three t</div>
<div>rees are collinear). For every v = 0 \ldots N-3, please help FJ determine how many of his L potentia</div>
<div>l lots have value v.</div>
<div>
<div>农夫约翰打算卖掉一些土地来获得额外的收入。他的土地上有N颗树(3 ≤ N ≤ 300)，可以看做一个平面上的点，</div>
<div>并且没有三点在一条直线上。约翰打算出售一块由三棵树构成的三角形土地，当然这样一共有L =C(n,3)种</div>
<div>可能性。如果一个三角形内部有v个点（不含边界），那么这块土地的价值为v。请帮助约翰统计当v = 0 ... N-3</div>
<div>时，分别有多少块三角形土地价值为v。</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N.</div>
<div>The following N lines contain the x and y coordinates of a single tree; </div>
<div>these are both integers in the range 0 \ldots 1,000,000.</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Output N-2 lines, where output line i contains a count of the number of lots having value i-1.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
3 6<br/>
17 15<br/>
13 15<br/>
6 12<br/>
9 1<br/>
2 7<br/>
10 19</span></div>

# Sample Output

<div class="content"><span class="sampledata">28<br/>
6<br/>
1<br/>
0<br/>
0</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum 鸣谢Firstlast提供译文">Platinum 鸣谢Firstlast提供译文</a></p></div>

