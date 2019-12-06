<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>元旦快到了，校学生会让乐乐负责新年晚会的纪念品发放工作。为使得参加晚会的同学所获得的纪念品价值相对均衡，他要把购来的纪念品根据价格进行分组，但每组最多只能包括两件纪念品，并且每组纪念品的价格之和不能超过一个给定的整数。为了保证在尽量短的时间内发完所有纪念品，乐乐希望分组的数目最少。</p>
<p>你的任务是写一个程序，找出所有分组方案中分组数最少的一种，输出最少的分组数目。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>包含<em>n</em>+2行：</p>
<p>第1行包括一个整数<em>w</em>，为每组纪念品价格之和的上限。</p>
<p>第2行为一个整数<em>n</em>，表示购来的纪念品的总件数。</p>
<p>第3~<em>n</em>+2行每行包含一个正整数<em>p<sub>i</sub></em> (5 &lt;= <em>p<sub>i</sub></em> &lt;= <em>w</em>)，表示所对应纪念品的价格。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行，包含一个整数，即最少的分组数目。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>100</p>
<p>9</p>
<p>90</p>
<p>20</p>
<p>20</p>
<p>30</p>
<p>50</p>
<p>60</p>
<p>70</p>
<p>80</p>
<p>90</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>50%的数据满足：1 &lt;= <em>n</em> &lt;= 15</p>
<p>100%的数据满足：1 &lt;= <em>n</em> &lt;= 30000, 80 &lt;= <em>w</em> &lt;= 200</p>
</div>
</div>