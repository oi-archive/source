<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>fyg 背着他的电脑来到河北省来，就是为了见一眼古老的赵州桥。 <br>终于，他来到了赵州桥，放下了电脑，正准备休息。一阵风吹来，从中闪现出一人影。<br>fyg 只觉天昏地暗，待得再次睁开眼时，发觉自己已经到了一神奇的国度，置身于一巨大的<br>圆盘之上。放眼看去，四周都是奇形怪状的桥，不远处有一老头盘膝而坐。 <br>fyg 还沉浸在惊奇之中，老头（难道就是传说中走过赵州桥的张老头！！）便开口了：凡<br>人，你现在在我的世界中，想要出去就要回答我的问题。fyg 只得点头，老头继续道：你现<br>在要去闯关，我给你 m 种颜色，总共有 n 关（神仙也懂数学，表示压力巨大。。== ）。每一关<br>中有一座桥，在第 i 关中，桥长度有 i 个单位，每个单位长度上有 2 个格子（也就是说这座<br>桥有2i 个格子），现在你要计算出：在这座桥上涂色使得桥上相邻格子的颜色不一样总方案<br>数，然后再乘上（2×i）^m。如在第 1 关，若你手上有 2 种颜色，分别为蓝色和绿色。则总<br>方案数为2×2×2 =8 种，涂色方案数为 2 （如下图，旋转、翻转相同算不同的方案），然后<br>还要再乘2 个2 ，最后你出来之后我会问你所有关中计算出来的数的和。如果你能答对，我<br>就可以让你出去了，否则就无限轮回吧。</p>
<p>fyg 表示这个问题太水了，完全不想算。。。于是，他马上打开电脑上了QQ 找到了喜欢计算的你，求你帮他直接把最终答案算出来，让他回到赵州桥上。</p>
<p>这两个数都有可能很大，fyg 不想为难你，所以你只要告诉他其除以 p 的余数</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>只有一行，其中包含四个正数 n、m、p，分别由一个空格分开。n、m、p 含义和题目描述一致。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行，表示方案数的和除以 p 的余数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 5 50 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>30 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>总共有 2 关。 <br> 第一关的桥长度为 1，总共有 2 个格子，涂色方案数为 20，再乘上 2 ^ 5，第一关中<br>计算出的数为 640。 <br> 第二关的桥长度为 2，总共有 4 个格子，涂色方案数为 260，再乘上 4 ^ 5，第二关中<br>计算出的数为 266240。 <br> 两个数字加起来除以 50 余 30，故输出为 30。</p>
<p>对于其中 25%的数据，满足 n &lt;= 10^6，m &lt;= 200，p &lt;= 10^9； <br> 对于其中 40%的数据，满足 n &lt;= 10^9，m &lt;= 120，p &lt;= 10^9； <br> 对于其中 15%的数据，满足 n &lt;= 10^9，m &lt;= 200，p &lt;= 10^9； <br> 对于最后 20%的数据，满足 n&lt;= 10^9，m &lt;= 3000，p &lt;= 3000；</p>
</div>
</div>