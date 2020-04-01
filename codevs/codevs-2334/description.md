<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小 Z 近日热衷于研究矩阵。他首先写下一个 N*M 的矩阵，在每个格子里填入一个小于 P 的非负整数，然后对其中的每个 2*2 的子矩阵，算出其中各数之和。例如 N=3，M=3，P=3，小 Z<br>写下的矩阵如下：</p>
<p>      0 1 2</p>
<p>A = 1 2 0</p>
<p>      2 0 1</p>
<p>其中共有4个2*2 的子矩阵，容易算出其中各数之和，表示如下：</p>
<p>      0 0 0</p>
<p>S = 0 4 5</p>
<p>      0 5 3</p>
<p>第一行和第一列的 0 是为了格式美观而添加进去的。现在小 Z 想试一试能不能根据这些和推算出原矩阵。因为小 Z 的数学没学好，所以这个任务就交给你了。当然，小 Z 早就发现：解很可能不唯一，例如对下面的矩阵B算出的其中各数之和与矩阵 A相同。</p>
<p>      0 2 1</p>
<p>B = 0 2 0</p>
<p>      2 1 0<br> <br>因此在有多个矩阵满足要求的情况下请你输出按字典序最小的那一个矩阵。 字典序的定义如下：对两个矩阵 X 和 Y，找到 X 和 Y 中的数不同的位置中行数最小的那个格子，若有多个这样的格子则取列数最小的那个格子，该格子中的数较小的矩阵字典序也较小。 例如上述矩阵A和 B，第一个不同的格子是第一行第二列的那个格子，而 A[1][2]&lt;B[1][2]，故矩阵A的字典序比矩阵B小。 <br>另外，小Z的数学尚未差到连加法都做错的地步，因此保证输入数据都是有解的。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行是用空格隔开的三个正整数N，M，P，分别表示矩阵的行数、列数以及输出矩阵元素的上界（即要求输出矩阵元素小于P）。接下来有N行，每行是用空格隔开的M个非负整数， 其中第i+1行第j个数表示以格子(i,j)为右下角的2*2子矩阵中各数之和。输入的数据保证第2行及除第1行外的各行的第1个数均为0，且第2行后各行中的数均不超过4(P-1)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含N行，每行是用空格隔开的 M个整数（行末不允许多余的空格） ，<br />第i行输出中的数就是你求出的矩阵的第i 行中的数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3 3 <br>0 0 0 <br>0 4 5 <br>0 5 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">0 0 2 </span></p>
<p>2 2 1 <br>1 0 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>输入的数据保证30%的数据满足N,M≤10。另外30%的数据满足P=2。100%的数据满足1&lt;N,M≤200，1&lt;P≤10。</p>
</div>
</div>