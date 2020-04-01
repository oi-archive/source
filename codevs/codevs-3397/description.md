<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><strong>【题目描述】</strong></p>
<p>操场上站着N个小朋友，每个小朋友有一个互不相同的编号，现在老师要改变他们的位置共M次，每次改变为以下一种：</p>
<p>1）选择编号为X的小朋友，移动到编号为Y的小朋友左边；</p>
<p>2）选择编号为X的小朋友，移动到编号为Y的小朋友右边。</p>
<p>请输出M次操作后的队伍。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行包含两个正整数N和M。</p>
<p>接下来一行包含N个数，为初始时小朋友队伍的顺序和他们的编号。</p>
<p>接下来M行，每行三个正整数op，x，y，op表示操作编号，x，y表示选择的小朋友的编号。保证存在编号为x，y的小朋友。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出包括一行共N个数，即操作后的队伍。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 2</p>
<p>1 2 3</p>
<p>2 1 3</p>
<p>2 2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>2≤M,N≤100000</p>
<p>保证队伍中编号互不相同且为1~N。</p>
</div>
</div>