# 题目描述


USACO/fence4(<b>译 by Jeru)</b> 
<div id="bodyContent">
<b></b> 
<div dir="ltr" class="mw-content-ltr" lang="zh-cn">
<b></b> 
<p>
<b>Closed Fences</b>闭合的栅栏
</p>
<hr/>
</div>
</div>
<p>
<span id=".E6.8F.8F.E8.BF.B0" class="mw-headline">描述</span> 
</p>
<p>
一个闭合的栅栏是平面上的一些不相交的首尾相连的线段形成的多边形，有N个角(顶点) (3 &lt; N &lt; 200)。 顶点不重合，它以逆时针方式以数组{x<sub>i</sub>, y<sub>i</sub>}给出(i=1,2,...,N)。
</p>
<p>
每一对相邻的顶点都是一条栅栏。因此共有N条栅栏 (定义x<sub>N+1</sub>=x<sub>1</sub>, y<sub>N+1</sub>=y<sub>1</sub>)。
</p>
<p>
这里有一个栅栏的例子和一个点x,y:
</p>
<pre>                        * x3,y3
                x5,y5  / 
   x,y *          *   /   
                 /  /     
                /   *       
          x6,y6*   x4,y4     
               |              
               |               
          x1,y1*----------------* x2,y2
</pre>
<p>
请编写一个程序实现下面的任务:
</p>
<ul>
<li>
检查输入的顶点列表{xi,yi}, i=1,2,...,N, 判断它是否为一个合法的闭合栅栏。
</li>
<li>
找出所有可以被站在点(x,y)处的人所能看到的栅栏(忽略人的高度)，因为有的栅栏会被另外的栅栏所挡住。
</li>
</ul>
<p>
只有当存在从(x,y)发射的一条射线第一个穿过栅栏i时，栅栏i是可以被看见的。如果栅栏是平行于目光的，它并不认为是可以看见的。在上面的例子里，线段[x3,y3]-[x4,y4], [x5,y5]-[x6,y6], [x6-y6]-[x1,y1]是可以被(x,y)看见的。
</p>
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
