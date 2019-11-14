<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    在几何课上，老师画了一个圆，圆上有很多条弦，这些弦两两不重合，但是有些是相交的。你本想把图临摹下来回家好好研究，可惜下课后，图被值日生擦掉了。幸运的是，你准确地记录了弦的数量和弦的相交情况。<br>    现在，你想尽量复原这张图。同时你还想知道，最多能选出多少条弦，使得选出来的弦两两不相交。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第一行包含2 个正整数n,m，分别表示弦的条数以及相交弦的对数，所有的弦从1 至n 编号。<br>    接下来m 行每行两个正整数a,b，表示第a 条弦与第b 条弦相交。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; 输出分为两行。<br />&nbsp; &nbsp; 第一行输出2n 个正整数，按逆时针方向给出满足题意的圆上每条弦的两个端点的相对顺序，其中第i 条弦的两个端点均用数字i 来表示。<br />&nbsp; &nbsp; 第二行输出1 个正整数，表示最多能选多少条两两不相交的弦。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 6<br>1 2<br>1 3<br>2 3<br>2 4<br>3 5<br>4 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 2 3 1 4 2 5 4 3 5<br>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>本题数据均为随机生成。没有在输入中出现的弦对均不相交。如果输出不合法，不得分。<br>对于100% 的数据， 1≤n≤20,1≤m≤40。</p>
</div>
</div>