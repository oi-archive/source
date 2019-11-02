<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>CZ市为了欢迎全国各地的同学，特地举办了一场盛大的美食节。作为一个喜欢尝鲜的美食客，小M自然不愿意错过这场盛宴。他很快就尝遍了美食节所有的美食。然而，尝鲜的欲望是难以满足的。尽管所有的菜品都很可口，厨师做菜的速度也很快，小M仍然觉得自己桌上没有已经摆在别人餐桌上的美食是一件无法忍受的事情。于是小M开始研究起了做菜顺序的问题，即安排一个做菜的顺序使得同学们的等待时间最短。小M发现，美食节共有n种不同的菜品。每次点餐，每个同学可以选择其中的一个菜品。总共有m个厨师来制作这些菜品。当所有的同学点餐结束后，菜品的制作任务就会分配给每个厨师。然后每个厨师就会同时开始做菜。厨师们会按照要求的顺序进行制作，并且每次只能制作一人份。此外，小M还发现了另一件有意思的事情: 虽然这m个厨师都会制作全部的n种菜品，但对于同一菜品，不同厨师的制作时间未必相同。他将菜品用1, 2, ..., n依次编号，厨师用1, 2, ..., m依次编号，将第j个厨师制作第i种菜品的时间记为 ti,j 。小M认为：每个同学的等待时间为所有厨师开始做菜起，到自己那份菜品完成为止的时间总长度。换句话说，如果一个同学点的菜是某个厨师做的第k道菜，则他的等待时间就是这个厨师制作前k道菜的时间之和。而总等待时间为所有同学的等待时间之和。现在，小M找到了所有同学的点菜信息: 有 pi 个同学点了第i种菜品（i=1, 2, ..., n）。他想知道的是最小的总等待时间是多少。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入文件的第1行包含两个正整数n和m，表示菜品的种数和厨师的数量。 第2行包含n个正整数，其中第i个数为pi，表示点第i种菜品的人数。 接下来有n行，每行包含m个非负整数，这n行中的第i行的第j个数为ti,j，表示第j个厨师制作第i种菜品所需的时间。 输入文件中每行相邻的两个数之间均由一个空格隔开，行末均没有多余空格。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>输出仅一行包含一个整数，为总等待时间的最小值。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>3 2 </span><br><span>3 1 1 </span><br><span>5 7 </span><br><span>3 6 </span><br><span>8 9</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>47</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>【样例说明】</span><br><span>厨师1先制作1份菜品2，再制作2份菜品1。点这3道菜的3个同学的等待时间分别为3，3+5=8，3+5+5=13。</span><br><span>厨师2先制作1份菜品1，再制作1份菜品3。点这2道菜的2个同学的等待时间分别为7，7+9=16。</span><br><span>总等待时间为3+8+13+7+16=47。</span><br><span>虽然菜品1和菜品3由厨师1制作更快，如果这些菜品都由厨师1制作，总等待时间反而更长。如果按上述的做法，将1份菜品1和1份菜品3调整到厨师2制作，这样厨师2不会闲着，总等待时间更短。</span><br><span>可以证明，没有更优的点餐方案。</span><br><br><br><span>【数据规模及约定】</span><br><span>对于100%的数据，n &lt;= 40, m &lt;= 100, p &lt;= 800, ti,j &lt;= 1000（其中p = ∑pi，即点菜同学的总人数）。</span><br><span>每组数据的n、m和p值如下：</span><br><span>测试点编号 n         m            p </span><br><span>1              n = 5   m = 5     p = 10 </span><br><span>2              n = 40 m = 1     p = 400 </span><br><span>3              n = 40 m = 2     p = 300 </span><br><span>4              n = 40 m = 40   p = 40 </span><br><span>5              n = 5   m = 40   p = 100 </span><br><span>6              n = 10 m = 50   p = 200 </span><br><span>7              n = 20 m = 60   p = 400 </span><br><span>8              n = 40 m = 80   p = 600 </span><br><span>9              n = 40 m = 100 p = 800 </span><br><span>10            n = 40 m = 100 p = 800 </span></p>
</div>
</div>