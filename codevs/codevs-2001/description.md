<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　给出一个长度为N由B、W、X三种字符组成的字符串S，你需要把每一个X染成B或W中的一个。</span><br><span>　　对于给出的K，问有多少种染色方式使得存在整数a,b,c,d使得:</span><br><span>　　1&lt;=a&lt;=b&lt;c&lt;=d&lt;=N</span><br><span>　　S</span><sub>a</sub><span>,S</span><sub>a+1</sub><span>,...,S</span><sub>b</sub><span>均为B</span><br><span>　　S</span><sub>c,</sub><span>S</span><sub>c+1</sub><span>,...,S</span><sub>d</sub><span>均为W</span><br><span>　　其中b=a+K-1,d=c+K-1</span><br><span>　　由于方法可能很多，因此只需要输出最后的答案对10</span><sup>9</sup><span>+7取模的结果。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　第一行两个正整数N,K</span><br><span>　　第二行一个长度为N的字符串S</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　一行一个整数表示答案%(10</span><sup>9</sup><span>+7)。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>5 2</span><br><span>XXXXX</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>4</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>　　对于20%的数据，N&lt;=20</span><br><span>　　对于50%的数据，N&lt;=2000</span><br><span>　　对于100%的数据，1&lt;=N&lt;=10</span><sup>6</sup><span>，1&lt;=K&lt;=10</span><sup>6</sup></p>
<p> </p>
<p>来源：<span>中国国家队清华集训 2012-2013 第一天</span></p>
</div>
</div>