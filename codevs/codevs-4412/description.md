<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><img src="/source/codevs/codevs-4412/img/aHR0cDovL29qLmp6eHgubmV0L3VwbG9hZC8xMTUzLmpwZw==.jpg"><br>&lt;a href="http://www.jzxx.net/Student/ShowArticle.asp?ArticleID=15648" target="_blank"&gt;汉诺塔（又称河内塔）&lt;/a&gt;问题是印度的一个古老的传说。开天辟地的神勃拉玛在一个庙里留下了三根金刚石的棒，第一根上面套着64个圆的金片，最大的一个在底下，其余一个比一个小，依次叠上去，庙里的众僧不倦地把它们一个个地从这根棒搬到另一根棒上，规定可利用中间的一根棒作为帮助，但每次只能搬一个，而且大的不能放在小的上面。面对庞大的数字(移动圆片的次数)18446744073709551615，看来，众僧们耗尽毕生精力也不可能完成金片的移动。
后来，这个传说就演变为汉诺塔游戏: 　　1.有三根杆子A,B,C。A杆上有若干碟子 　　2.每次移动一块碟子,小的只能叠在大的上面
3.把所有碟子从A杆全部移到C杆上　　经过研究发现，汉诺塔的破解很简单，就是按照移动规则向一个方向移动金片：　　如3阶汉诺塔的移动：A→C,A→B,C→B,A→C,B→A,B→C,A→C
此外，汉诺塔问题也是程序设计中的经典递归问题。　　算法思路：　　1.如果只有一个金片，则把该金片从源移动到目标棒，结束。　　2.如果有n个金片，则把前n-1个金片移动到辅助的棒，然后把自己移动到目标棒，最后再把前n-1个移动到目标棒.</p><p> </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一个整数N，表示A柱上有N个碟子。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>若干行，即移动的最少步骤</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><br></p><pre>A To C
A To B
C To B
A To C
B To A
B To C
A To C</pre><p>&lt;a href="http://www.jzxx.net/Student/ShowArticle.asp?ArticleID=15648" target="_blank" style="white-space: normal;"&gt;&lt;/a&gt;<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>自己想吧！3&lt;=n&lt;=15</p>
</div>
</div>