<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小可可在课余的时候受美术老师的委派从事一项漆绘瓷砖的任务。首先把n(n+1)/2块正六边形瓷砖拼成三角形的形状，右图给出了n=3时拼成的“瓷砖三角形”。然后把每一块瓷砖漆成纯白色或者纯黑色，而且每块瓷砖的正、反两面都必须漆成同样的颜色。 </p>
<p>有一天小可可突发奇想，觉得有必要试试看这些瓷砖究竟能够漆成多少种本质不同的图案。所谓两种图案本质不同就是其中的一种图案无论如何旋转、或者翻转、或者同时旋转和翻转都不能得到另外一种图案。</p>
<p>旋转是将瓷砖三角形整体顺时针旋转120度或240度。</p>
<p>翻转是将瓷砖三角形整体左右翻动180度。</p>
<p><br>一开始，小可可觉得这项实验很有意思，他知道n=2时有两个本质不同的漆绘方案，n=4时也只有四个本质不同的漆绘方案。小可可还把这些漆绘方案画了出来。</p>
<p> 但是后来小可可发现在变大的过程中，漆绘方案的数目增长很快，在n=14的时候，居然有6760803201217259503457555972096种不同的漆绘方案。这果然是一项非常艰巨的实验。因此他决定请你编写程序帮他求解本质不同的漆绘方案数</p>

<img src="/source/codevs/codevs-2926/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9pbWFnZS9wcm9ibGVtLzI5MjYuanBn.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一个正整数n, n≤20</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行正整数，代表问题的解s。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>输入1： 1</p>
<p>输入2： 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>输出1：2</p>
<p>输出2：4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>s不超过200位</p>
</div>
</div>