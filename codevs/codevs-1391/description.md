<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在幻想乡，伊吹萃香是能够控制物体密度的鬼王。因为能够控制密度，所以萃香能够制造白洞和黑洞，并可以随时改变它们。某一天萃香闲着无聊，在妖怪之山上设置了一些白洞或黑洞，由于引力的影响，给妖怪们带来了很大的麻烦。于是他们决定找出一条消耗体力最少的路，来方便进出。已知妖怪之山上有N个路口(编号1..N)，每个路口都被萃香设置了一定质量白洞或者黑洞。原本在各个路口之间有M条单向路，走过每一条路需要消耗一定量的体力以及1个单位的时间。由于白洞和黑洞的存在，走过每条路需要消耗的体力也就产生了变化，假设一条道路两端路口黑白洞的质量差为delta：</p>
<p>1. 从有白洞的路口走向有黑洞的路口，消耗的体力值减少delta，若该条路径消耗的体力值变为负数的话，取为0。</p>
<p>2. 从有黑洞的路口走向有白洞的路口，消耗的体力值增加delta。</p>
<p>3. 如果路口两端均为白洞或黑洞，消耗的体力值无变化。</p>
<p>由于光是放置黑洞白洞不足以体现萃香的强大，所以她决定每过1个单位时间，就把所有路口的白洞改成黑洞，黑洞改成白洞。当然在走的过程中你可以选择在一个路口上停留1个单位的时间，如果当前路口为白洞，则不消耗体力，否则消耗s[i]的体力。现在请你计算从路口1走到路口N最小的体力消耗。保证一定存在道路从路口1到路口N。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：2个正整数N, M</p>
<p>第2行：N个整数，第i个数为0表示第i个路口开始时为白洞，1表示黑洞</p>
<p>第3行：N个整数，第i个数表示第i个路口设置的白洞或黑洞的质量w[i]</p>
<p>第4行：N个整数，第i个数表示在第i个路口停留消耗的体力s[i]</p>
<p>第5..M+4行：每行3个整数，u, v, k，表示在没有影响的情况下，从路口u走到路口v需要消耗k的体力。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第1行：1个整数，表示消耗的最小体力</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 5</p>
<p>1 0 1 0</p>
<p>10 10 100 10</p>
<p>5 20 15 10</p>
<p>1 2 30</p>
<p>2 3 40</p>
<p>1 3 20</p>
<p>1 4 200</p>
<p>3 4 200</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>130</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据：1 &lt;= N &lt;= 100, 1 &lt;= M &lt;= 500</p>
<p>对于60%的数据：1 &lt;= N &lt;= 1,000, 1 &lt;= M &lt;= 5,000</p>
<p>对于100%的数据：1 &lt;= N &lt;= 5,000, 1 &lt;= M &lt;= 30,000</p>
<p>其中20%的数据为1 &lt;= N &lt;= 3000的链</p>
<p>1 &lt;= u,v &lt;= N, 1 &lt;= k,w[i],s[i] &lt;= 200</p>
<p>按照1 -&gt; 3 -&gt; 4的路线。</p>
</div>
</div>