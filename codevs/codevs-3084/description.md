<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>钱宗伟因孙XX毁了他的泡妞计划，决定报复孙某某！</p>
<p>众所周知，中国法律规定，近亲不能结婚（s和尹有关系），于是，钱宗伟跟主管计划生育的人说他们是近亲。</p>
<p>现在，主管部门想让你来完成如下问题：</p>
<p>众所周知，人类基因可以被简单认为是一个字符串，包含四种分别用A,C,T,G表示的核苷酸。生物学家对鉴别人类基因核确定他们的功能很感兴趣。因为这对诊断人类疾病和开发新药很有用。人类基因可以用一堆特别的快速的试验来鉴别，而且通常要借助电脑的帮助一旦基因序列测定了，下一步就可以确定它的功能了。生物学家确定一个新鉴定了的基因的功能的方法之一是在在基因数据库里和其他基因对照。要搜索的数据库里储存了很多的基因和它们的功能－－很多研究人员提交了他们的研究基因和功能到数据库，而数据库是在互联网上公开的。</p>
<p>数据库会返回一堆最相近基因。生物学家们假设类似的基因表示类似的功能。所以新基因的功能也包含在列表里的基因里。所以严格确定最相近的一个对生物试验非常必要。</p>
<p>你的任务是写一个程序来按以下规则比较两个基因和决定他们的相似程度。例如，给出两个基因串AGTGATG 和 GTTAG，他们有多相似呢？一个测量两个基因相似程度的方法就叫做“校准”。在校准中, 如果必要是可以在基因的适当位置插进空格以令他们的长度相等。例如，一个空格插进了AGTGATG以后就得到AGTGAT-G，三个空格插进了GTTAG就得到–GT—TAG（空格用减号-表示）。现在两个串的长度就相等了。现在排在一齐就成了：</p>
<p>AGTGAT-G</p>
<p>-GT--TAG</p>
<p>在这个校准中，有四个基因是相配的：第二位的G，第三位的 T，第六位的T，和第八位的G。每对排列排列的字母用一下的矩阵分配了不同的分值。</p>
<p> </p>
<p>其中，*表示空格对空格是不允许的。所以以上这个校准的分值是(-3)+5+5+(-2)+(-3)+ 5+(-3)+5=9 。当然，其他校准也是有可能的。一下有另一种排列 (不同数目的空格插进不同的位置)：</p>
<p>AGTGATG</p>
<p>-GTTA-G</p>
<p>这个校准给出了的分值是 (-3)+5+5+(-2)+5+(-1) +5=14。 所以这一个比前一个要好。</p>
<p>两个基因串的最大校准分值就是它们的相似程序。在这个例子中，没有其他的校准有更高的分值了，所以说这两个基因的相似程度是14。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，一个整数T表示测试数据组数(1≤T≤10)。每组测试数据有两行：每行有一个表示基因长度的整数和一个基因序列。每个基因的长度都不超过100。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p align="left">对应T行输入，输出每组测试数据的相似程度，每组一行。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>7 AGTGATG</p>
<p>5 GTTAG</p>
<p>7 AGCTATT</p>
<p>9 AGCTTTAAA</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>14</p>
<p>21</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1≤T≤10</p>
</div>
</div>