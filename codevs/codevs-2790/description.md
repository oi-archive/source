<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>求当x=k(|k|&lt;8)时，一组n个(n&lt;10)关于x的高次代数式的值</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，两个数n,k</p>
<p>n表示代数式的个数，k的意义如上</p>
<p>第2~n+1行，每行一个字符串s，表示形如ax<sup>9</sup>+bx<sup>8</sup>+cx<sup>7</sup>+dx<sup>6</sup>+ex<sup>5</sup>+mx<sup>4</sup>+nx<sup>3</sup>+ux<sup>2</sup>+vx+w的代数式，保证所有系数都为整数，可能为0，某一项系数为0时省略该项，系数为1时只写加号，系数为-1时只写减号</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出x=k时，各个代数式的值，每两个值之间空一行，保证所有答案在longint/long long范围内</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 5<br>-x^9+x^2+34x<br>6x^4-x^6-23x^5+12-x^2<br>-5x^4+4x^3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>-1952930<br>-83763<br>-2625</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据范围题目中都写了</p>
<p>做出这题是做出2785交点统计的前提</p>
</div>
</div>