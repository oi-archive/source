<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>大学排名现在已经非常流行。在网上搜索可查到关于中国大学排行的各个方面的消息。</p>
<p>我们知道，在一大学里通常都由许多不同的“系”（专业）组成，比如计算机系（简称CS）；电子工程系（简称EE）；外语系（简称FLS），等等。在一个大学里，其某一专业也许国内排前几，但其他专业却默默无闻。因此，大多数大学排行榜都有不同专业的详细的排名。</p>
<p>虽然信息量如此巨大，但是却掩盖不了一个严重的问题：究竟哪个大学更好？幸运的是，波布博士提出了一个新概念“绝对更好”，使得这个难题能被部分解决。</p>
<p>为了更好地阐述波布博士的新概念，我们举一个例子：</p>
<p>假设现在有三大学：X大学、Y大学、Z大学。每所大学都有三个专业：CS，EE，FLS。而这三所大学三个专业国际公认的排名如下：</p>
<p>CS排名：X&gt;Y&gt;Z（X&gt;Y表示X的CS专业比Y的好）</p>
<p>EE排名：X&gt;Z&gt;Y</p>
<p>FLS排名：Z&gt;X&gt;Y</p>
<p>显然，X大学的每个专业都比Y大学好，所以X大学绝对比Y大学好。运用这个概念我们就能比较出一些大学的优劣。</p>
<p>现在波布博士有一份完整的各个大学不同专业的排名，他想提出K问题，每个问题是比较两个大学Ui和Uj，看Ui是否一定比Uj好。</p>
<p>你能回答波布博士这K个问题么？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有三个整数N，M，K（0&lt;N,M,K≤100），表示有N所大学和M项专业。</p>
<p>接下来的M行中，第i（1≤i≤m）行有N所大学的编号Uj（1≤j≤N,1≤Uj≤N），代表第i个专业N大学的排名（越在前的大学排名越前）。</p>
<p>接下来的K行中，第i（1≤i≤K）行有两所大学的编号Ui和Uj（1≤Ui&lt;Uj≤N），即要比较大学Ui是否一定比大学Uj好。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件有K行，第i行即对第i个问题的回答，如果大学Ui一定比Uj好，输出&ldquo;Yes&rdquo;，否则输出&ldquo;No&rdquo; 。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3 2</p>
<p>1 2 3</p>
<p>1 3 2</p>
<p>3 1 2</p>
<p>1 2</p>
<p>2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Yes</p>
<p>No</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>0&lt;N,M,K≤100</p>
</div>
</div>