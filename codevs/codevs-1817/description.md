<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>B地区在地震过后，所有村庄都造成了一定的损毁，而这场地震却没对公路造成什么影响。但是在村庄重建好之前，所有与未重建完成的村庄的公路均无法通车。换句话说，只有连接着两个重建完成的村庄的公路才能通车，只能到达重建完成的村庄。</p>
<p>给出B地区的村庄数N，村庄编号从0到N-1，和所有M条公路的长度，公路是双向的。并给出第i个村庄重建完成的时间t[i]，你可以认为是同时开始重建并在第t[i]天重建完成，并且在当天即可通车。若t[i]为0则说明地震未对此地区造成损坏，一开始就可以通车。之后有Q个询问(x, y, t)，对于每个询问你要回答在第t天，从村庄x到村庄y的最短路径长度为多少。如果无法找到从x村庄到y村庄的路径，经过若干个已重建完成的村庄，或者村庄x或村庄y在第t天仍未重建完成 ，则需要返回-1。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行包含两个<strong>正整数</strong>N，M，表示了村庄的数目与公路的长度。</p>
<p>第二行包含N个<strong>非负整数</strong>t[0], t[1], …, t[N – 1]，表示了每个村庄重建完成的时间，<strong>数据保证了t[0] ≤ t[1] ≤ … ≤ t[N – 1]</strong>。</p>
<p>接下来M行，每行3个<strong>非负整数</strong>i, j, w，<strong>w为不超过10000的正整数</strong>，表示了有一条连接村庄i与村庄j的道路，长度为w，保证i≠j，且对于任意一对村庄只会存在一条道路。</p>
<p>接下来一行也就是M+3行包含一个<strong>正整数</strong>Q，表示Q个询问。</p>
<p>接下来Q行，每行3个<strong>非负整数</strong>x, y, t，询问在第t天，从村庄x到村庄y的最短路径长度为多少，<strong>数据保证了t是不下降的</strong>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出包含Q行，对每一个询问(x, y, t)输出对应的答案，即在第t天，从村庄x到村庄y的最短路径长度为多少。如果在第t天无法找到从x村庄到y村庄的路径，经过若干个已重建完成的村庄，或者村庄x或村庄y在第t天仍未修复完成，则输出-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 5</p>
<p>1 2 3 4</p>
<p>0 2 1</p>
<p>2 3 1</p>
<p>3 1 2</p>
<p>2 1 4</p>
<p>0 3 5</p>
<p>4</p>
<p>2 0 2</p>
<p>0 1 2</p>
<p>0 1 3</p>
<p>0 1 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>-1</p>
<p>-1</p>
<p>5</p>
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>【数据规模】</strong></p>
<p>对于30%的数据，有N≤50；</p>
<p>对于30%的数据，有t[i] = 0，其中有20%的数据有t[i] = 0<strong>且</strong>N＞50；</p>
<p>对于50%的数据，有Q≤100；</p>
<p>对于100%的数据，有N≤200，M≤N*(N-1)/2，Q≤50000，所有输入数据涉及整数均不超过100000。</p>
</div>
</div>