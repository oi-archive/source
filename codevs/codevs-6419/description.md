<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">“<span style="font-family: 'DejaVu Sans';">我是要成为狮子王的狮子！”，FXB一边喊着这样的口号，一边和他的伙伴们一起踏上了狮子王之路的艰险历程。</span></p><p style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><img src="/source/codevs/codevs-6419/img/aHR0cDovL21lZGlhLm9wZW5qdWRnZS5jbi9pbWFnZXMvdXBsb2FkLzEzNDAwNzM3OTMuanBn.jpg" style=""></p><p style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'DejaVu Sans';">FXB他们<span style="font-family: 'DejaVu Sans';">狮子王之路</span>行程的起点是罗格镇，终点是拉夫德鲁（那里藏匿着狮子王的象征（“Lion King”））</span><span style="font-family: 'DejaVu Sans';">。而航程中间，则是各式各样的岛屿。</span></p><p style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'DejaVu Sans';">因为<span style="font-family: 'DejaVu Sans';">狮子王之路</span>上的气候十分异常，所以来往任意两个岛屿之间的时间差别很大，从</span>A<span style="font-family: 'DejaVu Sans';">岛到</span>B<span style="font-family: 'DejaVu Sans';">岛可能需要</span>1<span style="font-family: 'DejaVu Sans';">天，而从</span>B<span style="font-family: 'DejaVu Sans';">岛到</span>A<span style="font-family: 'DejaVu Sans';">岛则可能需要</span>1<span style="font-family: 'DejaVu Sans';">年。当然，任意两个岛之间的航行时间虽然差别很大，但都是已知的。</span></p><p style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'DejaVu Sans';">现在假设FXB一行从罗格镇（起点）出发，遍历<span style="font-family: 'DejaVu Sans';">狮子王之路</span>中间所有的岛屿（但是已经经过的岛屿不能再次经过），最后到达拉夫德鲁（终点）。假设他们在岛上不作任何的停留，请问，他们最少需要花费多少时间才能到达终点？</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">输入数据包含多行。</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">第一行包含一个整数N(2 &lt; N ≤ 16)，代表狮子王之路上一共有N个岛屿（包含起点的罗格镇和终点的拉夫德鲁）。其中，起点的编号为1，终点的编号为N。</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">之后的N行每一行包含N个整数，其中，第i(1 ≤ i ≤ N)行的第j(1 ≤ j ≤ N)个整数代表从第i个岛屿出发到第j个岛屿需要的时间t(0 &lt; t &lt; 10000)。第i行第i个整数为0。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(35, 31, 23); font-family: &#39;Lucida Grande&#39;, Verdana, &#39;Bitstream Vera Sans&#39;, Arial, sans-serif; font-size: 14px; line-height: 21px;">输出为一个整数，代表FXB一行从起点遍历所有中间岛屿（不重复）之后到达终点所需要的最少的时间。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="font-family: 'Courier New';">4
0 10 20 999
5 0 90 30
99 50 0 10
999 1 2 0</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="font-family: 'Courier New';">100</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">提示：</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">对于样例输入1：FXB选择从起点岛屿1出发，依次经过岛屿3，岛屿2，最后到达终点岛屿4。花费时间为20+50+30=100。</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">对于样例输入2：可能的路径及总时间为：</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">1,2,3,4,5: 18+45+96+52=211</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">1,2,4,3,5: 18+78+29+12=137</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">1,3,2,4,5: 13+38+78+52=181</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">1,3,4,2,5: 13+96+19+43=171</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">1,4,2,3,5: 98+19+45+12=174</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">1,4,3,2,5: 98+29+38+43=208</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">所以最短的时间花费为137</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">单纯的枚举在N=16时需要14!次运算，一定会超时。</span></p>
</div>
</div>