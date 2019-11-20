<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>卡门——农夫约翰极其珍视的一条Holsteins奶牛——已经落了到“垃圾井”中。“垃圾井”是农夫们扔垃圾的地方，它的深度为D (2 &lt;= D &lt;= 100)英尺。</p>
<p>卡门想把垃圾堆起来，等到堆得与井同样高时，她就能逃出井外了。另外，卡门可以通过吃一些垃圾来维持自己的生命。</p>
<p>每个垃圾都可以用来吃或堆放，并且堆放垃圾不用花费卡门的时间。</p>
<p>假设卡门预先知道了每个垃圾扔下的时间t(0&lt;t&lt;=1000)，以及每个垃圾堆放的高度h(1&lt;=h&lt;=25)和吃进该垃圾能维持生命的时间f(1&lt;=f&lt;=30)，要求出卡门最早能逃出井外的时间，假设卡门当前体内有足够持续10小时的能量，如果卡门10小时内没有进食，卡门就将饿死。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为2个整数，D 和 G (1 &lt;= G &lt;= 100)，G为被投入井的垃圾的数量。</p>
<p>第二到第G+1行每行包括3个整数：T (0 &lt; T &lt;= 1000)，表示垃圾被投进井中的时间；F (1 &lt;= F &lt;= 30)，表示该垃圾能维持卡门生命的时间；和 H (1 &lt;= H &lt;= 25)，该垃圾能垫高的高度。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">如果卡门可以爬出陷阱，输出一个整表示最早什么时候可以爬出；否则输出卡门最长可以存活多长时间。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>20 4</p>
<p>5 4 9</p>
<p>9 3 2</p>
<p>12 6 10</p>
<p>13 1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>13</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>[样例说明]</p>
<p>卡门堆放她收到的第一个垃圾：height=9；</p>
<p>卡门吃掉她收到的第二个垃圾，使她的生命从10小时延伸到13小时；</p>
<p>卡门堆放第3个垃圾，height=19；</p>
<p>卡门堆放第4个垃圾，height=20。</p>
</div>
</div>