<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>孔子是我国古代著名的教育家。他有先见之明，可以判断学生出师以后给他带来的声望。声望共有三种“G”“M”“B”，“G”可以给他带来3点声望，“M”可以给他带来2点声望，“B”可以让他丢失2点声望。每个学生出师后的声望为a<sub>i</sub>。当然，学生出师的时间不同,第i个的学生需要b<sub>i</sub>个单位时间。他每次只能教1名学生。他共有x个学生，有y个单位时间，但必须教z名学生。求孔子可获得的最大声望。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入格式：</p>
<p>x z y</p>
<p>a<sub>1</sub> b<sub>1</sub></p>
<p>……</p>
<p>……</p>
<p>……</p>
<p>a<sub>x </sub>b<sub>x</sub></p>
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

<p>输出格式：</p>
<p>ans（为最大声望）</p>
<p>无解输出- 1</p>
<p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>例一：</p>
<p>2 2 2</p>
<p>G 0</p>
<p>G 2</p>
<p>例二：</p>
<p>4 2 2</p>
<p>B 1</p>
<p>B 1</p>
<p>G 4</p>
<p>M 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>例一：</p>
<p>6</p>
<p>例二：</p>
<p>-4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>x&lt;=10,z&lt;=a,y&lt;=200,声望可能为负数，保证时间大于0,但不一定有解。</p>
</div>
</div>