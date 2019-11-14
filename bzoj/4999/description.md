
# Description

<div class="content"><div>给您一颗树，每个节点有个初始值。</div>
<div>现在支持以下两种操作：</div>
<div>1. C i x(0&lt;=x&lt;2^31) 表示将i节点的值改为x。</div>
<div>2. Q i j x(0&lt;=x&lt;2^31) 表示询问i节点到j节点的路径上有多少个值为x的节点。</div>
<div></div></div>

# Input

<div class="content"><div>第一行有两个整数N,Q（1 ≤N≤ 100,000；1 ≤Q≤ 200,000），分别表示节点个数和操作个数。</div>
<div>下面一行N个整数，表示初始时每个节点的初始值。</div>
<div>接下来N-1行，每行两个整数x,y，表示x节点与y节点之间有边直接相连（描述一颗树）。</div>
<div>接下来Q行，每行表示一个操作，操作的描述已经在题目描述中给出。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每个Q输出单独一行表示所求的答案。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 6<br/>
10 20 30 40 50<br/>
1 2<br/>
1 3<br/>
3 4<br/>
3 5<br/>
Q 2 3 40<br/>
C 1 40<br/>
Q 2 3 40<br/>
Q 4 5 30<br/>
C 3 10<br/>
Q 4 5 30</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
1<br/>
1<br/>
0</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢佚名上传">鸣谢佚名上传</a></p></div>

