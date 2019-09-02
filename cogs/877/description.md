
USACO/fence4(
# x3,y3


<p>
<span id=".E6.A0.BC.E5.BC.8F" class="mw-headline">格式</span> 
</p>
<p>
<b>PROGRAM NAME</b>: fence4
</p>
<p>
<b>INPUT FORMAT</b>:
</p>
<p>
(file fence4.in)
</p>
<p>
第一行: N, 表示闭合栅栏的顶点数。
</p>
<p>
第二行: 两个整数x和y，表示观测者的位置。两个整数都是16位的。即2^16，在longlong或longint范围内。
</p>
<p>
第3到N+2行: 每行一对整数(x,y)表示对应闭合栅栏的第k个顶点的坐标。坐标以逆时针顺序给出。整数绝对值不超过1000。
</p>
<p>
<b>注意：我添加了该题的新的第12个测试点。如果你认为这个点的数据是错误的，发送邮件到Rob（kolstad@ace.delos.com）在您的邮件主题中一定要包括USACO！</b> 
</p>
<p>
<b>OUTPUT FORMAT</b>:
</p>
<p>
(file fence4.out)
</p>
<p>
如果给出的序列不是一个合法的闭合栅栏，那么输出文件只需要输出“NOFENCE”。
</p>
<p>
栅栏用两端的顶点表示，顶点的输出顺序以输入文件中的顺序为准。把栅栏按照最后一个点在输入文件中的顺序排序。如果两条栅栏的最后一个点是一样的，就以它们第一个点的顺序排序。
</p>
<p>
<span id="SAMPLE_INPUT" class="mw-headline">SAMPLE INPUT </span> 
</p>
<pre>13
5 5
0 0
7 0
5 2
7 5
5 7
3 5
4 9
1 8
2 5
0 9
-2 7
0 3
-3 1 <span id="SAMPLE_OUTPUT" class="mw-headline">SAMPLE OUTPUT </span> 
<pre>7
0 0 7 0
5 2 7 5
7 5 5 7
5 7 3 5
-2 7 0 3
0 0 -3 1
0 3 -3 1
</pre>
<!-- NewPP limit report Preprocessor node count: 15/1000000 Post-expand include size: 0/2097152 bytes Template argument size: 0/2097152 bytes Expensive parser function count: 0/100 --><!-- Saved in parser cache with key newnocow:pcache:idhash:856-0!*!*!!zh-cn!*!* and timestamp 20120711023612 --></pre>
