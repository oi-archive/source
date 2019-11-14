<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">小T 准备在家里摆放几幅画，为此他买来了N 幅画和N 个画框。为了体现他的品味，小</p><p style="">T 希望能合理地搭配画与画框，使得其显得既不过于平庸也不太违和。对于第i 幅画与第j 个</p><p style="">画框的配对，小T 都给出了这个配对的平凡度Ai,j 与违和度Bi,j。整个搭配方案的总体不和谐</p><p style="">度为每对画与画框平凡度之和与每对画与画框违和度之和的乘积。具体来说，设搭配方案中第</p><p style="">i 幅画与第Pi 个画框配对，则总体不和谐度为</p><p style=""><br></p><p style=""><img src="/source/codevs/codevs-3669/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0zNjY5L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvYmxvYl8yMDE1MDQxNzE3NTU0OV8zMTIucG5n.png" title=""></p><p style="">小T 希望知道通过搭配能得到的最小的总体不和谐度是多少。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件名为frame.in。</p><p>输入文件第1行是一个正整数T，表示数据组数。</p><p>接下来是T组数据。</p><p>对于每组数据：</p><p>第1行是一个正整数N，表示有N对画和画框；</p><p>第2到第N+1行，每行有N个非负整数，第i+1行第j个数表示Ai,j；</p><p>第N+2到第2N+1行，每行有N个非负整数，第i+N+1行第j个数表示Bi,j。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件仅包含T 行，每行一个整数，表示最小的总体不和谐度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1</p><p>3</p><p>4 3 2</p><p>2 3 4</p><p>3 2 1</p><p>2 3 2</p><p>2 2 4</p><p>1 1 3</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>30</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于10%的数据满足N≤10,T≤2；</p><p>对于30%的数据满足Ai,j=Bi,j；</p><p>对于70%的数据满足N≤40；</p><p>对于100%的数据满足N≤70,T≤3,Ai,j≤200,Bi,j≤200。</p><p><br></p>
</div>
</div>