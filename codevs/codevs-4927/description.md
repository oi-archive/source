<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有n个数和5种操作</p><p>add a b c：把区间[a,b]内的所有数都增加c</p><p>set a b c：把区间[a,b]内的所有数都设为c</p><p>sum a b：查询区间[a,b]的区间和</p><p>max a b：查询区间[a,b]的最大值</p><p>min a b：查询区间[a,b]的最小值</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数n，m，第二行n个整数表示这n个数的初始值</p><p>接下来m行操作，同题目描述</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于所有的sum、max、min询问，一行输出一个答案</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 6</p><p>3 9 2 8 1 7 5 0 4 6</p><p>add 4 9 4</p><p>set 2 6 2</p><p>add 3 8 2</p><p>sum 2 10</p><p>max 1 7</p><p>min 3 6</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>49</p><p>11</p><p>4</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>10%:1&lt;n,m&lt;=10</p><p>30%:1&lt;n,m&lt;=10000</p><p>100%:1&lt;n,m&lt;=100000</p><p>保证中间结果在long long(C/C++)、int64(pascal)范围内</p><p><br></p><p>PS:由于数据6出错导致某些人只有90分，已于2016.5.13修正。</p><p>出题人在此对两位90分的用户表示诚挚的歉意</p>
</div>
</div>