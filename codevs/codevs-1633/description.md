<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>找到一个数组的最大值的一种方法是从数组开头从前到后对数组进行扫描<span style="font-family: Calibri;">,</span><span style="">令</span><span style="font-family: Calibri;">max=a[0](</span><span style="">数组下表从</span><span style="font-family: Calibri;">0..N-1),</span><span style="">如果</span><span style="font-family: Calibri;">a[i]&gt;max,</span><span style="">就更新</span><span style="font-family: Calibri;">max,</span><span style="">这样就可以在</span><span style="font-family: Calibri;">O(N)</span><span style="">的时间里找到一个数组的最大值。</span></p>
<p>这个问题是相当简单的<span style="font-family: Calibri;">,</span><span style="">但是想到了另一个问题</span><span style="font-family: Calibri;">,</span><span style="">如果一个包含</span><span style="font-family: Calibri;">N</span><span style="">个元素的数组</span><span style="font-family: Calibri;">a</span><span style="">里面的元素的值是在</span><span style="font-family: Calibri;">1...K</span><span style="">之间的整数</span><span style="font-family: Calibri;">,</span><span style="">存在多少个不同的数组</span><span style="font-family: Calibri;">a,</span><span style="">进行了如上扫描之后</span><span style="font-family: Calibri;">,max</span><span style="">恰好进行了</span><span style="font-family: Calibri;">k</span><span style="">次更新</span><span style="font-family: Calibri;">? </span></p>
<p>下面是<span style="font-family: Calibri;">N = 4,K = 3,P = 2</span><span style="">时所有情况</span></p>
<p>1) {1,1,2,3}</p>
<p>2) {1,2,1,3}</p>
<p>3) {1,2,2,3}</p>
<p>4) {1,2,3,1}</p>
<p>5) {1,2,3,2}</p>
<p>6) {1,2,3,3}</p>
<p>共有<span style="font-family: Calibri;">6</span><span style="">种情况</span></p>
<p>由于答案可能很大，所以你仅仅需要把答案<span style="font-family: Calibri;">mod 10^9+7</span><span style="">输出。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件<span style="font-family: Calibri;">findmax</span>.in的第一行<span style="font-family: Calibri;">T,</span><span style="">本题有</span><span style="font-family: Calibri;">T</span><span style="">组数据。</span></p>
<p>接下来<span style="font-family: Calibri;">T</span><span style="">行</span><span style="font-family: Calibri;">,</span><span style="">每行三个整数</span><span style="font-family: Calibri;">,N,K,P</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件<span style="font-family: Calibri;">findmax</span>.out包括<span style="font-family: Calibri;">T</span><span style="font-family: 宋体;">行</span><span style="font-family: Calibri;">,</span><span style="font-family: 宋体;">每行一个答案。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>4 3 2</p>
<p>2 3 1</p>
<p>3 4 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>
<p>3</p>
<p>30</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>【数据规模】</p>
<p>30%<span style="">数据</span></p>
<p>T=1</p>
<p>1 &lt;= n &lt;= 10</p>
<p>1 &lt;= K &lt;= 2</p>
<p>0 &lt;= P &lt; n</p>
<p>60%<span style="">数据</span></p>
<p>T=1</p>
<p>1 &lt;= n &lt;= 50</p>
<p>1 &lt;= K &lt;= 10</p>
<p>0 &lt;= P &lt; n</p>
<p>100%<span style="">数据</span></p>
<p>1 &lt;= T &lt;= 100</p>
<p>1 &lt;= n &lt;= 100</p>
<p>1 &lt;= K &lt;= 300</p>
<p>0 &lt;= P &lt; n</p>
</div>
</div>
</div>