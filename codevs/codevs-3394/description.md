<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定一个包含N个数的数列，请将它按顺序分割为M个新数列，分割规则如下：</p>
<p>1）第i个元素将被分割进入第(i mod M)+1个数列中；</p>
<p>2）新数列中的元素按照被分割的顺序，新分割到的数放在最后。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行包含两个正整数N和M。</p>
<p>接下来一行包含N个数，为待分割的序列。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p align="left">输出包括M行，第k行为分割后的第k个序列。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7 3</p>
<p>1 3 5 7 2 4 8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5 4</p>
<p>1 7 8</p>
<p>3 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>2≤M≤N≤10000</p>
<p>保证M接近于√N，且数列中每个数小于32767。</p>
</div>
</div>