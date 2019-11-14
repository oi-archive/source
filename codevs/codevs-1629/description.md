<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一个由01组成的n*n格迷宫，若你位于一格0上，那么你可以移动到相邻4格中的某一格1上，同样若你位于一格1上，那么你可以移动到相邻4格中的某一格0上。那么对于给定的迷宫，询问从某一格开始能移动到多少格。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第1行为两个正整数n，m。</p>
<p>下面n行，每行n个字符，字符只可能是0或者1，字符之间没有空格。</p>
<p>接下来m行，每行2个用空格分隔的正整数i,j，对应了迷宫中第i行第j列的一个0，询问从这一格开始能移动到多少格。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出包括m行，对于每个询问输出答案。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 2</p>
<p>01</p>
<p>10</p>
<p>1 1</p>
<p>2 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】</p>
<p>所有格子互相可达。</p>
<p> </p>
<p>【数据规模】</p>
<p>对于20%的数据，n≤10； </p>
<p>对于40%的数据，n≤50；</p>
<p>对于50%的数据，m≤5；</p>
<p>对于60%的数据，n≤100，m≤100；</p>
<p>对于100%的数据，n≤1000，m≤1000000。</p>
</div>
</div>