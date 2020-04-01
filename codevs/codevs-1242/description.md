<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">当排队等候喂食时，奶牛喜欢和它们的朋友站得靠近些。<span style="font-family: Times New Roman;">FJ</span><span style="">有</span><span style="font-family: Times New Roman;">N</span><span style="">（</span><span style="font-family: Times New Roman;">2&lt;=N&lt;=1000</span><span style="">）头奶牛，编号从</span><span style="font-family: Times New Roman;">1</span><span style="">到</span><span style="font-family: Times New Roman;">N</span><span style="">，沿一条直线站着等候喂食。奶牛排在队伍中的顺序和它们的编号是相同的。因为奶牛相当苗条，所以可能有两头或者更多奶牛站在同一位置上。即使说，如果我们想象奶牛是站在一条数轴上的话，允许有两头或更多奶牛拥有相同的横坐标。</span></span></p>
<p><span style="">一些奶牛相互间存有好感，它们希望两者之间的距离不超过一个给定的数<span style="font-family: Times New Roman;">L</span><span style="">。另一方面，一些奶牛相互间非常反感，它们希望两者间的距离不小于一个给定的数</span><span style="font-family: Times New Roman;">D</span><span style="">。给出</span><span style="font-family: Times New Roman;">ML</span><span style="">条关于两头奶牛间有好感的描述，再给出</span><span style="font-family: Times New Roman;">MD</span><span style="">条关于两头奶牛间存有反感的描述。（</span><span style="font-family: Times New Roman;">1&lt;=ML,MD&lt;=10000</span><span style="">，</span><span style="font-family: Times New Roman;">1&lt;=L,D&lt;=1000000</span><span style="">）</span></span></p>
<p><span style="">你的工作是：如果不存在满足要求的方案，输出<span style="font-family: Times New Roman;">-1</span><span style="">；如果</span><span style="font-family: Times New Roman;">1</span><span style="">号奶牛和</span><span style="font-family: Times New Roman;">N</span><span style="">号</span></span></p>
<p><span style="">奶牛间的距离可以任意大，输出<span style="font-family: Times New Roman;">-2</span><span style="">；否则，计算出在满足所有要求的情况下，</span><span style="font-family: Times New Roman;">1</span><span style="">号奶牛和</span><span style="font-family: Times New Roman;">N</span><span style="">号奶牛间可能的最大距离。</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<div><span style="">Line 1: Three space-separated integers: N, ML, and MD. </span><br><br><span style="">Lines 2..ML+1: Each line contains three space-separated positive integers: A, B, and D, with 1 &lt;= A &lt; B &lt;= N. Cows A and B must be at most D (1 &lt;= D &lt;= 1,000,000) apart. </span><br><br><span style="">Lines ML+2..ML+MD+1: Each line contains three space-separated positive integers: A, B, and D, with 1 &lt;= A &lt; B &lt;= N. Cows A and B must be at least D (1 &lt;= D &lt;= 1,000,000) apart.</span></div>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<div class="ptx" lang="en-US"><span style="font-size: medium;">Line 1: A single integer. If no line-up is possible, output -1. If cows 1 and N can be arbitrarily far apart, output -2. Otherwise output the greatest possible distance between cows 1 and N.</span></div>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">4 2 1</span><br><span style="">1 3 10</span><br><span style="">2 4 20</span><br><span style="">2 3 3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">27</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>