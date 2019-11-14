<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定有向图G=(V,E)。设P 是G 的一个简单路（顶点不相交）的集合。如果V 中每个<br>顶点恰好在P 的一条路上，则称P是G 的一个路径覆盖。P 中路径可以从V 的任何一个顶<br>点开始，长度也是任意的，特别地，可以为0。G 的最小路径覆盖是G 的所含路径条数最少<br>的路径覆盖。<br>设计一个有效算法求一个有向无环图G 的最小路径覆盖。</p>
<p>对于给定的给定有向无环图G，编程找出G的一个最小路径覆盖。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1 行有2个正整数n和m。n是给定有向无环图<br>G 的顶点数，m是G 的边数。接下来的m行，每行有2 个正整数i和j，表示一条有向边(i,j)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>将最小路径覆盖输出。从第1 行开始，每行输出<br />一条路径。文件的最后一行是最少路径数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>11 12<br>1 2<br>1 3<br>1 4<br>2 5<br>3 6<br>4 7<br>5 8<br>6 9<br>7 10<br>8 11<br>9 11<br>10 11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 4 7 10 11<br>2 5 8<br>3 6 9<br>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>