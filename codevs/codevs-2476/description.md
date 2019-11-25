<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>好吧，新年到了，要买贺年卡了</p>
<p>我们知道要买m张贺年卡，且看中n家店铺，每家店铺的存货量和价格不同</p>
<p>我们最少要花多少钱？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>包括n+1行</p>
<p>第一行，m和n</p>
<p>以下n行，每行两个整数，代表该店铺的贺年卡单价与存货量</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一个整数，表示我们最少要花多少钱</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 4</p>
<p>4 3</p>
<p>6 2</p>
<p>8 10</p>
<p>3 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>36</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例解释：</p>
<p>先将最后一家买空（3元*6=18元）</p>
<p>再将第一家买空（4元*3=12元）</p>
<p>再从第二家买一张（6元*1=6元）</p>
<p>刚好十张，总价格36元</p>
<p>保证结果在长整型以内且总存货量不少于m，保证有且只有一个最优解</p>
<p>0&lt;m,n&lt;=1000</p>
</div>
</div>