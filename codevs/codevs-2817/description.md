<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　<span style="text-decoration: underline;">如果机房马上要关门了，或者你急着要和MM约会，请直接跳到第六个自然段。</span></p>
<p>　　第二段：本题改编自Usaco Training 4.4.2...</p>
<p>　　第三段：本题加大了数据强度...</p>
<p>　　第四段：本题来自CH Round #1...</p>
<p>　　第五段：快去看第六段！</p>
<p><span>　　Tangent来到OI村，想起Bread经常在他面前晒妹(Lemon)，于是要把二人分隔两地，永世不能相见。</span></p>
<p><span>　　黑化的Tangent拥有了分裂大地的力量，他要分裂两人的家之间的一些路，</span><strong>使得Bread不能去找Lemon。</strong><span>(保证Bread家和Lemon家连通)</span></p>
<p><span>　　从Bread家到Lemon家的路现在可以看成是一个有向图，具有N个点，M条边。(点的编号为1~N，</span><strong>边的编号按照离Tangent的距离由近到远依次为1~M</strong><span>)</span></p>
<p><span>　　Tangent想要毁坏一条边的代价是W</span><sub>i</sub><span>。</span></p>
<p><span>　　由于Tangent想要节省力量去毁坏更多和谐的事物，所以他的炸路方案必定是</span><strong>总代价最小、边数量最小的</strong><span>，而且他希望能尽快做完这件事，所以他炸的路对应编号必定是</span><strong>字典序最小的</strong><span>。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　第一行四个正整数N，M，S</span><sub>0</sub><span>，T</span><sub>0</sub><span>，分别表示点数，边数，Bread家的点编号，Lemon家的点编号。</span></p>
<p><span><span>　　接下来N行，</span><strong>按照边的编号依次描述每条边</strong><span>，每行三个正整数S</span><sub>i</sub><span>，T</span><sub>i</sub><span>，W</span><sub>i</sub><span>，分别表示第i条边的起点、终点和毁坏代价。</span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　第一行两个正整数W和K，表示总最小代价和最小炸路数量。</span></p>
<p><span><span>　　接下来K行，输出最小字典序方案，每行一个正整数Number，表示第Number条边要炸毁。</span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 5 1 4<br>1 3 100<br>3 2 50<br>2 4 60<br>1 2 40<br>2 3 80</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>60 1<br>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>对于30%的数据:<img src="/source/codevs/codevs-2817/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_TlxsZXEmYW1wO3NwYWNlOzEwLCZhbXA7c3BhY2U7TVxsZXEmYW1wO3NwYWNlOzUwMA==.latex"></div>
<div>对于60%的数据:<img src="/source/codevs/codevs-2817/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_TlxsZXEmYW1wO3NwYWNlOzIwLCZhbXA7c3BhY2U7TVxsZXEmYW1wO3NwYWNlOzEwMDA=.latex"></div>
<div>对于100%的数据:<img src="/source/codevs/codevs-2817/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_TlxsZXEmYW1wO3NwYWNlOzUwLE1cbGVxJmFtcDtzcGFjZTs1MDAwLFdfe2l9XGxlcSZhbXA7c3BhY2U7MTBeezV9.latex"></div>
</div>
</div>