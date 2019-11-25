<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小<span style="font-family: 'Times New Roman';">Q</span><span style="">是一个非常聪明的孩子，除了国际象棋，他还很喜欢玩一个电脑益智游戏——矩阵游戏。矩阵游戏在一个</span>N*N黑白方阵进行（如同国际象棋一般，只是颜色是随意的）。每次可以对该矩阵进行两种操作：</p>
<p> 行交换操作：选择矩阵的任意两行，交换这两行（即交换对应格子的颜色）</p>
<p> 列交换操作：选择矩阵的任意行列，交换这两列（即交换对应格子的颜色）</p>
<p> </p>
<p>游戏的目标，即通过若干次操作，使得方阵的主对角线<span style="font-family: 'Times New Roman';">(</span><span style="">左上角到右下角的连线</span><span style="font-family: 'Times New Roman';">)</span><span style="">上的格子均为黑色。</span></p>
<p>对于某些关卡，小<span style="font-family: 'Times New Roman';">Q</span><span style="">百思不得其解，以致他开始怀疑这些关卡是不是根本就是无解的！！于是小</span><span style="font-family: 'Times New Roman';">Q</span><span style="">决定写一个程序来判断这些关卡是否有解。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个整数T，表示数据的组数。</p>
<p>接下来包含T组数据，每组数据第一行为一个整数N，表示方阵的大小；接下来N行为一个N*N的<span style="font-family: 'Times New Roman';">01</span><span style="">矩阵（</span><span style="font-family: 'Times New Roman';">0</span><span style="">表示白色，</span><span style="font-family: 'Times New Roman';">1</span><span style="">表示黑色）。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出应包含T行。对于每一组数据，如果该关卡有解，输出一行<span style="font-family: 'Times New Roman';">Yes</span><span style="font-family: 宋体;">；否则输出一行</span><span style="font-family: 'Times New Roman';">No</span><span style="font-family: 宋体;">。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>2</p>
<p>0 0</p>
<p>0 1</p>
<p>3</p>
<p>0 0 1</p>
<p>0 1 0</p>
<p>1 0 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>No</p>
<p>Yes</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于<span style="font-family: 'Times New Roman';">20%</span><span style="">的数据，</span>N ≤ 7</p>
<p>对于<span style="font-family: 'Times New Roman';">50%</span><span style="">的数据，</span>N ≤ 50</p>
<p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据，</span>N ≤ 200</p>
</div>
</div>