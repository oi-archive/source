<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>学校里有一个水房，水房里一共装有m 个龙头可供同学们打开水，每个龙头每秒钟的供水量相等，均为1。</p>
<p><br>现在有n 名同学准备接水，他们的初始接水顺序已经确定。将这些同学按接水顺序从1到n 编号，i 号同学的接水量为wi。接水开始时，1 到m 号同学各占一个水龙头，并同时打开水龙头接水。当其中某名同学j 完成其接水量要求wj 后，下一名排队等候接水的同学k马上接替j 同学的位置开始接水。这个换人的过程是瞬间完成的，且没有任何水的浪费。即j 同学第x 秒结束时完成接水，则k 同学第x+1 秒立刻开始接水。若当前接水人数n’不足m，则只有n’个龙头供水，其它m−n’个龙头关闭。</p>
<p><br>现在给出n 名同学的接水量，按照上述接水规则，问所有同学都接完水需要多少秒。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1 行2 个整数n 和m，用一个空格隔开，分别表示接水人数和龙头个数。<br>第2 行n 个整数w1、w2、……、wn，每两个整数之间用一个空格隔开，wi 表示i 号同<br>学的接水量。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行，1 个整数，表示接水所需的总时间。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 3<br>4 4 1 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=10000, m&lt;=100</p>
<p>第1 秒，3 人接水。第1 秒结束时，1、2、3 号同学每人的已接水量为1，3 号同学接完水，4 号同学接替3 号同学开始接水。<br>第2 秒，3 人接水。第2 秒结束时，1、2 号同学每人的已接水量为2，4 号同学的已接水量为1。<br>第3 秒，3 人接水。第3 秒结束时，1、2 号同学每人的已接水量为3，4 号同学的已接水量为2。4 号同学接完水，5 号同学接替4 号同学开始接水。<br>第4 秒，3 人接水。第4 秒结束时，1、2 号同学每人的已接水量为4，5 号同学的已接水量为1。1、2、5 号同学接完水，即所有人完成接水。<br>总接水时间为4 秒。</p>
</div>
</div>