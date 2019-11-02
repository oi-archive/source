<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在“jloi-08”游戏中，还存有非常非常多的棋局定式，也就是常会用到的下棋的组合。有时在学习一个著名棋局时，电脑会考一考刘先生：在这局棋里面，有多少个定式啊？分别是什么啊？</p>
<p> </p>
<p>对于30~40步的普通棋局，刘先生还能回答出来，可是有时候2个实力相当的大牛下的棋局，2000000步都有可能。如果电脑对这样的棋局提上面的问题时，刘先生就必须写一个程序来帮助自己了。可是，刘先生在这方面却…，怎么写也写不对。你能帮助刘先生吗？</p>
<p> </p>
<p>棋局是由很多step组成的，而step是由一个字符串组成的，比如Kh2或者是Nxb7。</p>
<p>前者表示K(king)移动至h2格，后者表示N(knight)移动至b7格并吃掉原有的棋子。</p>
<p> </p>
<p>第一个字符可能有6种：K Q B N R P，而后面可能是一个坐标或者是字符x后跟一个坐标。</p>
<p> </p>
<p>坐标是由一个小写英文字母(a~h)和一个数字(1~8)组成的。</p>
<p> </p>
<p>如果一个棋局中完整地并连续地包含一个定式中所有的step，那么这个棋局便包含这个定式。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行2个整数n, m，表示定式的个数(1&lt;=n&lt;=2000)以及这个棋局所包含的步数</p>
<p> </p>
<p>下面的n个块(block)，每块包含：</p>
<p>第一行一个整数k表示定式包含的步数(1&lt;=k&lt;=100000, ∑k&lt;=200000)</p>
<p>第二行一个字符串表示该定式的名称(长度不超过50)</p>
<p>下面的k行每行一个字符串表示定式中的一步</p>
<p> </p>
<p>最后的m行每行一个字符串，表示棋局中的一步</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>按照输入文件包含的定式的顺序，输出棋局包含的所有定式的名称，一个一行。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 5</p>
<p>3</p>
<p>King's Knight Opening</p>
<p>Pe4</p>
<p>Pe5</p>
<p>Nf3</p>
<p>3</p>
<p>Nimzowitsch Variation</p>
<p>Pc4</p>
<p>Pe5</p>
<p>Nf3</p>
<p>Pe4</p>
<p>Pe5</p>
<p>Nf3</p>
<p>Nc6</p>
<p>Bb5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>King's Knight Opening</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=n&lt;=2000</p>
</div>
</div>