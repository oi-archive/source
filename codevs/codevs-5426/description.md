<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Xz有一个切割机。Xz有一个m行n列的矩阵，他想把矩阵分成若干个1*x或x*1的矩阵。切割一个矩阵的方法如下：</p><p><br></p><p>1、如果这个矩阵是1*x或x*1的，那么<span style="">不用</span>切割了。</p><p><br></p><p>2、你可以<span style="">横着或竖着</span>切割这个矩阵。切割的矩阵将变成两个矩阵。这时，你可以获得一些钱——在这两个矩阵选一个矩阵，然后将这个矩阵的<span style="">各元素</span>相加，就是你得到的钱。</p><p><br></p><p>3、继续切割那两个矩阵，直到矩阵变成1*x或x*1的矩阵为止。</p><p><br></p><p>显然，有多种切割方法。但是，Xz想得到更多的钱（废话）。那么，Xz<span style="">最多</span>能得到多少钱呢？他想编一个程序，在 1s 内算出它最多能得到的钱数，这个任务就交给你了。</p><p><br></p><p>Xz的电脑不好，只有1MB内存。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是m,n.</p><p>接下来m行，每行n个整数，矩阵的各个元素。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个数，Xz最多能得到的钱。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p><p>3 4 5</p><p>5 2 9</p><p>6 7 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>64</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%数据 m,n&lt;=2</p><p>对于50%数据 m,n&lt;=5</p><p>对于100%数据 m,n&lt;=10</p><p>所有数据随机生成</p><p><br></p><p><span style="">样例解释：</span></p><p><span style="">先切下3,4,5，获得（5+2+9+6+7+2）元</span></p><p><span style="">3,4,5不用切了</span></p><p><span style="">5 2 9</span></p><p><span style="">6 7 2</span></p><p><span style="">切下5,2,6,7，获得（5+2+6+7）元</span></p><p><span style="">5,2,6,7切下6 7获得（6+7）元</span></p><p><span style="">共64元</span></p>
</div>
</div>