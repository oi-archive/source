<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">给出两个没有完成的数独矩阵，将这两个矩阵填满之后，两个矩阵同一个位置的数相同的话，则填入第三个空的矩阵，然后第二第三个矩阵再填，相同的放入第四个矩阵……以此类推，直到矩阵不再变化。</span></p><p style=""><span style="">如果</span><span style="">每个矩阵有多种填法，则输出</span><span style="">[1,1]最小的,[1,1]相等输出[1,2]最小的……以此类推</span></p><p style=""><span style="">保证每次的第一第二矩阵不相同</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">两个没有完成的数独</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style=";font-family:宋体;font-size:16px">输出最终不再变化的</span><span style=";font-family:宋体;font-weight:bold;font-size:16px">完成</span><span style=";font-family:宋体;font-size:16px">的矩阵</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">6 0 7 3 9 8 2 5 4</span></p><p style=""><span style="">4 2 5 6 7 0 3 9 8</span></p><p style=""><span style="">8 3 9 4 2 5 6 7 0</span></p><p style=""><span style="">0 5 3 7 6 2 4 8 9</span></p><p style=""><span style="">2 8 4 0 5 9 7 3 6</span></p><p style=""><span style="">7 9 6 8 4 3 5 0 2</span></p><p style=""><span style="">3 6 0 2 8 7 9 4 5</span></p><p style=""><span style="">5 7 2 9 0 4 8 6 3</span></p><p style=""><span style="">9 4 8 5 3 6 0 2 7</span></p><p style=""><span style=""> </span></p><p style=""><span style="">5 7 2 4 3 1 0 6 8</span></p><p style=""><span style="">8 0 1 7 5 6 2 4 3</span></p><p style=""><span style="">6 3 4 2 0 8 5 1 7</span></p><p style=""><span style="">3 2 6 5 1 0 8 7 4</span></p><p style=""><span style="">0 1 5 8 4 7 3 2 6</span></p><p style=""><span style="">4 8 7 6 2 3 1 5 0</span></p><p style=""><span style="">1 4 8 0 6 2 7 3 5</span></p><p style=""><span style="">2 5 0 3 7 4 6 8 1</span></p><p style=""><span style="">7 6 3 1 8 5 4 0 2</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">1 2 4 3 5 6 7 8 9</span></p><p style=""><span style="">5 6 7 1 8 9 2 3 4</span></p><p style=""><span style="">8 3 9 2 4 7 5 6 1</span></p><p style=""><span style="">2 1 3 4 6 5 8 9 7</span></p><p style=""><span style="">4 5 8 7 9 2 3 1 6</span></p><p style=""><span style="">7 9 6 8 1 3 4 5 2</span></p><p style=""><span style="">3 4 1 6 2 8 9 7 5</span></p><p style=""><span style="">6 7 5 9 3 4 1 2 8</span></p><p style=""><span style="">9 8 2 5 7 1 6 4 3</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">祝你们好运</span></p><p><span style="">30%的数据0的个数&lt;=25</span></p><p><span style="">60%的数据0的个数&lt;=35</span></p><p><span style="">100%的数据0的个数&lt;=45</span></p><p><br></p>
</div>
</div>