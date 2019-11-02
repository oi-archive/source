<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">有一个n行m列的方阵，从某个方格可以通向上下左右（如果存在）的任一方格。Alice的任务是从第一行中找一个方格开始，经过某些方格，到最后一行的某个方格结束。有k个方格已经被破坏，不能作为出发点，结束点，或者被经过。Bob想要再破坏几个点从而让Alice无法完成任务，他想知道至少要破坏几个。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行为三个整数n，m，k。</span></p><p><span style="">接下来k行，每行一对整数x，y，表示第x行第y列的方格已经被破坏（被破坏的方格可能重复给出）。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="FONT-SIZE: 14px; FONT-FAMILY: 宋体">仅一行，一个非负整数，表示Bob最少需要再破坏的方格数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">5 5 3</span></p><p><span style="">4 1</span></p><p><span style="">2 3</span></p><p><span style="">4 5</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于样例，只要将第3行第2列，第3行第4列的两个方格再进行破坏即可。</span></p><p><span style="">对于全部20个数据点，</span>0&lt;x&lt;=n&lt;=1,000,000,000<span style="">，</span>0&lt;y&lt;=m&lt;=1,000,000,000<span style="">，</span>0&lt;=k&lt;=500,000<span style="">。</span></p><p><span style="">另外有特殊条件：</span></p><table cellpadding="0" cellspacing="0"><tbody><tr><td style="" valign="top" width="116"><p style=""><span style="">数据点编号</span></p></td><td style="" valign="top" width="452"><p style=""><span style="">特殊条件</span></p></td></tr><tr><td style="" valign="top" width="116"><p style="">1</p></td><td style="" valign="top" width="452"><p style="">n=1</p></td></tr><tr><td style="" valign="top" width="116"><p style="">2</p></td><td style="" valign="top" width="452"><p style="">m=1</p></td></tr><tr><td style="" valign="top" width="116"><p style="">3,4,5</p></td><td style="" valign="top" width="452"><p style="">n,m&lt;=4<span style="">，</span>k&lt;=10</p></td></tr><tr><td style="" valign="top" width="116"><p style="">6,7,8</p></td><td style="" valign="top" width="452"><p style="">n,m&lt;=8<span style="">，</span>k&lt;=50</p></td></tr><tr style=""><td height="16" style="" valign="top" width="116"><p style="">9,10,11,12,13,14</p></td><td height="16" style="" valign="top" width="452"><p style="">k&lt;=1,000</p></td></tr><tr style=""><td height="15" style="" valign="top" width="116"><p style="">15,16,17,18,19,20</p></td><td height="15" style="" valign="top" width="452"><p style="">n,m&lt;=1,000</p></td></tr></tbody></table><p><span style=""> </span></p><p><br></p>
</div>
</div>