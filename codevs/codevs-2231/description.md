<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>        象棋的问题被小可可轻松解决了，下面小可可邀请你一起来研究另一个难题，这次与跳棋有关，问题是这样的：在一个1行N列（N是奇数）的棋盘上，在K个格子是红色的，这种情况下，在开始移动之前，你可以棋盘的任何空位上放棋子。在游戏开始后，你只可以随时在一个红色格子上放棋子。棋子的移动规则是：每次只可以选择一个棋子，跳过与之相邻的棋子走到后面的空格上，被它跳过的棋子就被吃掉了，即从棋盘上移走，如相邻棋子的另一侧有棋子，则不能跳。现在你和小可可要解答以下两个问题：<br> 1.移动开始前至少要放多少棋子才能完成任务？<br> 2.如果使移动开始前放的棋子数要求尽量少，那么在移动过程中最少需要放多少个棋子才能完成任务？<br> 这是你和小可可合作解决的最后一个问题了，共同努力吧！<br> 关于规则的补充说明：<br> 1.只能往空位上放棋子，不管是移动开始前还是在移动过程中。<br> 2.移动开始前棋盘最左端的那个原始棋子绝对不能被吃掉。<br> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行  一个正奇数N<br>第二行  N个整数，如果第i个整数是1，说明第i个格子是红色，否则则为白色，数字之间用一个空格隔开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>两个用一个空格隔开的整数，分别为对第一问和第二问的回答。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5<br>0 0 0 1 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>100%的数据中，N不超过1000且输出中数字不会超过10<sup>15</sup><br> 30%的数据 ，N不超过20</p>
</div>
</div>