<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　上帝手中有着N 种被称作“世界元素”的东西，现在他要把它们中的一部分投放到一个新的空间中去以建造世界。每种世界元素都可以限制另外一种世界元素，所以说上帝希望所有被投放的世界元素都有至少一个没有被投放的世界元素能够限制它，这样上帝就可以保持对世界的控制。由于那个著名的有关于上帝能不能制造一块连自己都不能举起的大石头的二律背反命题，我们知道上帝不是万能的，而且不但不是万能的，他甚至有事情需要找你帮忙——上帝希望知道他最多可以投放多少种世界元素，但是他只会O(2<sup>N</sup>) 级别的算法。虽然上帝拥有无限多的时间，但是他也是个急性子。你需要帮助上帝解决这个问题。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　第一行是一个整数N，表示世界元素的数目。<br>　　第二行有 N 个整数A<sub>1</sub>, A<sub>2</sub>, …, A<sub>N</sub>。A<sub>i</sub> 表示第i 个世界元素能够限制的世界元素的编号。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　一个整数，表示最多可以投放的世界元素的数目。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6<br>2 3 1 3 6 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>　　选择2、3、5 三个世界元素即可。分别有1、4、6 来限制它们。</p>
<p>　　对于 30% 的数据，N≤10。<br>　　对于 100% 的数据，N≤10<sup>6</sup>，1≤A<sub>i</sub>≤N，不保证A<sub>i</sub>≠i。</p>
<p> </p>
<p><span>来源：Nescafe VIII</span></p>
</div>
</div>