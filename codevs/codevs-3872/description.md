<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一个邮递员要送东西，邮局在结点1。他总共要送N-1样东西，其目的地分别是2~ N，由于这个城市的交通比较繁忙，因此所有的道路都是单行的<span style="text-decoration: line-through;">（每次都是这个理由╮(╯▽╰)╭ ）</span>，共有M条道路，通过每条道路需要一定的时间。这个邮递员每次只能带一件东西<span style="text-decoration: line-through;">（你送的快递是要有多大）</span>。求送完这N-1样东西并最终回到邮局最少需要多少时间。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行包含一个正整数N和M  <span style="text-decoration: line-through;">（这叫一个正整数？）</span></p><p><span style="text-decoration: none;">接下来M行，每行三个整数U,V,W，表示该条道路为从U到V的，且通过这条道路需要W的时间。满足1≤U,V≤N，1≤W≤10000，输入保证任意两点都能互相到达，但不保证每两个目的地之间只有一条路径。</span></p><p><span style="text-decoration: none;"><br></span></p><p><span style="text-decoration: none;"><br></span></p><p><span style="text-decoration: none;">温馨提示：本题数据量较大，所以……你懂的…………</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出仅一行，包含一个整数，为最少需要的时间。<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 10</p><p>2 3 5</p><p>1 5 5</p><p>3 5 6</p><p>1 2 8</p><p>1 3 8</p><p>5 3 4</p><p>4 1 8</p><p>4 5 3</p><p>3 5 6</p><p>5 4 2</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>83<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，满足1≤N≤200；</p><p>对于100%的数据，满足1≤N≤1000,1≤M≤100000。</p>
</div>
</div>