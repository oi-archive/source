<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>     到了难得的假期，小白班上组织大家去看电影。但由于假期里看电影的人太多，很难做到让全班看上同一场电影，最后大家在一个偏僻的小胡同里找到了一家电影院。但这家电影院分配座位的方式很特殊，具体方式如下：</p>
<ol>
<li><span style="text-decoration: underline;">电影院的座位共有K</span><span style="text-decoration: underline;">个</span>，并被标号为1…K，每个人买完票后会被随机指定一个座位，具体来说是从1…K中等可能的随机选取一个正整数，设其为L。</li>
<li>如果编号L的座位是空位，则这个座位就分配给此人，否则将L加一，继续前面的步骤。</li>
<li>如果在第二步中不存在编号L的座位，则该人只能站着看电影，即所谓的站票。</li>
</ol>
<p><span style="text-decoration: underline;">小白班上共有</span><span style="text-decoration: underline;">N</span><span style="text-decoration: underline;">人</span>（包括小白自己），作为数学爱好者，小白想知道全班都能够有座位的概率是多少。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p> 输入文件第一行有且只有一个正整数T，表示测试数据的组数。</p>
<p>     第2～T+1行，每行两个正整数N,K，用单个空格隔开，其含义同题目描述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;&nbsp;输出文件共包含T行。</p>
<p>第i行应包含两个用空格隔开的整数A,B，表示输入文件中的第i组数据的答案为A/B。（注意，这里要求将答案化为既约分数）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>    3</p>
<p>     1 1</p>
<p>     2 1</p>
<p>     2 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 1</p>
<p>     0 1</p>
<p>     3 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据   N,K&lt;=10</p>
<p>对于100%的数据  T&lt;=50,N,K&lt;=200</p>
</div>
</div>