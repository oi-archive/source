
# Description

<div class="content"><div>
<div>A国计划在战争中对B国发动反物质武器，此计划定名为Styx。为阻止两国从此大肆使用反物质武器，你决定破坏A</div>
<div>国的反物质武器（假设你有破坏它们的奇怪技巧）。武器的位置显然是机密，但是某人留下了关于武器位置的加密</div>
<div>信息，并告诉了你解密方式。</div>
<div>该信息是一个n个点（1..n）的树，根节点为1，每个点上均有一个点权Ai。</div>
<div>定义f(n)= ∑gcd(i,n)，其中i=1..n；</div>
<div>g(n)=∑d|nf(d)；</div>
<div>S(i)= ∏Aj,其中j节点在i节点到根的路径上;</div>
<div>s(i)表示以i节点为根的子树大小；</div>
<div>i节点对应的三维向量F(i)=(g(S(i)),4*i,s(i))。</div>
<div>A国存放武器的地点共有m个，每个地点都被表示为数对（x，y），代表着F(x)×F(v1)×F(v2)×F(v3)×…×F(y)</div>
<div>（其中vi在x到y的路径上），即路径上的向量按次序排列后的向量积，最后得出的向量即是存放武器的位置。你的</div>
<div>任务即是对每条信息进行解密，阻止Styx。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行包含两个正整数n，m (n,m&lt;=100,000)</div>
<div>第二行n个数字表示Ai,(1&lt;=Ai&lt;=1,000,000)</div>
<div>以下n-1行表示树边（无向）</div>
<div>接下来为一个空行，之后m行表示每个地点的加密信息x,y(1&lt;=x,y&lt;=n)</div>
<div></div>
</div></div>

# Output

<div class="content"><div>
<div>对于每个地点，输出解密后的坐标（mod 1000000007，取值在0..1,000,001）</div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
9 4 9 <br/>
1 2<br/>
1 3<br/>
<br/>
1 1<br/>
3 2<br/>
3 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">27 4 3<br/>
999988451 419872 385168<br/>
405 12 1<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img src="/source/bzoj/4623/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNi_ml6DmoIfpopgoMSkucG5n.png" width="444" height="218" alt=""/></p><br/>
<p></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By tlzmybm">By tlzmybm</a></p></div>

