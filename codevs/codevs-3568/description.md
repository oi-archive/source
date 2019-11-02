<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    老刘最近很不刷，他在学校整天被人说他附别人的体，尽管是开玩笑，但是他仍然觉得不开心。</p><p>    现在老刘需要做恶作剧对说他的人。但也有些人是无辜的。所以总共有n行，m列，n*m个人(3&lt;=n,m&lt;=30)。有说他的人记为k(1&lt;=k&lt;=9)数字越大证明说他的次数越多，没有的记为0。然后下面再出一个矩阵，表示那个人的聪明程度(也就是要做恶作剧的时间，1&lt;=时间&lt;=9,老刘对应的为字符'l')</p><p>    总时间为t(1&lt;=t&lt;=100)，用字符'l’代表老刘。老刘走一格需要一个时间，然后对说他的人做恶作剧又要时间，问在规定时间内，如何使成功做恶作剧的人的时间*次数 达到最大值。<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第一行三个数，分别是n,m,t。</p><p>    接下来n行，每行m数，其中有个是字符'l'代表老刘。</p><p>    然后再n行，每行m数，表示对应的每个人的时间。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;&nbsp;&nbsp; 成功做恶作剧的人的时间*次数的总和（最大值）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4 15<br></p><p>0 l 3 5</p><p>2 0 3 3<br></p><p>2 0 3 0<br></p><p>0 2 0 3</p><p>2 l 1 3</p><p>1 3 2 1</p><p>3 6 4 8</p><p>5 2 9 1<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>30<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例的答案是这样算的：3*5+3*4+3+1=30</p><p>好好理解题目，有点小坑爹。<br></p>
</div>
</div>