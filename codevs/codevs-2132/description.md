<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>幸福幼儿园 B29 班的粟粟是一个聪明机灵、乖巧可爱的小朋友，她的爱好<br>是画画和读书，尤其喜欢 Thomas H. Cormen 的文章。粟粟家中有一个 R行C 列<br>的巨型书架，书架的每一个位置都摆有一本书，上数第i 行、左数第 j 列摆放的<br>书有Pi,j页厚。 <br>粟粟每天除了读书之外，还有一件必不可少的工作就是摘苹果，她每天必须<br>摘取一个指定的苹果。粟粟家果树上的苹果有的高、有的低，但无论如何凭粟粟<br>自己的个头都难以摘到。不过她发现， 如果在脚下放上几本书，就可以够着苹果；<br>她同时注意到，对于第 i 天指定的那个苹果，只要她脚下放置书的总页数之和不<br>低于Hi，就一定能够摘到。 <br>由于书架内的书过多，父母担心粟粟一天内就把所有书看完而耽误了上幼儿<br>园，于是每天只允许粟粟在一个特定区域内拿书。这个区域是一个矩形，第 i 天<br>给定区域的左上角是上数第 x1i行的左数第 y1i本书，右下角是上数第 x2i行的左<br>数第y2i本书。换句话说，粟粟在这一天，只能在这﹙x2i－x1i＋1﹚×﹙y2i－y1i<br>＋1﹚本书中挑选若干本垫在脚下，摘取苹果。 <br>粟粟每次取书时都能及时放回原位，并且她的书架不会再撤下书目或换上新<br>书，摘苹果的任务会一直持续 M天。给出每本书籍的页数和每天的区域限制及<br>采摘要求，请你告诉粟粟，她每天至少拿取多少本书，就可以摘到当天指定的苹<br>果。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是三个正整数R, C, M。 <br>接下来是一个 R行C 列的矩阵，从上到下、从左向右依次给出了每本书的<br>页数Pi,j。 <br>接下来 M行，第 i 行给出正整数x1i, y1i, x2i, y2i, Hi，表示第i 天的指定区域<br>是﹙x1i, y1i﹚与﹙x2i, y2i﹚间的矩形，总页数之和要求不低于 Hi。 <br>保证 1≤x1i≤x2i≤R，1≤y1i≤y2i≤C。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>有M行，第i 行回答粟粟在第 i 天时为摘到苹果至少需要<br />拿取多少本书。如果即使取走所有书都无法摘到苹果，则在该行输出&ldquo;Poor QLW&rdquo;<br />（不含引号）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 10 7 <br>14 15 9 26 53 58 9 7 9 32 <br>1 2 1 9 170 <br>1 2 1 9 171 <br>1 5 1 7 115 <br>1 1 1 10 228 <br>1 4 1 4 45704571 <br>1 1 1 1 1 <br>1 7 1 8 16</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6 <br>7 <br>3 <br>10 <br>Poor QLW <br>1 <br>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 10%的数据，满足 R, C≤10； <br>对于 20%的数据，满足 R, C≤40； <br>对于 50%的数据，满足 R, C≤200，M≤200,000； <br>另有 50%的数据，满足 R＝1，C≤500,000，M≤20,000； <br>对于 100%的数据，满足 1≤Pi,j≤1,000，1≤Hi≤2,000,000,000。</p>
</div>
</div>