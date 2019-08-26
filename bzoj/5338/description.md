
# Description

<div class="content"><div>现在有一颗以1为根节点的由n个节点组成的树，树上每个节点上都有一个权值vi。</div>
<div>现在有Q 次操作，操作如下:</div>
<div>1  x y    查询节点x的子树中与y异或结果的最大值</div>
<div>2 x y z    查询路径x到y上点与z异或结果最大值</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行是两个数字n, Q;</div>
<div>第二行是n个数字用空格隔开，第i个数字vi表示点i上的权值 </div>
<div>接下来n-1行，每行两个数，x,y，表示节点x与y之间有边 </div>
<div>接下来Q行，每一行为一个查询，格式如上所述.</div>
<div>1 &lt; n, Q ≤ 100000 ，查询1中的y ≤ 2^30 ，查询2中的z ≤ 2^30</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每一个查询，输出一行，表示满足条件的最大值。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 5<br/>
1 3 5 7 9 2  4<br/>
1 2<br/>
1 3<br/>
2 4<br/>
2 5<br/>
3 6<br/>
3 7<br/>
1  3 5<br/>
2 4 6 3<br/>
1  5 5<br/>
2 5 7 2<br/>
1  1 9</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
6<br/>
12<br/>
11<br/>
14</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

