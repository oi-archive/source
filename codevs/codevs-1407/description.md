<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一棵树上有<span style="font-family: 'Times New Roman';">n</span><span style="">个节点，编号分别为</span><span style="font-family: 'Times New Roman';">1</span><span style="">到</span><span style="font-family: 'Times New Roman';">n</span><span style="">，每个节点都有一个权值</span><span style="font-family: 'Times New Roman';">w</span><span style="">。</span></p>
<p>我们将以下面的形式来要求你对这棵树完成一些操作：</p>
<p>I. CHANGE u t : 把结点u的权值改为t</p>
<p>II. QMAX u v: 询问从点u到点v的路径上的节点的最大权值</p>
<p>III. QSUM u v: 询问从点u到点v的路径上的节点的权值和</p>
<p> </p>
<p>注意：从点<span style="font-family: 'Times New Roman';">u</span><span style="">到点</span><span style="font-family: 'Times New Roman';">v</span><span style="">的路径上的节点包括</span><span style="font-family: 'Times New Roman';">u</span><span style="">和</span><span style="font-family: 'Times New Roman';">v</span><span style="">本身</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行为一个整数<span style="font-family: 'Times New Roman';">n</span><span style="">，表示节点的个数。</span></p>
<p>接下来<span style="font-family: 'Times New Roman';">n </span>– 1<span style="">行，每行</span><span style="font-family: 'Times New Roman';">2</span><span style="">个整数</span><span style="font-family: 'Times New Roman';">a</span><span style="">和</span><span style="font-family: 'Times New Roman';">b</span><span style="">，表示</span>节点a<span style="">和节点</span><span style="font-family: 'Times New Roman';">b</span><span style="">之间有一条边相连。</span></p>
<p>接下来<span style="font-family: 'Times New Roman';">n</span><span style="">行，每行一个整数，第</span><span style="font-family: 'Times New Roman';">i</span><span style="">行的整数</span><span style="font-family: 'Times New Roman';">wi</span><span style="">表示节点</span><span style="font-family: 'Times New Roman';">i</span><span style="">的权值。</span></p>
<p>接下来<span style="font-family: 'Times New Roman';">1</span><span style="">行，为一个整数</span><span style="font-family: 'Times New Roman';">q</span><span style="">，表示操作的总数。</span></p>
<p>接下来<span style="font-family: 'Times New Roman';">q</span><span style="">行，每行一个操作，以“</span>CHANGE u t”或者“QMAX u v”或者“QSUM u v”的形式给出。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">对于每个&ldquo;QMAX&rdquo;或者&ldquo;QSUM&rdquo;的操作，每行输出一个整数表示要求输出的结果。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>1 2</p>
<p>2 3</p>
<p>4 1</p>
<p>4 2 1 3</p>
<p>12</p>
<p>QMAX 3 4</p>
<p>QMAX 3 3</p>
<p>QMAX 3 2</p>
<p>QMAX 2 3</p>
<p>QSUM 3 4</p>
<p>QSUM 2 1</p>
<p>CHANGE 1 5</p>
<p>QMAX 3 4</p>
<p>CHANGE 3 6</p>
<p>QMAX 3 4</p>
<p>QMAX 2 4</p>
<p>QSUM 3 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div>
<p>4</p>
<p>1</p>
<p>2</p>
<p>2</p>
<p>10</p>
<p>6</p>
<p>5</p>
<p>6</p>
<p>5</p>
<p>16</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p> </p>
<p>对于100<span style="">％的数据，保证</span><span style="font-family: 'Times New Roman';">1&lt;=n&lt;=30000</span><span style="">，</span><span style="font-family: 'Times New Roman';">0&lt;=q&lt;=200000</span><span style="">；中途操作中保证每个节点的权值</span><span style="font-family: 'Times New Roman';">w</span><span style="">在</span><span style="font-family: 'Times New Roman';">-30000</span><span style="">到</span><span style="font-family: 'Times New Roman';">30000</span><span style="">之间。</span></p>
</div>
</div>