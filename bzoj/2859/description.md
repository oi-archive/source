
# Description

<div class="content"><div>在一个圆环上，有N个地点，这些地点按照逆时针顺序用正整数1..N编号。有些地点间存在直线道路可以到达，但</div>
<div>道路并不是双向的，也就是说如果存在a到b的道路，不一定同时存在b到a的道路。现在你要从某个地点开始，沿着</div>
<div>道路走，每个地点最多被经过一次，并且你走过的道路对应的线段只能在公共端点处相交。但是有时候允许一些特</div>
<div>例，具体说就是你走过的某条道路可以和最初走的道路相交最多一次。</div>
<div>你的任务是求出最多能走过的道路数，并给出一个可行的起点。</div>
<div><img src="/source/bzoj/2859/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMy8xMS5qcGc=.jpg" width="338" height="358" alt=""/></div></div>

# Input

<div class="content"><div>
<div>第一行两个非负整数N, K。如果K = 0表示不允许特例，K = 1表示允许特例。</div>
<div>下面N行，依次描述每个地点可以到达的地点编号。每行以0结束。</div>
<div>N ≤ 500。</div>
</div></div>

# Output

<div class="content"><p>第一行一个非负整数，表示最多可以走的道路数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">7 1<br/>
5 0<br/>
5 0<br/>
7 0<br/>
3 0<br/>
4 0<br/>
4 3 0<br/>
2 1 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Oimaster">鸣谢Oimaster</a></p></div>

