<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"> 小y是个几何迷。有一天，他画了一个n边形，并且将n个顶点用l，2，…，n这n个连续自然数随手编了一下号。然后他又画了一些不相交的对角线。如下图:</span></p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><img src="/source/codevs/codevs-6063/img/aHR0cDovL3d3dy5nZGZ6b2ouY29tL3VwbG9hZC9mZXRjaF9pbWFnZS8wZWFkYzU2ODI0MGQxN2JkYzU5NWQzOTI1OGE3YjdhNC5qcGc=.jpg" style=""></p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">他把所有的边和对角线都写在一张纸上。对于上图，他写了:(1，3)，(3，2)，(2，4)，(4，5)，(5，1)，(1，4)，(3,4)。</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">过了几个星期，他无意中发现了这张写着字的纸，可是怎么也找不着那个几何图形了。他很想把n边形的编号复原，可是试了一天也没弄出来。你能帮助他吗?</p><p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"></span><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">  第一行n(n&lt;=50)。</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">    下面的若干行，每行两个数a，b，表示纸上写着(a,b)。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 10px; color: rgb(51, 51, 51); font-family: &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px; white-space: normal; background-color: rgb(255, 255, 255);">&nbsp; 仅一行，按顺序依次输出顶点的编号。对于上面的例子，你的输m应该是l 3 2 4 5。</p><p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 10px; color: rgb(51, 51, 51); font-family: &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px; white-space: normal; background-color: rgb(255, 255, 255);">&nbsp;&nbsp;&nbsp; 1 5 4 2 3也是符合题目要求的。两者区别只是逆时针和顺时针而已。</p><p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 10px; color: rgb(51, 51, 51); font-family: &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px; white-space: normal; background-color: rgb(255, 255, 255);">&nbsp;&nbsp;&nbsp; 但是.你的输出只能足l 3 2 4 5!也就是说你必须把两个符合要求的输出比较大小(先比较第一位；第一位相等，就比较第二位；第二位相等……，依此类推)，你的输出应该是较小者!(这只是为了评测的方便)</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">5</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">1 3</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">3 2</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">2 4</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">4 5</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">5 1</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">1 4</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">3 4</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">1 3 2 4 5</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>自检请文件输入输出，提交时请将文件输入输出语句删去以供评测<br></p><p><br></p><p>下为C++版<br></p><pre style="font-family: Menlo, Monaco, Consolas, 'Courier New', monospace;">    int xx,yy,i,j,k;
cin&gt;&gt;n;
while(~scanf("%d%d",&amp;xx,&amp;yy)) {
l[xx][yy]=true;
l[yy][xx]=true;
}</pre><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">可先把题目的输入保存为resume.in的文件中，然后使用文件操作测试，运行后查看resume.out的结果。</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">文件操作：freopen("resume.in","r",stdin);<br style="">                 freopen("resume.out","w",stdout);</p><p><br></p>
</div>
</div>