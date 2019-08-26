
# Description

<div class="content"><div>这是一道经典傻逼题，对经典题很熟悉的人也不要激动，希望大家不要傻逼。</div>
<div>考虑一张N个点的带权无向图，点的编号为1到N。 对于图中的任意一个点集</div>
<div>（可以为空或者全集），所有恰好有一个端点在这个点集中的边组成的集合被称</div>
<div>为割。 一个割的权值被定义为所有在这个割上的边的异或和。</div>
<div>一开始这张图是空图， 现在，考虑给这张无向图不断的加边， 加入每条边之</div>
<div>后，你都要求出当前权值最大的割的权值， 注意加入的边永远都不会消失。</div>
<div></div></div>

# Input

<div class="content"><div>输入的第一行包括一个数ID表示数据编号， 如第一组数据中的ID = 1。注意</div>
<div>样例数据中的ID = 0。</div>
<div>接下来的第一行包括两个整数N,M表示图的点数和总共加的边。</div>
<div>接下来M行，每行三个正整数x,y,w表示在点x和点y之间加入一条权值为w的边。 </div>
<div>注意x和y可能相同，两条不同的边也可能连接了同一对点。</div>
<div>此外， w将以二进制形式从高位向低位给出，比如， 6 = 110(2)，因此如果边</div>
<div>权为 6，那么w将会是110。</div>
<div> 1 ≤ N≤ 500， 1 ≤ M ≤ 1000， 0 ≤ L &lt; 1000， 1 ≤ x,y≤ N</div>
<div></div></div>

# Output

<div class="content"><div>输出M行，按顺序输出每一条边加入之后权值最大的割的权值。</div>
<div>同样，你也要以二进制形式输出，形式和输入格式中描述的形式一样。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">0 3<br/>
6<br/>
1 2 1<br/>
1 2 1<br/>
3 3 111<br/>
1 3 101101<br/>
1 2 1011<br/>
2 3 111011</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 0 0<br/>
101101<br/>
101101<br/>
110000<br/>
<br/>
前三条边加入之后的答案较为显然，考虑后三条边，加入第六条边之前， 考<br/>
虑点集{1,2}，它对应的割只有第四条边， 因此答案就是第四条边的权值，考虑加<br/>
入最后一条边以后的情况，此时点集{1,2}对应的割变成了第四条边和第六条边组<br/>
成的集合，权值也发生了相应的改变。 点集{2}对应的割是第五条边和第六条边<br/>
组成的集合， 可以证明这就是权值最大的割，权值为1011(2) ⊕ 111011(2) =110000(2)</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

