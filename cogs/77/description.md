# 题目描述


<p>
<span>数塔</span> 
</p>
<p>
<span style="font-family:宋体;"><b>问题描述</b> </span> 
</p>
<p>
<span style="font-size:10.5pt;">设有一个三角形的数塔，顶点结点称为根结点，每个结点有一个整数数值（小于3000）。从顶点出发，可以向左走，也可以向右走。如图所示<span>：从根结点13出发，向左走到达11，再向右走到达7，再向左走到达14，再向左走到达7.由于7是最底层，无路可走。此时，我们找到一条从根结点开始到达底层的路径：</span></span> 
</p>
<p style="text-indent:24pt;text-align:justify;">
<span style="font-size:10.5pt;"><span>13--11--7--14--7</span></span> 
</p>
<p style="text-indent:24pt;text-align:justify;">
<span style="font-size:10.5pt;"><span>路径上结点中数字的和称为路径的值，如上面路径的值为13+11+7+14+7=52。同时，从图中可以看到除了上述路径外，还存在其他的路径，如：</span></span> 
</p>
<p style="text-indent:24pt;text-align:justify;">
<span style="font-size:10.5pt;"><span>13--11--12--14--13</span></span> 
</p>
<p style="text-indent:24pt;text-align:justify;">
<span style="font-size:10.5pt;"><span>其路径的值为63。</span></span> 
</p>
<p style="text-indent:24pt;text-align:justify;">
<span style="font-size:10.5pt;"><span>问题：当三角形数塔给出后，找出一条路径，使路径上的值为最大。若这样的路径存在多条，选根部偏左的路径。</span></span> 
</p>
<p align="left">
<span><img src="/upload/image/20120925/20120925163312_31263.png" alt=""/></span> 
</p>
<p style="text-align:left;" align="left">
<span> </span> 
</p>
<p>
【输入格式】
</p>
<p>
<span><span>    </span>输入由若干行组成，第一行有一个整数，n（1≤n≤80）；n<span>表示</span>数塔的层数。第2至n+1行是数塔的信息。</span> 
</p>
<p>
<span></span>【输出格式】
</p>
<p>
<span><span>    </span><span>输出由两行组成，第</span>一行有一个整数，为所选路径的值。</span> 
</p>
<p>
<span><span>    </span>第二行有n个整数，为所选路径，<span>中间用一个空格隔开。</span></span> 
</p>
<p>
【输入样例】
</p>
<p>
输入文件名：<span><span>shuta.in</span></span> 
</p>
<p>
5<br/>
13<br/>
11 8<br/>
12 7 26<br/>
6 14 15 8<br/>
12 7 13 24 11
</p>
<p>
【输出样例】
</p>
<p>
输出文件名：<span><span>shuta.out</span></span> 
</p>
<p>
<span>86<br/>
13 8 26 15 24</span> 
</p>
