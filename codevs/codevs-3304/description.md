<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>水果姐今天心情不错，来到了水果街。</p>
<p>水果街有n家水果店，呈直线结构，编号为1~n，每家店能买水果也能卖水果，并且同一家店卖与买的价格一样。</p>
<p>学过oi的水果姐迅速发现了一个赚钱的方法：在某家水果店买一个水果，再到另外一家店卖出去，赚差价。</p>
<p>就在水果姐窃喜的时候，cgh突然出现，他为了为难水果姐，<span style="">给出m个问题，每个问题要求水果姐从第x家店出发到第y家店，途中只能选一家店买一个水果，然后选一家店（可以是同一家店，但不能往回走）卖出去，求每个问题中最多可以赚多少钱。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行n，表示有n家店</p>
<p>下来n个正整数，表示每家店一个苹果的价格。</p>
<p>下来一个整数m，表示下来有m个询问。</p>
<p>下来有m行，每行两个整数x和y，表示从第x家店出发到第y家店。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>有m行。</p>
<p>每行对应一个询问，一个整数，表示面对cgh的每次询问，水果姐最多可以赚到多少钱。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10<br>2 8 15 1 10 5 19 19 3 5 <br>4<br>6 6<br>2 8<br>2 2<br>6 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0<br>18<br>0<br>14</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>0&lt;=苹果的价格&lt;=10^8</p>
<p>0&lt;n,m&lt;=200000</p>
</div>
</div>