<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>英语老师考了一张试卷，上面有N大项。</p>
<p>某同学每项的正确率分别为Ai%。</p>
<p>可以在任意大项上画星，画星的项如果全对，可得分Bi；</p>
<p>如果有错，需写Ci字检讨。</p>
<p>如果画星少于P个，老师会认为信心不够，需写K字检讨。</p>
<p>求该同学在写最少检讨情况下的最大得分。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>N P K</p>
<p>一行，Ai。</p>
<p>一行，Bi。</p>
<p>一行，Ci。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>最大得分。</p>
<p>若最少检讨情况是写K字检讨，输出Oh，I'm poor at English！</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3 5</p>
<p>80 80 100</p>
<p>5 5 3</p>
<p>10 8 15</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N&lt;=20,P&lt;=10,P&lt;=N,K&lt;=100,Ai&lt;=100,Bi&lt;=50,Ci&lt;=50.</p>
<p>检讨=（1-正确率）*检讨数</p>
<p>得分=正确率*分数</p>
</div>
</div>