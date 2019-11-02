<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一个偶然的机会，yh得到了一棵神奇的苹果树。</p>
<p>这棵苹果树能变成各式各样，但是必须满足如下条件：</p>
<p>1.该苹果树为一棵二叉树，树一共有d层，n个节点，每个节点均有一个苹果，苹果的重量为1,2,4，…,2^(n-1)中的一个，且没有相同重量的果子。 </p>
<p>2.对于每个非叶子节点，它的右节点及其子节点的总重量要大于它的左节点及其子节点的总重量（但可以没有右节点）。</p>
<p>yh想知道，他的苹果树究竟能变成多少种？由于数量非常大，你只需告诉他结果mod 109+7 即可。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一行，2个整数，n，d，分别表示树的节点数和层数（d≤n）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出一行，一个整数，表示苹果树能变成多少种，答案取模10^9+7。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入1】</p>
<p>2 2</p>
<p> </p>
<p>【样例输入2】</p>
<p>4 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">【样例输出1】</span></p>
<p>4</p>
<p> </p>
<p>【样例输出2】</p>
<p>72</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%数据，n,d≤10</p>
<p>对于100%数据，n,d≤200</p>
</div>
</div>