<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>sb有一天和sml吵架了，她离家出走，走到了一个a*a的正方形里，她迷路了！</p>
<p>A为入口，</p>
<p>B为sb。</p>
<p>正在此时，sml来到了迷宫入口，他和她都很着急，求最快要x步（从入口进，从入口出）（要*2）</p>
<p>‘0’为水，‘1’为路，‘2’为障碍物，‘3’为草地（可以走）。‘4’为树（也走不了），‘5’为石头（可以走）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>a</p>
<p>a*a个数（A,B也在内）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>x（A,B只统计1次）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>0 0 0 0 <span style="text-decoration: underline;">A</span></p>
<p>1 1 1 <span style="text-decoration: underline;">1 1</span></p>
<p>3 2 4 <span style="text-decoration: underline;">1</span> 0</p>
<p>5 5 5 <span style="text-decoration: underline;">5</span> 0</p>
<p>0 0 0 <span style="text-decoration: underline;">3</span> <span style="text-decoration: underline;">B</span></p>
<p>//画横线的为路径！</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>12</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>a&lt;=500</p>
<p>对于30%的数据只有“1”和“0”。</p>
<p>对于60%的数据没有“3”和“5”</p>
<p>对于100%的数据，路程&gt;=10.</p>
<p>当行不通时“printf（“NoNE！”）；”</p>
</div>
</div>