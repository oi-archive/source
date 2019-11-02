<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>将<span style="font-family: 'Lucida Console';">1</span><span style="">到</span><span style="font-family: 'Lucida Console';">N</span><span style="">的整数数列（</span><span style="font-family: 'Lucida Console';">1</span><span style="">，</span><span style="font-family: 'Lucida Console';">2</span><span style="">，</span><span style="font-family: 'Lucida Console';">3</span><span style="">，……，</span><span style="font-family: 'Lucida Console';">N</span><span style="">）打乱，变为数列</span><span style="font-family: 'Lucida Console';">a</span><span style="">（</span><span style="font-family: 'Lucida Console';">a[1]</span><span style="">，</span><span style="font-family: 'Lucida Console';">a[2]</span><span style="">，</span><span style="font-family: 'Lucida Console';">a[3]</span><span style="">，……，</span><span style="font-family: 'Lucida Console';">a[N]</span><span style="">）。如果这个数列对于任意的</span><span style="font-family: 'Lucida Console';">i</span><span style="">∈</span><span style="font-family: 'Lucida Console';">{1</span><span style="">，</span><span style="font-family: 'Lucida Console';">2</span><span style="">，</span><span style="font-family: 'Lucida Console';">3</span><span style="">，……，</span><span style="font-family: 'Lucida Console';">N}</span><span style="">都满足</span><span style="font-family: 'Lucida Console';">a[a[i]]=N+1-i</span><span style="">，则这个数列叫做长度为</span><span style="font-family: 'Lucida Console';">N</span><span style="">的</span><span style="font-family: 'Lucida Console';">Queen</span><span style="">数列。</span></p>
<p>现给你长度<span style="font-family: 'Lucida Console';">N</span><span style="">，请输出字典序最小的</span><span style="font-family: 'Lucida Console';">Queen</span><span style="">数列。</span></p>
<p>所谓字典序最小，即为<span style="font-family: 'Lucida Console';">a[1]</span><span style="">最小，在此基础上</span><span style="font-family: 'Lucida Console';">a[2]</span><span style="">最小，在此基础上</span><span style="font-family: 'Lucida Console';">a[3]</span><span style="">最小……</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>共一行，为一个整数<span style="font-family: 'Lucida Console';">N</span><span style="">。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">共一行，有<span style="font-family: 'Lucida Console';">i</span><span style="font-family: 宋体;">个整数，以空格隔开（行尾没有空格），第</span><span style="font-family: 'Lucida Console';">i</span><span style="font-family: 宋体;">个整数为</span><span style="font-family: 'Lucida Console';">a[i]</span><span style="font-family: 宋体;">。其中</span><span style="font-family: 'Lucida Console';">a</span><span style="font-family: 宋体;">为字典序最小的长度为</span><span style="font-family: 'Lucida Console';">N</span><span style="font-family: 宋体;">的</span><span style="font-family: 'Lucida Console';">Queen</span><span style="font-family: 宋体;">数列。如果不存在这样的数列，请输出一个</span><span style="font-family: 'Lucida Console';">0</span><span style="font-family: 宋体;">。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>Input1:</p>
<p>3</p>
<p>Input2:</p>
<p>4</p>
<p>Input3:</p>
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Output1:</p>
<p>0</p>
<p>Output2:</p>
<p>2 4 1 3</p>
<p>Output3:</p>
<p>2 5 3 1 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>不存在长度为<span style="font-family: 'Lucida Console';">3</span><span style="">的</span><span style="font-family: 'Lucida Console';">Queen</span><span style="">数列。</span></p>
<p> </p>
<p>2 4 1 3<span style="">为字典序最小的长度为</span><span style="font-family: 'Lucida Console';">4</span><span style="">的</span><span style="font-family: 'Lucida Console';">Queen</span><span style="">数列。</span></p>
<p> </p>
<p>2 5 3 1 4<span style="">为字典序最小的长度为</span><span style="font-family: 'Lucida Console';">5</span><span style="">的</span><span style="font-family: 'Lucida Console';">Queen</span><span style="">数列。</span></p>
<p><span style=""><br></span></p>
<p> </p>
<p>对于<span style="font-family: 'Lucida Console';">20%</span><span style="">的数据，</span><span style="font-family: 'Lucida Console';">N</span><span style="">≤</span><span style="font-family: 'Lucida Console';">10</span><span style="">；对于</span><span style="font-family: 'Lucida Console';">50%</span><span style="">的数据，</span><span style="font-family: 'Lucida Console';">N</span><span style="">≤</span><span style="font-family: 'Lucida Console';">1000</span><span style="">；对于</span><span style="font-family: 'Lucida Console';">100%</span><span style="">的数据，</span><span style="font-family: 'Lucida Console';">1</span><span style="">≤</span><span style="font-family: 'Lucida Console';">N</span><span style="">≤</span><span style="font-family: 'Lucida Console';">200000</span><span style="">。</span></p>
<p><span style=""><br></span></p>
</div>
</div>