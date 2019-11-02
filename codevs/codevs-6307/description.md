<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>现在，在世界上有许多知名的OJ，它们各有各的特色，也各有各的优点。</p><p>ZZH是一名蒟蒻，他刚开始学习OI，最近他想选一个适合他的OJ，请你帮他进行选择。<br></p><p><img src="/source/codevs/codevs-6307/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy02MzA3L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvZWVlZV8yMDE3MDcxMzE3MTY1M185NjUucG5n.png" title="">←我是Z**</p><p>已知在世界上一共有N个OJ，每个OJ有其对应的各个参数，分别是知名度(满分100）、使用人数、题目平均难度、优点总数及缺点总数。已知每个OJ的分数为知名度+使用人数/1000（四舍五入）+优点数*5-缺点数*10，分数越高，代表这个OJ越好，若一个OJ的分数≥K（给定），则代表这个OJ质量适合ZZH。</p><p>当然，OJ不是说分数越高就越适合ZZH，这还要看他的平均题目难度。已知ZZH的水平为T，而每个OJ的平均题目难度为Si，如果|T-Si|≤5，则这个OJ难度适合ZZH。</p><p>只有当质量、难度都适合ZZH时，ZZH才会选用这个OJ。现给出N、K、T及每个OJ的信息，求最适合ZZH的OJ，并输出编号。</p><p>※若有多个OJ适合ZZH，则先比较|T-Si|（难度、水平差），越小则越适合。若T-Si相等，再比较质量分数，越高越适合。若质量分数亦相等，则输出序号靠前的OJ。</p><p>※若没有OJ适合ZZH，则输出“NO ANSWER”（注意大小写）</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>共N+1行。</p><p>第1行：N、K、T.（OJ数、ZZH要求的质量分数、ZZH的水平）</p><p>第2至N+1行：</p><p>每行5个数，分别为该OJ的知名度、使用人数、题目平均难度、优点总数和缺点总数，第i行的OJ序号为i-1.</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行一个数，最适合ZZH的OJ。若没有OJ适合ZZH，则输出“NO ANSWER”</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 60 22</p><p>50 5000 22 1 1</p><p>100 20000 26 1 1</p><p>20 1000 22 2 1</p><p>80 50000 30 10 3</p><p><br></p>

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
<p>【样例解释】</p><p>OJ1：题目难度符合（差为0），分数不足（50）。×</p><p>OJ2：题目难度符合（差为4），分数足够（115）。√</p><p>OJ3：题目难度符合（差为0），分数不足（21）。×</p><p>OJ4：题目难度不符（差为8），分数足够（150）。×</p><p><br></p><p>【数据范围】</p><p>对于30%的数据，N≤30，且不存在多个OJ符合的情况。</p><p>对于100%的数据，N≤500，K，T≤1000000。</p><p>P.S.数据其实很水很水，真的很水</p><p><br></p><p>SQRT题目系列 III </p><p>By Sqrt_-1</p><p><br></p><p>P.S.本来这道题是在6281的，因为审核后仍无法显示到题库上（但在分类筛选里可以看到），所以重新提交了一次，如果管理员看到，可以把上一次提交的题目删掉，谢谢</p><p><br></p>
</div>
</div>