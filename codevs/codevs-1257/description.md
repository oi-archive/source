<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一个凹槽中放置了<span style="font-family: 'Times New Roman';">n</span><span style="">层砖块，最上面的一层有</span><span style="font-family: 'Times New Roman';">n</span><span style="">块砖，第二层有</span><span style="font-family: 'Times New Roman';">n-1</span><span style="">块，</span>……最下面一层仅有一块砖。第<span style="font-family: 'Times New Roman';">i</span><span style="">层的砖块从左至右编号为</span><span style="font-family: 'Times New Roman';">1</span><span style="">，</span><span style="font-family: 'Times New Roman';">2</span><span style="">，</span>……i<span style="">，第</span><span style="font-family: 'Times New Roman';">i</span><span style="">层的第</span><span style="font-family: 'Times New Roman';">j</span><span style="">块砖有一个价值</span><span style="font-family: 'Times New Roman';">a[i,j]</span><span style="">（</span><span style="font-family: 'Times New Roman';">a[i,j]&lt;=50</span><span style="">）。下面是一个有</span><span style="font-family: 'Times New Roman';">5</span><span style="">层砖块的例子。</span><span style="">如果你要敲掉第</span><span style="font-family: 'Times New Roman';">i</span><span style="">层的第</span><span style="font-family: 'Times New Roman';">j</span><span style="">块砖的话，若</span><span style="font-family: 'Times New Roman';">i=1</span><span style="">，你可以直接敲掉它，若</span><span style="font-family: 'Times New Roman';">i&gt;1</span><span style="">，则你必须先敲掉第</span><span style="font-family: 'Times New Roman';">i-1</span><span style="">层的第</span><span style="font-family: 'Times New Roman';">j</span><span style="">和第</span><span style="font-family: 'Times New Roman';">j+1</span><span style="">块砖。</span></p>
<p> </p>
<p>你的任务是从一个有<span>n</span><span>（</span><span>n&lt;=50</span><span>）层的砖块堆中，敲掉</span><span>(m&lt;=500)</span><span>块砖，使得被敲掉的这些砖块的价值总和最大。</span></p>
<p> </p>
<p> </p>
<p><span style=""><br></span></p>

<img src="/source/codevs/codevs-1257/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9pbWFnZS9wcm9ibGVtLzEyNTcuZ2lm.gif" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>你将从文件<span style="">中读入数据，数据的第一行为两个正整数，分别表示</span><span style="font-family: 'Times New Roman';">n,m</span><span style="">，接下来的第</span><span style="font-family: 'Times New Roman';">i</span><span style="">每行有</span><span style="font-family: 'Times New Roman';">n-i+1</span><span style="">个数据，分别表示</span><span style="font-family: 'Times New Roman';">a[i,1],a[i,2]</span>……a[i,n – i + 1]<span style="">。</span></p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件<span style="font-family: 宋体;">中仅有一个正整数，表示被敲掉砖块的最大价值总和。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 5</p>
<p>2 2 3 4</p>
<p>8 2 7</p>
<p>2 3</p>
<p>49</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>19</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>敲掉第一层的四块砖，再敲掉第二层的第一块砖，<span style="font-family: 'Times New Roman';">2+2+3+4+8=19</span></p>
</div>
</div>