
# Description

<div class="content"><div>发生了火警，所有人员需要紧急疏散！假设每个房间是一个N M的矩形区域。每个格子如果是&#39;.&#39;，那么表示这是一</div>
<div>块空地；如果是&#39;X&#39;，那么表示这是一面墙，如果是&#39;D&#39;，那么表示这是一扇门，人们可以从这儿撤出房间。已知门</div>
<div>一定在房间的边界上，并且边界上不会有空地。最初，每块空地上都有一个人，在疏散的时候，每一秒钟每个人都</div>
<div>可以向上下左右四个方向移动一格，当然他也可以站着不动。疏散开始后，每块空地上就没有人数限制了（也就是</div>
<div>说每块空地可以同时站无数个人）。但是，由于门很窄，每一秒钟只能有一个人移动到门的位置，一旦移动到门的</div>
<div>位置，就表示他已经安全撤离了。现在的问题是：如果希望所有的人安全撤离，最短需要多少时间？或者告知根本</div>
<div>不可能。</div></div>

# Input

<div class="content"><div>第一行是由空格隔开的一对正整数N与M，3&lt;=N &lt;=20，3&lt;=M&lt;=20，</div>
<div>以下N行M列描述一个N M的矩阵。其中的元素可为字符&#39;.&#39;、&#39;X&#39;和&#39;D&#39;，且字符间无空格。</div></div>

# Output

<div class="content"><div>只有一个整数K，表示让所有人安全撤离的最短时间，</div>
<div>如果不可能撤离，那么输出&#39;impossible&#39;（不包括引号）。</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 5  <br/>
XXXXX<br/>
X...D<br/>
XX.XX<br/>
X..XX<br/>
XXDXX</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p><p>2015.1.12新加数据一组，鸣谢1756500824</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

