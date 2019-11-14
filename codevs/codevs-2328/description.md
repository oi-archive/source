<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>若能将无向图G=(V,E)画在平面上使得任意两条无重合顶点的边不相交，则称 G是平面图。判定一个图是否为平面图的问题是图论中的一个重要问题。现在假设你要判定的是一类特殊的图，图中存在一个包含所有顶点的环，即存在哈密顿回路。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行是一个正整数T，表示数据组数（每组数据描述一个要判定的图） 。接下来从输入文件第二行开始有T组数据，每组数据的第一行是用空格隔开的两个正整数N和M，分别表示对应图的顶点数和边数。紧接着的M行，每行是用空格隔开的两个正整数u和v(1≤u,v≤N)，表示对应图的一条边(u,v)，输入的数据保证所有边仅出现一次。<br>每组数据的最后一行是用空格隔开的N个正整数， 从左到右表示对应图中的一个哈密顿回路： V1, V2, „, VN，即对任意i≠j有Vi≠Vj且对任意1≤i≤N-1有(Vi,Vi+1)∈E及(V1,VN)∈E。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含T行，若输入文件的第i组数据所对应图是平面图，则在第i 行<br />输出YES，否则在第i 行输出NO，注意均为大写字母。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 <br>6 9 <br>1 4 <br>1 5 <br>1 6 <br>2 4 <br>2 5 <br>2 6 <br>3 4 <br>3 5 <br>3 6 <br>1 4 2 5 3 6 <br>5 5 <br>1 2 <br>2 3 <br>3 4 <br>4 5 <br>5 1 <br>1 2 3 4 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>NO</p>
<p>YES</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>保证100%的数据满足T≤100,3≤N≤200,M≤10000</p>
</div>
</div>