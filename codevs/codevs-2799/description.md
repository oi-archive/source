<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>大学排名现在已经非常流行。在网上搜索可查到关于中国大学排行的各个方面的消息。</p>
<p>我们知道，在一大学里通常都由许多不同的<span style="font-family: Times New Roman;">“</span><span style="">系</span><span style="font-family: Times New Roman;">”</span><span style="">（专业）组成，比如计算机系（简称</span><span style="font-family: Times New Roman;">CS</span><span style="">）；电子工程系（简称</span><span style="font-family: Times New Roman;">EE</span><span style="">）；外语系（简称</span><span style="font-family: Times New Roman;">FLS</span><span style="">），等等。在一个大学里，其某一专业也许国内排前几，但其他专业却默默无闻。因此，大多数大学排行榜都有不同专业的详细的排名。</span></p>
<p>但是信息量如此巨大的光芒，却掩盖不了一个严重的问题：究竟哪个大学更好？幸运的是，波布博士提出了一个新概念<span style="font-family: Times New Roman;">“</span><span style="">绝对更好</span><span style="font-family: Times New Roman;">”</span><span style="">，</span>使得这个难题能被部分解决。</p>
<p>为了更好地阐述波布博士的新概念，我们举一个例子：</p>
<p>假设现在有三大学：<span style="font-family: Times New Roman;">X</span><span style="">大学、</span><span style="font-family: Times New Roman;">Y</span><span style="">大学、</span><span style="font-family: Times New Roman;">Z</span><span style="">大学。每所大学都有三个专业：</span><span style="font-family: Times New Roman;">CS</span><span style="">，</span><span style="font-family: Times New Roman;">EE</span><span style="">，</span><span style="font-family: Times New Roman;">FLS</span><span style="">。而这三所大学三个专业国际公认的排名如下：</span></p>
<p>CS<span style="">排名：</span><span style="font-family: Times New Roman;">X&gt;Y&gt;Z</span><span style="">（</span><span style="font-family: Times New Roman;">X&gt;Y</span><span style="">表示</span><span style="font-family: Times New Roman;">X</span><span style="">的</span><span style="font-family: Times New Roman;">CS</span><span style="">专业比</span><span style="font-family: Times New Roman;">Y</span><span style="">的好）</span></p>
<p>EE<span style="">排名：</span><span style="font-family: Times New Roman;">X&gt;Z&gt;Y</span></p>
<p>FLS<span style="">排名：</span><span style="font-family: Times New Roman;">Z&gt;X&gt;Y</span></p>
<p>显然，<span style="font-family: Times New Roman;">X</span><span style="">大学的每个专业都比</span><span style="font-family: Times New Roman;">Y</span><span style="">大学好，所以</span><span style="font-family: Times New Roman;">X</span><span style="">大学绝对比</span><span style="font-family: Times New Roman;">Y</span><span style="">大学好。运用这个概念我们就能比较出一些大学的优劣。</span></p>
<p>现在波布博士有一份完整的各个大学不同专业的排名，他想找出这样的<span style="font-family: Times New Roman;">K</span><span style="">个大学（</span><span style="font-family: Times New Roman;">U1</span><span style="">，</span><span style="font-family: Times New Roman;">U2</span><span style="">，</span><span style="font-family: Times New Roman;">U3…,Uk</span><span style="">），</span><span style="font-family: Times New Roman;">Ui</span><span style="">一定比</span><span style="font-family: Times New Roman;">Uj</span><span style="">（</span><span style="font-family: Times New Roman;">i&lt;j</span><span style="">）好。</span></p>
<p>你能告诉波布博士这个<span style="font-family: Times New Roman;">K</span><span style="">的最大值么？</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有两个整数<span style="font-family: Times New Roman;">N</span><span style="">，</span><span style="font-family: Times New Roman;">M</span><span style="">（</span><span style="font-family: Times New Roman;">0&lt;N,M</span>≤100<span style="">），表示有</span><span style="font-family: Times New Roman;">N</span><span style="">所大学和</span><span style="font-family: Times New Roman;">M</span><span style="">项专业。</span></p>
<p>接下来的<span style="font-family: Times New Roman;">M</span><span style="">行中，</span>第i<span style="">（</span><span style="font-family: Times New Roman;">1&lt;=i&lt;=m</span><span style="">）行有</span><span style="font-family: Times New Roman;">N</span><span style="">所大学的编号</span><span style="font-family: Times New Roman;">Uj</span><span style="">（</span><span style="font-family: Times New Roman;">1</span>≤j≤N,1≤Uj≤N<span style="">），代表第</span><span style="font-family: Times New Roman;">i</span><span style="">个专业</span><span style="font-family: Times New Roman;">N</span><span style="">大学的排名（越在前的排名越前）。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件应该一行，该行是<span style="font-family: Times New Roman;">K</span><span style="font-family: 宋体;">值的最大值。不需要多余的空格。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p>
<p>1 2 3</p>
<p>1 3 2</p>
<p>3 1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>0&lt;N,M≤100</p>
</div>
</div>