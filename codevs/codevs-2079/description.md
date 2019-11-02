<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一个夜黑风高,下着暴风雨的夜晚,farmer John的牛棚的屋顶、门被吹飞了。 好在许多牛正在度假，所以牛棚没有住满。 牛棚一个紧挨着另一个被排成一行，牛就住在里面过夜。 有些牛棚里有牛，有些没有。 所有的牛棚有相同的宽度。 自门遗失以后,farmer John必须尽快在牛棚之前竖立起新的木板。 他的新木材供应商将会供应他任何他想要的长度,但是吝啬的供应商只能提供有限数目的木板。 farmer John想将他购买的木板总长度减到最少。</p>
<p>给出:可能买到的木板最大的数目M(1&lt;= M&lt;=50);牛棚的总数S(1&lt;= S&lt;=200); 牛棚里牛的总数C(1 &lt;= C &lt;=S);和牛所在的牛棚的编号stall_number(1 &lt;= stall_number &lt;= S),计算拦住所有有牛的牛棚所需木板的最小总长度。 输出所需木板的最小总长度作为答案。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<ul>
<li>第 1 行: 木板最大的数目M ,牛棚的总数S 和 牛的总数C(用空格分开)</li>
<li>第 2 到 C+1行: 每行包含一个整数，表示牛所占的牛棚的编号。</li>
</ul>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>单独的一行包含一个整数表示所需木板的最小总长度。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>4 50 18
3
4
6
8
14
15
16
17
21
25
26
27
30
31
40
41
42
43</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>25
</pre>
<p>[ 一种最优的安排是用板拦牛棚3-8,14-21,25-31,40-43.]</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见描述</p>
</div>
</div>