<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    从m开始，我们只需要6次运算就可以计算出m<sup>31</sup>：</p>
<p> </p>
<p>    m<sup>2</sup>=m×m，m<sup>4</sup>=m<sup>2</sup>×m<sup>2</sup>，m<sup>8</sup>=m<sup>4</sup>×m<sup>4</sup>，m<sup>16</sup>=m<sup>8</sup>×m<sup>8</sup>，m<sup>32</sup>=m<sup>16</sup>×m<sup>16</sup>，m<sup>31</sup>=m<sup>32</sup>÷m。</p>
<p> </p>
<p>    请你找出从m开始，计算m<sup>n</sup>的最少运算次数。在运算的每一步，都应该是m的正整数次方，换句话说，类似m<sup>-3</sup>是不允许出现的。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入为一个正整数n</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出为一个整数，为从m开始，计算m<sup>n</sup>的最少运算次数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1<br>1<br><br>样例2<br>31<br><br>样例3<br>70</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1<br>0<br><br>样例2<br>6<br><br>样例3<br>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n（1&lt;=n&lt;=1000）</p>
<p> </p>
<p>数据没有问题，已经出现过的n次方可以直接调用</p>
</div>
</div>