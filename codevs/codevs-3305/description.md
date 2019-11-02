<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>水果姐第二天心情也很不错，又来逛水果街。</p>
<p>突然，cgh又出现了。cgh施展了魔法，水果街变成了树结构（店与店之间只有一条唯一的路径）。</p>
<p>同样还是n家水果店，编号为1~n，每家店能买水果也能卖水果，并且同一家店卖与买的价格一样。</p>
<p>cgh给出m个问题，每个问题要求水果姐从第x家店出发到第y家店，途中只能选一家店买一个水果，然后选一家店（可以是同一家店，但不能往回走）卖出去。求最多可以赚多少钱。</p>
<p>水果姐向学过oi的你求助。</p>

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
<p>下来n-1行，每行两个整数x，y，表示第x家店和第y家店有一条边。</p>
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
<p>10<br>16 5 1 15 15 1 8 9 9 15 <br>1 2<br>1 3<br>2 4<br>2 5<br>2 6<br>6 7<br>4 8<br>1 9<br>1 10<br>6<br>9 1<br>5 1<br>1 7<br>3 3<br>1 1<br>3 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7<br>11<br>7<br>0<br>0<br>15</p>

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
<p>0&lt;n&lt;=200000</p>
<p>0&lt;m&lt;=10000</p>
</div>
</div>