<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    高考已经结束，而志愿填报正在进行中～</p>
<p>    吴校长的学校里有n位同学，每位同学有ki个愿意去的大学。而在吴老师的省份中，有m所大学有招生名额。根据往年的经验，对于每所大学（编号为ci），学校中最多只会有一人考上。因此为了避免志愿冲突，每年吴校长都要安排老师对同学们的志愿进行调整。</p>
<p>    今年吴校长找到了你来帮忙，请你编程计算，在不冲突的情况下，最多能有多少同学顺利填报志愿，填报志愿的方案又是怎样的。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第一行，一个数n。</p>
<p>    接下来的n行，每行的第一个数为ki，接下来有ki个数，表示第i个同学愿意去的大学的编号。</p>
<p>    下一行，一个数m。 </p>
<p>    下一行，m个数，为m个大学的编号。保证大学编号递增。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">&nbsp; &nbsp; 第一行，一个数，为在不冲突的情况下，最多能有多少同学顺利填报志愿。</p>
<p class="p0">&nbsp;&nbsp;&nbsp;&nbsp;接下来的若干行，输出填报志愿的方案。每行两个数，第一个数为学生编号，第二个数为大学编号，以空格隔开。若有多种可行方案，输出字典序最小的一种。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>2 1 2</p>
<p>3 2 4 5</p>
<p>2 2 3</p>
<p>5</p>
<p>1 3 4 5 6</p>

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
<p>1 1</p>
<p>2 4</p>
<p>3 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>0&lt;n&lt;=1000,0&lt;ki&lt;=20,0&lt;m&lt;=2000,学生的编号为1~n，大学的编号为1~5000。同学愿意去的大学不一定招生。</p>
</div>
</div>
</div>