<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>煤矿工地可以看成是由隧道连接挖煤点组成的无向图。为安全起见，希望在工地发生事故时所有挖煤点的工人都能有一条出路逃到救援出口处。于是矿主决定在某些挖煤点设立救援出口，使得无论哪一个挖煤点坍塌之后，其他挖煤点的工人都有一条道路通向救援出口。<br>请写一个程序，用来计算至少需要设置几个救援出口，以及不同最少救援出口的设置方案总数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件有若干组数据，每组数据的第一行是一个正整数N（N≤500），表示工地的隧道数，接下来的N 行每行是用空格隔开的两个整数S 和T，表示挖煤点S 与挖煤点T 由隧道直接连接。输入数据以0 结尾。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输入文件中有多少组数据，输出文件中就有多少行。每行对应一组输入数据的结果。其中第i 行以Case i: 开始（注意大小写，Case 与i 之间有空格，i 与:之间无空格，:之后有空格），其后是用空格隔开的两个正整数，第一个正整数表示对于第i 组输入数据至少需要设置几个救援出口，第二个正整数表示对于第i 组输入数据不同最少救援出口的设置方案总数。输入数据保证答案小于2^64。输出格式参照以下输入输出样例。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>9<br>1 3<br>4 1<br>3 5<br>1 2<br>2 6<br>1 5<br>6 3<br>1 6<br>3 2<br>6<br>1 2<br>1 3<br>2 4<br>2 5<br>3 6<br>3 7<br>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Case 1: 2 4<br>Case 2: 4 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>Case 1 的四组解分别是(2,4),(3,4),(4,5),(4,6)；<br>Case 2 的一组解为(4,5,6,7)。</p>
</div>
</div>