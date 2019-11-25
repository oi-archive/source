<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>为了更好地解决这个问题，我们来看几个例子。</p>
<p>    首先我们定义N！=1*2*3*……*N。</p>
<p>    再定义C（M，N）为从M个元素中无序取出N个的方法，P（M，N）为从M个元素中有序取出N个的方法。</p>
<p>    这样的定义是什么意思呢?比如说从1,2,3,4共4个元素中中取出3个,有(1,2,3);(1,3,4);(2,3,4);(1,2,4)这样共4种,而这里是不考虑顺序的,所以C(4,3)=4,而如果对每一种方案考虑它的排列顺序的话,那结果将会不同,因为(1,2,3);(1,3,2);(2,1,3);(2,3,1);(3,1,2);(3,2,1)将被视为不同的方案,所以P(4,3)=6*4=24.</p>
<p>    下面给出它们的计算公式:</p>
<p>    P(M,N)=M!/(M-N)! C(M,N)=M!/((M-N)!*N!)</p>
<p>    再来解决这个问题,你会觉得更轻松!</p>
<p>    圆周上有N（N&lt;=100）个点，用线段将它们彼此相连。这些线段中任意三条在圆内都没有公共交点，问这些线段能构成多少个顶点在圆内的三角形？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入：一行，为数值N。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出：一行，为所求的答案。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p> 样例输入：6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>    样例输出：1 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>  注意：只要你数据处理得当，结果与中间数值的范围一定在longint以内，请不要使用int64，因为这可能会引起系统误判！</p>
</div>
</div>