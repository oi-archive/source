<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">求长方体a[1,1,1]到a[n,m,p]的所有路径中和最大的路径，并输出这个和。</span><br></p><p><span style=""><img src="/source/codevs/codevs-4864/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9ibG9iXzIwMTYwNDA5MTcxNTQ4XzEwMy5wbmc=.png" title=""></span></p><p><span style=""><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行：3个数n,m,p（分别代表长方形的高、宽、长）；</span></p><p><span style="">第n*m行：n个矩阵（一个一个平面输入）</span></p><p><span style=""><img src="/source/codevs/codevs-4864/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9ibG9iXzIwMTYwNDA5MTcxNzEwXzQzOS5wbmc=.png" title=""></span></p><p><span style=""><br></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 楷体, 楷体_GB2312, SimKai;">一行：最大路径和。</span></p><p><span style="font-family: 楷体, 楷体_GB2312, SimKai;"><img src="/source/codevs/codevs-4864/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9ibG9iXzIwMTYwNDA5MTcxNzMzXzc1Ni5wbmc=.png" title="" alt="blob.png"/></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'andale mono';">-----------1-------------</span></p><p><span style="font-family: 'andale mono';">3 3 3</span></p><p><span style="font-family: 'andale mono';">443 110 600 </span></p><p><span style="font-family: 'andale mono';">947 587 241 </span></p><p><span style="font-family: 'andale mono';">152 248 288 </span></p><p><span style="font-family: 'andale mono';">765 282 934 </span></p><p><span style="font-family: 'andale mono';">918 907 597 </span></p><p><span style="font-family: 'andale mono';">587 427 759 </span></p><p><span style="font-family: 'andale mono';">857 836 566 </span></p><p><span style="font-family: 'andale mono';">636 843 325 </span></p><p><span style="font-family: 'andale mono';">508 888 575 </span></p><p><span style="font-family: 'andale mono';">-----------2-------------</span></p><p><span style="font-family: 'andale mono';">2 2 2</span></p><p><span style="font-family: 'andale mono';">88 84 </span></p><p><span style="font-family: 'andale mono';">2 31 </span></p><p><span style="font-family: 'andale mono';">93 35 </span></p><p><span style="font-family: 'andale mono';">14 44</span></p><p><span style="font-family: 'andale mono';"><img src="/source/codevs/codevs-4864/img/aHR0cDovL2NvZGV2cy5jbi9hY2NvdW50cy9hdmF0YXIvNWYxNTVkY2U5MDFjMzkxYzE1NWJhZTJjZjgxOTk3ODgtODAucG5n.png"></span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'andale mono';">---------1--------</span></p><p><span style="font-family: 'andale mono';">5521</span></p><p><span style="font-family: 'andale mono';">---------2--------</span></p><p><span style="font-family: 'andale mono';">260</span></p><p><span style="font-family: 'andale mono';"><img src="/source/codevs/codevs-4864/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9ibG9iXzIwMTYwNDA5MTcxNzUyXzU3MC5wbmc=.png" title=""></span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;50 m&lt;50 p&lt;50 每个数不超过1000000000</p><p><img src="/source/codevs/codevs-4864/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9ibG9iXzIwMTYwNDA5MTcxODMzXzQ4Ni5wbmc=.png" title=""></p>
</div>
</div>