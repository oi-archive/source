<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>lxhgww最近收到了一个01序列，序列里面包含了n个数，这些数要么是0，要么是1，现在对于这个序列有五种变换操作和询问操作：</p>
<p>0 a b 把[a, b]区间内的所有数全变成0</p>
<p>1 a b 把[a, b]区间内的所有数全变成1</p>
<p>2 a b 把[a,b]区间内的所有数全部取反，也就是说把所有的0变成1，把所有的1变成0</p>
<p>3 a b 询问[a, b]区间内总共有多少个1</p>
<p>4 a b 询问[a, b]区间内最多有多少个连续的1</p>
<p>对于每一种询问操作，lxhgww都需要给出回答，聪明的程序员们，你们能帮助他吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>   输入数据第一行包括2个数，n和m，分别表示序列的长度和操作数目</p>
<p>   第二行包括n个数，表示序列的初始状态</p>
<p>   接下来m行，每行3个数，op, a, b，（0&lt;=op&lt;=4，0&lt;=a&lt;=b&lt;n）表示对于区间[a, b]执行标号为op的操作</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp;对于每一个询问操作，输出一行，包括1个数，表示其对应的答案</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   10 10</p>
<p>   0 0 0 1 1 0 1 0 1 1</p>
<p>   1 0 2</p>
<p>   3 0 5</p>
<p>   2 2 2</p>
<p>   4 0 4</p>
<p>   0 3 6</p>
<p>   2 3 7</p>
<p>   4 2 8</p>
<p>   1 0 5</p>
<p>   0 5 6</p>
<p>   3 3 9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   5</p>
<p>   2</p>
<p>   6</p>
<p>   5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>   对于30%的数据，1&lt;=n, m&lt;=1000</p>
<p>   对于100%的数据，1&lt;=n, m&lt;=100000</p>
</div>
</div>