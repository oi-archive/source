<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>      在幻想乡，上白泽慧音是以知识渊博闻名的老师。春雪异变导致人间之里的很多道路都被大雪堵塞，使有的学生不能顺利地到达慧音所在的村庄。因此慧音决定换一个能够聚集最多人数的村庄作为新的教学地点。人间之里由N个村庄（编号为1..N）和M条道路组成，道路分为两种一种为单向通行的，一种为双向通行的，分别用1和2来标记。如果存在由村庄A到达村庄B的通路，那么我们认为可以从村庄A到达村庄B，记为(A,B)。当(A,B)和(B,A)同时满足时，我们认为A,B是绝对连通的，记为&lt;A,B&gt;。绝对连通区域是指一个村庄的集合，在这个集合中任意两个村庄X,Y都满足&lt;X,Y&gt;。现在你的任务是，找出最大的绝对连通区域，并将这个绝对连通区域的村庄按编号依次输出。若存在两个最大的，输出字典序最小的，比如当存在1,3,4和2,5,6这两个最大连通区域时，输出的是1,3,4。 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：两个正整数N,M</p>
<p>第2..M+1行：每行三个正整数a,b,t, t = 1表示存在从村庄a到b的单向道路，t = 2表示村庄a,b之间存在双向通行的道路。保证每条道路只出现一次。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第1行： 1个整数，表示最大的绝对连通区域包含的村庄个数。</p>
<p>第2行：若干个整数，依次输出最大的绝对连通区域所包含的村庄编号。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5</p>
<p>1 2 1</p>
<p>1 3 2</p>
<p>2 4 2</p>
<p>5 1 2</p>
<p>3 5 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>1 3 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于60%的数据：N &lt;= 200且M &lt;= 10,000</p>
<p>对于100%的数据：N &lt;= 5,000且M &lt;= 50,000</p>
</div>
</div>