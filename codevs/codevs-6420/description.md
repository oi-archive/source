<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>  一下是一个很有艺术感的排序，它称之为人品排序（然而和人品没有多大关系）。时间并不重要，重要的是艺术，所以本题的数据非常的水（ken）。</p><p>排序方法:</p><p style="">     一二比较，保证升序，三四比较，保证升序({1,2}，{3,4}，{5,6}，……)</p><p style="">——第1(3,5,7，……)层排序。<br></p><p style="">     二三比较，保证升序，四五比较，保证升序({2,3}，{4,5}，{6,7}，……)</p><p style="">——第2(4,6,8，……)层排序。</p><p>不断循环两层排序，直到数据有序。</p><p>(具体见输出数据)。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行:数据个数n；<br></p><p>第二行:n个数据(不保证无序)；</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>接下来k行:</p><p>第i行为第i层排序后的数据；</p><p>第k行为完成排序后的升序数据；<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8</p><p>8 7 6 5 4 3 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7 8 5 6 3 4 1 2</p><p>7 5 8 3 6 1 4 2</p><p>5 7 3 8 1 6 2 4</p><p>5 3 7 1 8 2 6 4</p><p>3 5 1 7 2 8 4 6</p><p>3 1 5 2 7 4 8 6</p><p>1 3 2 5 4 7 6 8</p><p>1 2 3 4 5 6 7 8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，保证n&lt;=16。</p><p>对于100%的数据，保证n&lt;=50,每个数据都在int范围内。</p><p><br></p>
</div>
</div>