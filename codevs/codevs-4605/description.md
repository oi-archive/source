<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>顾名思义.</p><p>给一棵有根树，以及一些询问，每次询问树上的2 个节点A、B，求它</p><p>们的最近公共祖先.</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数N.</p><p>接下来N 个数，第i 个数Fi 表示i 的父亲是Fi. 若Fi = 0,则i 为树</p><p>根.</p><p>接下来一个整数M.</p><p>接下来M 行，每行2 个整数A、B，询问节点(A xor LastAns)、(B</p><p>xor LastAns)的最近公共祖先. 其中LastAns 为上一个询问的答案，</p><p>一开始LastAns = 0.</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对每一个询问输出相应的答案.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10</p><p>0 1 2 3 2 4 2 5 4 9</p><p>10</p><p>3 9</p><p>2 7</p><p>7 8</p><p>1 1</p><p>0 6</p><p>6 11</p><p>6 3</p><p>10 7</p><p>2 15</p><p>7 7</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3<br></p><p>1</p><p>4</p><p>5</p><p>2</p><p>4</p><p>2</p><p>5</p><p>2</p><p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30% n,m≤1000</p><p>100% n,m≤100,000</p><p><br></p>
</div>
</div>