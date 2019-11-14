<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style=""><strong><span style="text-decoration: none;">由于未知原因，<strong style="">该题无法提交评测，请跳转到http://codevs.cn/problem/4243/！</strong></span></strong></span><br></p><p style=""><span style="text-decoration: line-through;"><br></span></p><p style=""><span style="text-decoration: line-through;">Urimoo养了一群小猪猪，Ta很开心，每天看着这些小猪猪。</span></p><p style=""><span style="text-decoration: line-through;">但是当他上了DYYZ之后他就不能天天看这些小猪猪了QAQ。</span></p><p style=""><span style="text-decoration: line-through;">3年后，他回到DYYZ的老机房，来看这些小猪猪（他把猪猪养哪啦？）</span></p><p style=""><span style="text-decoration: line-through;">他发现这些小猪已经可以无性繁殖了！而且一个小猪可能有很多很多的孩纸！</span></p><p style=""><span style="text-decoration: line-through;">他惊奇地发现每一只小猪都有自己独特的颜色！</span></p><p style=""><span style="text-decoration: line-through;">他凌乱了，看着面前一大堆小猪不知道编号为i的小猪猪一共有几个颜色为i的后代。</span></p><p style=""><span style="text-decoration: line-through;">但是这小猪猪的数量和祖先关系是知道的。</span></p><p style=""><span style="text-decoration: line-through;">小猪猪总数为n，编号为1到n。</span></p><p style=""><span style="text-decoration: line-through;">颜色数为k，编号为0到k-1.</span></p><p style=""><span style="text-decoration: line-through;">你来帮帮他吧！</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="text-decoration: line-through;">第一行两个整数n, k，表示面前有n只猪猪，有k种颜色。</span></p><p style=""><span style="text-decoration: line-through;">下面n-1行，每行三个整数u, v, c，表示编号为u的猪猪有个编号为v，颜色为c的孩子。</span></p><p style=""><span style="text-decoration: line-through;">接下来一行一个整数m，表示有m次询问，</span></p><p style=""><span style="text-decoration: line-through;">接下来m行，每行两个整数x, q，表示询问编号为x的小猪猪一共有几个q颜色的后代（算上他自己）？</span></p><p><span style="text-decoration: line-through;">输入数据保证是一颗有根单向树，根节点只有一个</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="text-decoration: line-through;">对于每次询问，输出编号为x的小猪猪一共有几个q颜色的后代（算上他自己）</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="text-decoration: line-through;">3 1</span></p><p style=""><span style="text-decoration: line-through;">1 2 0</span></p><p style=""><span style="text-decoration: line-through;">1 3 0</span></p><p style=""><span style="text-decoration: line-through;">2</span></p><p style=""><span style="text-decoration: line-through;">1 0</span></p><p style=""><span style="text-decoration: line-through;">2 0</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="text-decoration: line-through;">3</span></p><p style=""><span style="text-decoration: line-through;">1</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="text-decoration: line-through;">1 &lt; n &lt;= 100000,</span></p><p style=""><span style="text-decoration: line-through;">1 &lt; m &lt;= 100000,</span></p><p style=""><span style="text-decoration: line-through;">1 &lt; k &lt;= 80.</span></p><p style=""><span style="text-decoration: line-through;">样例图片：</span></p><p style=""><img src="/source/codevs/codevs-4193/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy00MTkzL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvYmxvYl8yMDE1MDkyMzIyMjQzN185MDgucG5n.png" title=""></p><p style=""><br></p><p style=""><span style="font-family: 'comic sans ms'; text-decoration: line-through;">                                                                    SBJ, 2015-9-23 from DYYZ.</span></p><p><span style="font-family: 'comic sans ms'; text-decoration: line-through;"><br></span></p><p><br></p>
</div>
</div>