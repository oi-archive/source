<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>由于一不小心知道了一种叫 LXK 的充满农气的生物,R 现在烦<br>恼极了。更加可怕的是 LXK 的农气是不断增加的!所以,现在 R<br>需要你的帮助。现在有 n 个 LXK,每个有一个农气值记为 A i ,设<br>总操作数为 T。R 会告诉你[L,R]中的 LXK 的农气值增加了 x,或<br>者告诉你一个 v,并询问你所有满足条件 A<sub>l </sub>=v 且 A<sub>r</sub> =v 的(l,r)<br>中,r-l(r,l 可以相等)的最大值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行,两个整数 n 和 T ,意义如题目所述<br>接下来一行,共 n 个正整数<br>第 i 个为 A i ,表示第 i 个的 LXK 初始农气值。<br>再接下来 T 行<br>第一个数 opt,<br>如果 opt=1,再读入三个数,L,R,x,表示[L,R]间的 LXK 农气值<br>增加了 x。<br>如果 opt=2,再读入一个数 v,表示询问。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>若干行整数,每行依次表示对每一个 opt=2 的询问的回答。如果<br/>不存在有 A i =v,输出-1。<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4<br>1 2 3 4<br>1 1 2 1<br>1 1 1 1<br>2 3<br>2 10<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p><p>-1<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 20%,1&lt;=n&lt;=1000,1&lt;=T&lt;=1000<br>对于另 30%,所有 opt=1 的操作个数&lt;=200<br>对于 100%,1&lt;=n&lt;=10<sup>5</sup> ,T&lt;=5*10<sup>4</sup> ,0&lt;A i &lt;=10<sup>9</sup> ,0&lt;x&lt;=10<sup>9</sup> ,0&lt;v&lt;=10<sup>18</sup></p>
</div>
</div>