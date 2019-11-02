<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一块梯形田地上，一群蚯蚓在做收集食物游戏。蚯蚓们把梯形田地上的食物堆积整理如下：</p>
<p>                                                 a(1,1)  a(1,2)…a(1,m)</p>
<p>                                          a(2,1)  a(2,2)  a(2,3)…a(2,m)  a(2,m+1)     </p>
<p>                                     a(3,1)  a (3,2)  a(3,3)…a(3,m+1)  a(3,m+2)</p>
<p>                             ……  </p>
<p>                                   a(n,1)   a(n,2)   a(n,3)…           a(n,m+n-1)     </p>
<p>       它们把食物分成n行，第1行有m堆的食物，每堆的食物量分别是a(1,1),a(1,2),…,a(1,m)；</p>
<p>第2行有m+1堆食物，每堆的食物量分别是a(2,1),a(2,2),…,  a(2,m+1)；以下依次有m+2堆、m+3堆、…m+n-1堆食物。</p>
<p>现在蚯蚓们选择了k条蚯蚓来测试它们的合作能力（1≤ k ≤m）。测试法如下：第1条蚯蚓从第1行选择一堆食物，然后往左下或右下爬，并收集1堆食物，例如从a（1,2）只能爬向a(2,2) 或a(2,3)，而不能爬向其它地方。接下来再爬向下一行收集一堆食物，直到第n行收集一堆食物。第1条蚯蚓所收集到的食物量是它在每一行所收集的食物量之和；第2条蚯蚓也从第1行爬到第n行，每行收集一堆食物，爬的方法与第1条蚯蚓相类似，但不能碰到第1条蚯蚓所爬的轨迹；一般地，第i 条蚯蚓从第1行爬到第 n行，每行收集一堆食物，爬的方法与第1条蚯蚓类似，但不能碰到前 I-1 条蚯蚓所爬的轨迹。这k条蚯蚓应该如何合作，才能使它们所收集到的食物总量最多？收集到的食物总量可代表这k条蚯蚓的合作水平。</p>
<ul>
<li>Ø编程任务：</li>
</ul>
<p>       给定上述梯形m、n和k的值（1≤k≤m≤30;1≤n≤30）以及梯形中每堆食物的量（小于10的非整数），编程计算这k条蚯蚓所能收集到的食物的最多总量。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>       输入数据由文件名为INPUT1.*的文本文件提供，共有n+1行。每行的两个数据之间用一个空格隔开。</p>
<p>        ●第1行是n、m和k的值。</p>
<ul>
<li>接下来的n行依次是梯形的每一行的食物量a(i,1)，a(i,2)，…，a(i,m+i-1)，i=1,2,…,n。</li>
</ul>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>程序运行结束时，在屏幕上输出k蚯蚓条所能收集到的食物的最多总量。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3    2   2    </p>
<p>1   2</p>
<p>5   0   2</p>
<p>1   10  0  6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>26</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>