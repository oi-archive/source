<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一个数字的数字根定义为：这个数字每一位的数字加起来求和，反复这个过程直到和小于10。例如，64357的数字根为7，因为6+4+3+5+7=25,2+5=7.一个区间的数字根定义为这个区间所有数字和的数字根。<br> 给定一个序列A1,A2,A3,…，An，你需要回答一些询问。每一个询问给定一个区间[L,R],求出这个区间所有连续子区间里最大的前5个不同的数字根。不够5个的用-1补全。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数N，表示序列的长度。第二行是N个整数Ai（0≤Ai≤10的九次方）。第三哪行是一个整数Q，表示询问次数。接下来Q行，每一行两个正整数l,r,表示询问区间。（1≤l≤r≤N）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>Q行，表示每一个查询区间所有连续子区间里最大的前5个不同的数字根，按降序输出，输出用空格隔开。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5<br>101 240 331 4 52<br>3<br>1 3<br>4 5<br>1 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8 7 6 4 2<br>7 4 2 -1 -1<br>9 8 7 6 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>提示<br> 第一个查询区间[1,3]，它的连续子区间有[1,1],[2,2],[3,3],[1,2],[2,3],[1,3],对应的数字跟分别为2,6,7,8,4,6。所以最大的5个是8,7,6,4,2。</p>
<p>注意<br> 输入较大，C++建议使用scanf()进行输入。</p>
<p>数据范围<br>30%的数据，N≤1000，Q≤1000<br>100%的数据，N≤100000,Q≤100000</p>
</div>
</div>