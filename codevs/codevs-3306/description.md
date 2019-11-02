<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>连续两天都没有被cgh难倒，水果姐心情很不错，第三天又来逛水果街。</p>
<p>今天cgh早早就来到了水果街等水果姐，因为他带来了帮手cys。cgh的魔法是把水果街变成树结构，而cys的魔法是瞬间改变某家店的水果价格。一边问一边改，绝不给水果姐思考的时间！</p>
<p>同样还是n家水果店，编号为1~n，每家店能买水果也能卖水果，并且同一家店卖与买的价格一样。</p>
<p>cgh和cys一共有m个操作。</p>
<p>操作的格式为</p>
<p>0 x y 获 1 x y</p>
<p>如果操作类型是0，表示cys把第x家店的价格改为y</p>
<p>如果操作类型是1，则表示要求水果姐从第x家店出发到第y家店，途中只能选一家店买一个水果，然后选一家店（可以是同一家店，但不能往回走）卖出去。并且输出最多可以赚多少钱。</p>
<p>这题是给天牛做的。</p>

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
<p>下来一个整数m，表示下来有m个操作。</p>
<p>下来有m行，每行三个整数，表示一次操作。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: 10px;">每行对应一个1类型的操作，输出一个整数，表示面对cgh的每次询问，水果姐最多可以赚到多少钱。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>4</span><br><span>16 5 1 15</span><br><span>1 2</span><br><span>1 3</span><br><span>2 4</span><br><span>3</span><br><span>1 3 4</span><br><span>0 3 17</span><br>1 4 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>15<br>12</p>

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
<p>0&lt;n&lt;=2*10^5</p>
<p>0&lt;m&lt;=10^5</p>
</div>
</div>