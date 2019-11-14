<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">怪盗基德发布了将在圣诞夜的今晚偷取东风百货前圣诞树上的宝石——巨人之星的犯罪预告。但是，这实际上是巨人之星的主人财前放出的假预告。财前蓄意炒热话题以便增加营业额，并命令职员冒充基德盗取宝石。晚上，对假预告毫不知情的快斗前往青子的家参加聚会。然而，临近预告时间的时候，快斗惊讶地得知了假预告的事。不过为时已晚，假的怪盗基德已经在东风百货前现身……</span></p><p><span style="">但怪盗基德成功地打败了<span style="">假的怪盗基德</span>，急忙地赶回家，帮青子装饰房间。基德准备给青子一个惊喜，所以请你帮忙。</span></p><p><span style="">基德</span><span style="">手头上有n朵大小相同的花，第i朵花的重量为w</span><sub style="">i</sub><span style="">。现在打算用一根绳将这n朵花按顺序穿起来，挂在天花板上。绳子被m个点固定，也就是绳子的一头被固定在1号点，另外一头固定在m号点，中间部分需要固定在剩余的点。当然，装饰还有一些规则要注意：</span></p><p><span style="">1、</span><span style="">每一段需要包含非0的偶数个花朵。正因如此，我们可以将每一段划分为两个半段。</span></p><p><span style="">2、为了减少撞到花环的可能，花环不能挂的太低：也就是说，每个半段不能超过d朵花。</span></p><p><span style="">3、</span><span style="font-family: 'Times New Roman';"> </span><span style="">最后，你需要让所有半段的重量的最大值最小。</span></p><p><span style=""></span><img src="/source/codevs/codevs-5158/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy01MTU4L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvMzc5ZjgzOTk2NDUwNzA4Ml8yMDE2MDcxNzE2MDUyNF80MjMuanBn.jpg" title=""></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入文件第一行包含三个正整数n，m和d。</span></p><p><span style="">接下来一行包含n个正整数w</span><sub style="">1</sub><span style="">，w</span><sub style="">2</sub><span style="">，…，w</span><sub style="">n</sub><span style="">，代表对应花的重量。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size:13px;font-family:宋体">输出一行一个整数，代表最小的所有半段重量的最大值。如果没有方案满足条件，那么你只要输出“BAD”（不包括引号）。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">4 3 10</span></p><p><span style="">10 10 20 20</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">20</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">1≤n≤15000,2≤m≤10000，1≤d≤2000，且n*d≤5000000</span></p><p><span style=""><span style="">1≤w</span><sub style="">i</sub><span style="">≤10000</span></span></p><p>提示什么的去问基德吧。。。。。。<br></p>
</div>
</div>