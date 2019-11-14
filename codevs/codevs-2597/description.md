<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>1920年的芝加哥，出现了一群强盗。如果两个强盗遇上了，那么他们要么是朋友，要么是敌人。而且有一点是肯定的，就是：</p>
<p>我朋友的朋友是我的朋友；</p>
<p>我敌人的敌人也是我的朋友。 </p>
<p>两个强盗是同一团伙的条件是当且仅当他们是朋友。现在给你一些关于强盗们的信息，问你最多有多少个强盗团伙。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件gangs.in的第一行是一个整数N(2&lt;=N&lt;=1000)，表示强盗的个数（从1编号到N）。 第二行M(1&lt;=M&lt;=5000)，表示关于强盗的信息条数。 以下M行，每行可能是F p q或是E p q（1&lt;=p q&lt;=N），F表示p和q是朋友，E表示p和q是敌人。输入数据保证不会产生信息的矛盾。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件gangs.out只有一行，表示最大可能的团伙数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6<br>4<br>E 1 4<br>F 3 5<br>F 4 6<br>E 1 2</p>

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

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>2&lt;=N&lt;=1000</p>
<p>1&lt;=M&lt;=5000</p>
<p>1&lt;=p q&lt;=N</p>
<p> </p>
</div>
</div>