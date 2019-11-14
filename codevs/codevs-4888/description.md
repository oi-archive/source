<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>现有一些棍状零件，每个零件都有一定的长度(Li)和重量(Wi)。现在为了加工需要，要将他们分成若干组，使每一组中的零件都能排成一个长度和重量都不下降(若i&lt;j，则Li&lt;=Lj，Wi&lt;=Wj，其中i,j为在同一组中的序号)的序列。请问至少要分成几组？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行为一个整数n，表示棍状零件的总个数。</p><p>接下来n行每行有两个正整数，分别为一个零件的长度(Li)和重量(Wi)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个正整数，表示最小分成的组数</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p><p>8 4</p><p>3 8</p><p>9 7</p><p>2 3</p><p>3 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p><p><br></p><p>解释：</p><p>第一组</p><p>(2,3) (3,5) (3,8)</p><p>第二组</p><p>(8,4)(9,7)</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=1000</p><p>Wi&lt;=10000</p><p>Li&lt;=10000</p>
</div>
</div>