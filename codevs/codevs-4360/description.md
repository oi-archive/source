<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>人类喜欢许下各种各样的祈愿,祈愿的感应强度是可以用数值来表示的,感应强度较强的祈愿会首先被神灵所响应而得到实现.<br></p><p>但是因为人类的祈愿太多了,现在SatiyaAugust已经没有办法很快的选出她想要帮助人类实现的祈愿了.</p><p>现在有一些祈愿,每个祈愿有自己的数值,SatiyaAugust让这些祈愿排成了一列.她会向你询问在一段区间l~r中第k大的祈愿,但是人类是一种奇怪的生物,他们的祈愿大小会发生变化.</p><p>一句话题意:单点修改动态k区间第k小</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个数T,表示数据组数.</p><p>每组数据第一行是两个数n,m,n表示祈愿数目,m表示修改和询问的总数.</p><p>接下来一行n个数,表示n个祈愿初始数值.</p><p>接下来m行</p><p>每行开头是一个字母</p><p>若为Q,则下面有三个整数l,r,k,表示查询a[l]~a[r]中第k小</p><p>若为C,则接下来两个整数x,k,表示修改a[x]为k</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对每个询问,输出相应的值</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1</p><p>2 3</p><p>1 2</p><p>Q 1 2 1</p><p>C 1 3</p><p>Q 1 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p><p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>T&lt;=5</p><p>N&lt;=50000 M&lt;=10000 0&lt;=a[i]&lt;=10^9</p>
</div>
</div>