<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Masha和Stas正在玩一个游戏。在游戏的开始，给出一个定值N，同时有两个正整数A<br>和B，初始时满足A^B&lt;=N。Masha先手。每一回合，玩家要将A和B的其中一个数加上1，但<br>不能令到A^B &gt; N，否则该玩家输。现在，Masha想知道假如两人都使用最优策略，对于一<br>个特定的N，不同的A、B的初始值谁将获胜呢？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行为一个正整数N。<br>输入第二行为一个正整数T，表示测试数据个数。<br>下面T行，每行有两个正整数Ai、Bi，描述了一组测试数据&lt; Ai，Bi，N &gt;，含义如题<br>目描述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对每组数据输出一行。如果先手Masha获胜，输出"Masha"；如果Stas获胜，输<br />出"Stas"；如果和则输出"Missing"（不用输出引号）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例数据1<br>9<br>2<br>2 2<br>1 4</p>
<p>样例数据2</p>
<p>16807<br>3<br>5 5<br>1 100<br>100 1</p>
<p>样例数据3</p>
<p>3<br>1<br>3 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例数据1</p>
<p>Masha<br>Missing</p>
<p>样例数据2</p>
<p>Masha<br>Missing<br>stas</p>
<p>样例数据3</p>
<p>Stas</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据限制<br>对30%数据有1&lt;=N&lt;=2000<br>对100%的数据有：<br>1&lt;=N&lt;=10^8<br>1&lt;=T&lt;=100<br>1&lt;=Ai，1&lt;=Bi,Ai^Bi&lt;=N</p>
</div>
</div>