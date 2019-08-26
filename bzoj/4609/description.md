
# Description

<div class="content"><div>要完成一个由s个子项目组成的项目，给b(b&gt;=s)个部门分配，从而把b个部门分成s个组。分组完成后，每一组的任</div>
<div>意两个点之间都要传递信息。假设在(i,j)两个点间传送信息，要先把信息加密，然后快递员从i出发到总部，再加</div>
<div>密，在到j点。出于安全原因，每次只能携带一条消息。现在给出了道路网络、各个部门和总部的位置，请输出快</div>
<div>递员要走的最小总距离。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含四个整数n,b,s,r。n(2&lt;=n&lt;=5000)代表路口数，b(1&lt;=b&lt;=n-1)是部门数，s(1&lt;=s&lt;=b)是子项目数</div>
<div>r(1&lt;=r&lt;=50000)是道路数。路口标号为1~n，部门在路口1~b，总部在路口b+1。</div>
<div>接下来r行每行三个整数u,v,l，描述一条从u到v长度为l(0&lt;=l&lt;=10000)的双向边。保证没有重边，保证图强连通。</div></div>

# Output

<div class="content"><p> 输出快递员要走的最小总距离。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4 3 8<br/>
1 5 15<br/>
5 1 15<br/>
2 5 2<br/>
5 2 3<br/>
3 5 1<br/>
5 3 1<br/>
4 5 2<br/>
5 4 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Yts1999上传，lbn187提供译文">鸣谢Yts1999上传，lbn187提供译文</a></p></div>

