<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>婷婷是个喜欢矩阵的小朋友,有一天她想用电脑生成一个巨大的n行m列的矩阵(你不用担心她如何存储)。她生成的这个矩阵满足一个神奇的性质：若用F[i][j]来表示矩阵中第i行第j列的元素，则F[i][j]满足下面的递推式:<br> <br> F[1][1]=1<br> F[i,j]=a*F[i][j-1]+b (j!=1)<br> F[i,1]=c*F[i-1][m]+d (i!=1)<br> 递推式中a,b,c,d都是给定的常数。<br> <br> 现在婷婷想知道F[n][m]的值是多少,请你帮助她。由于最终结果可能很大，你只需要输出F[n][m]除以1,000,000,007的余数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件包含一行有六个整数n,m,a,b,c,d。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: 10px;">输出文件中包括一个整数，表示F[n][m]除以1,000,000,007的余数</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 4 1 3 2 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>85</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例1说明】<br> 样例中的矩阵为：<br> 1 4 7 10<br> 26 29 32 35<br> 76 79 82 85<br> <br> 数据范围<br> <img src="/source/codevs/codevs-3046/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0zMDQ2L2h0dHA6Ly9vai5sdW9ndS5vcmc6ODg4OC91c2Vyc2V0L2dldHBpYy5waHA_cGljaWQ9MTk3.php"></p>
</div>
</div>