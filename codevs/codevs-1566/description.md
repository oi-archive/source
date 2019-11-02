<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定一棵有n个节点的无根树和m个操作，操作有2类：</p>
<p>1、将节点a到节点b路径上所有点都染成颜色c；</p>
<p>2、询问节点a到节点b路径上的颜色段数量（连续相同颜色被认为是同一段），如“112221”由3段组成：“11”、“222”和“1”。</p>
<p>请你写一个程序依次完成这m个操作。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含2个整数n和m，分别表示节点数和操作数；</p>
<p>第二行包含n个正整数表示n个节点的初始颜色</p>
<p>下面n-1行每行包含两个整数 和 ，表示<em>x</em>和<em>y</em>之间有一条无向边。</p>
<p>下面m行每行描述一个操作：</p>
<p>“C a b c”表示这是一个染色操作，把节点a到节点b路径上所有点（包括a和b）都染成颜色c；</p>
<p>“Q a b”表示这是一个询问操作，询问节点a到节点b（包括a和b）路径上的颜色段数量。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="NOI">对于每个询问操作，输出一行答案。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>6 5</span></p>
<p><span>2 2 1 2 1 1</span></p>
<p><span>1 2</span></p>
<p><span>1 3</span></p>
<p><span>2 4</span></p>
<p><span>2 5</span></p>
<p><span>2 6</span></p>
<p><span>Q 3 5</span></p>
<p><span>C 2 1 1</span></p>
<p><span>Q 3 5</span></p>
<p><span>C 5 1 2</span></p>
<p><span>Q 3 5</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>3</span></p>
<p><span>1</span></p>
<p><span>2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据1≤n≤10<sup>4</sup>，1≤m≤10<sup>5</sup>，1≤m≤10<sup>9</sup>；<br> </p>
</div>
</div>