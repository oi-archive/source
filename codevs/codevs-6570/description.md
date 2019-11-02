<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">皮皮</span>喜欢吃苹果，他有一棵苹果树，每个夏天都会有一些苹果成熟（长在树上的一些节点上），他会选择树上的两个<strong>成熟的不同的</strong>苹果摘下来吃。</p><p>皮皮认为，两个苹果是好吃的<strong>当且仅当他们之间的距离不超过一个值</strong>。当然，他只会选择两个好吃的苹果摘下来吃。</p><p>皮皮想知道，每个夏天，他有多少种选择方法（<strong>两个苹果交换顺序后算一种</strong>）。</p><p>皮皮的树有一个特点，就是所有的夏天成熟的苹果总数不会太多</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行两个整数N Q，表示树上的节点数量和夏天的个数</p><p>第2~N行每行两个数字X Y，表示树上X与Y之间有一条长度为1的边</p><p>接下来Q块，每块表示一个夏天</p><p>每块第一行两个整数M K，表示这个夏天有M个苹果成熟，强强这个夏天认为距离不超过K的苹果对好吃。</p><p>每块第二行M个整数，分别表示这M个苹果的位置（长在哪个节点上）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个询问输出一个答案，表示皮皮有多少种选择。</p><p>一共Q行</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 2</p><p>1 2</p><p>2 3</p><p>2 4</p><p>1 5</p><p><br></p><p>3 2</p><p>2 4 5</p><p><br></p><p>3 4</p><p>3 4 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p><p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>对于9%的数据，M≤N≤1000,Q=1</p><p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>对于另外36%的数据，M≤N≤45000,Q=1</p><p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>对于另外45%的数据，M≤N≤45000,Q≤23000</p><p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>对于90%的数据，ΣM≤30*N</p><p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>对于额外10%的数据，M=N=200000,Q=1</p><p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>对于所有100%的数据，不保证树随机生成</p><p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>最后一个点要开long long</p><p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>样例解释：</p><p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>第一个夏天，皮皮可以选择（2,4）或者（2,5）</p><p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>第二个夏天，皮皮可以选择（3,4）、（3,5）或者（4,5）</p><p><br></p>
</div>
</div>