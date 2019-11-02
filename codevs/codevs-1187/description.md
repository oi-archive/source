<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>MT<span style="">神牛非常喜欢出</span><span style="font-family: 'Times New Roman';">Xor</span><span style="">的题，在</span><span style="font-family: 'Times New Roman';">WC2011</span><span style="">的时候，</span><span style="font-family: 'Times New Roman';">MT</span><span style="">神牛出了一道非常经典的</span><span style="font-family: 'Times New Roman';">Xor</span><span style="">最大路径题。</span></p>
<p>Cyz<span style="">向</span><span style="font-family: 'Times New Roman';">MT</span><span style="">神牛学习，思考了许多关于</span><span style="font-family: 'Times New Roman';">Xor</span><span style="">路径的问题，有一天，</span><span style="font-family: 'Times New Roman';">Cyz</span><span style="">想到了一个问题，给出一个序列，求这个序列的连续子序列的</span><span style="font-family: 'Times New Roman';">Xor</span><span style="">值最大。</span></p>
<p>如<span style="font-family: 'Times New Roman';">1 3 4 8</span><span style="">，最大的</span><span style="font-family: 'Times New Roman';">Xor</span><span style="">子序列当然是</span><span style="font-family: 'Times New Roman';">3 xor 4 xor 8=15</span><span style="">了。</span></p>
<p>Cyz<span style="">实在太强大了，这个问题怎么能难住他呢？于是</span><span style="font-family: 'Times New Roman';">Cyz</span><span style="">又开始思考了，如果是一颗树呢，如何求出这棵带边权的树的一条最大</span><span style="font-family: 'Times New Roman';">Xor</span><span style="">路径呢？但是谁都知道</span><span style="font-family: 'Times New Roman';">Cyz</span><span style="">实在太强大了，马上想到了解决这个问题的高效算法，但是</span><span style="font-family: 'Times New Roman';">Cyz</span><span style="">总是不愿去机房写代码，于是他把这个</span><span style="font-family: 'Times New Roman';">easy</span><span style="">的问题，交给了你，希望你能尽快帮他写完代码。</span></p>
<p> </p>
<p>问题概括：求一棵带边权的树的一条最大<span style="font-family: 'Times New Roman';">Xor</span><span style="">路径的值。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，一个整数N<span style="">，表示一颗树有</span><span style="font-family: 'Times New Roman';">N</span><span style="">个节点，接下来</span><span style="font-family: 'Times New Roman';">N-1</span><span style="">行，每行三个整数</span><span style="font-family: 'Times New Roman';">a,b,c</span><span style="">表示节点</span><span style="font-family: 'Times New Roman';">a</span><span style="">和节点</span><span style="font-family: 'Times New Roman';">b</span><span style="">之间有条权值为</span><span style="font-family: 'Times New Roman';">c</span><span style="">的边</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p15">输出仅一行，即所求的最大值</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>1 2 3</p>
<p>1 3 4</p>
<p>1 4 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据规模】</p>
<p>对于40%<span style="">的数据，数据退化为一条链</span></p>
<p>除上述的<span style="font-family: 'Times New Roman';">40%</span><span style="">的数据外，还有</span><span style="font-family: 'Times New Roman';">10%</span><span style="">的数据</span><span style="font-family: 'Times New Roman';">N&lt;=1000</span></p>
<p>100%<span style="">的数据满足</span><span style="font-family: 'Times New Roman';">2&lt;=n&lt;=100000,1&lt;a,b&lt;=N,C&lt;=2^31-1</span></p>
</div>
</div>