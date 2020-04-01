<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一个神秘好人跟Bdcxq玩一个游戏，如果Bdcxq成功完成了这个游戏，那么他将会得到一件礼物。</p>
<p>这个游戏是这样的：</p>
<p>有一个梯子形的图如下，每条边都有一个权值。</p>
<p>神秘好人一开始会告诉Bdcxq每条边的权值。</p>
<p>       然后神秘好人会做这样的事情：</p>
<p>1．神秘好人会修改某条边的权值；</p>
<p>2．神秘老人会问你从一个点走到另一个点所需经过边权和最小的权值和。</p>
<p> </p>
<p>如果Bdcxq一直能答对问题，那么他就完成了游戏，也能得到礼物。</p>
<p>现在他请你编一个程序来帮他完成游戏。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行包含一个整数<em>N</em>，表示梯子总共含有<em>2N</em>个点，第一行从左至右分别标号为<em>1</em><em>，</em><em>3</em><em>，……，</em><em>2N-1</em><em>，</em>第二行从左至右分别标号为<em>2</em><em>，</em><em>4</em><em>，……，</em><em>2N</em>。</p>
<p>接下来有三行。</p>
<p>第一行有<em>N-1</em>个整数，依次表示上层相邻两点间的初始权值。</p>
<p>第二行有<em>N</em>个整数，依次表示两层之间的边的初始权值。</p>
<p>第三行有<em>N-1</em>个整数，依次表示下层相邻两点间的初始权值。</p>
<p>接下来一行包含一个整数M，表示神秘好人在游戏开始后的操作。</p>
<p>接下来M行：</p>
<p>每行第一个整数若是0，表示这是一个修改操作，接下来会有3个整数A<sub>i</sub>，B<sub>i</sub>，C<sub>i</sub>，A<sub>i</sub>为0，1，2分别代表这条边属于上层边，中间边和下层边，B<sub>i</sub>表示这条边是这一层从左向右数的第B<sub>i</sub>条边，C<sub>i</sub>表示要修改成的边权。</p>
<p>每行第一个整数若是1，表示这是一个询问操作，接下来会有2个整数A<sub>i</sub>，B<sub>i</sub>，询问A<sub>i</sub>到B<sub>i</sub>的经过边的最小权值和。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每次询问操作你需要输出一行包含一个整数，为最小的边权值和。</p>

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
<p>1 2 7</p>
<p>1 3 4 8</p>
<p>4 5 6</p>
<p>5</p>
<p>1 1 2</p>
<p>1 2 6</p>
<p>1 1 8</p>
<p>0 1 3 1</p>
<p>1 1 8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>8</p>
<p>13</p>
<p>10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的数据满足<em>N</em><em>，</em><em>M</em>≤ 1000。</p>
<p>100%的数据满足<em>N</em><em>，</em><em>M</em>≤ 100000。</p>
</div>
</div>