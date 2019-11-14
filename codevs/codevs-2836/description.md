<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>X<span style="">和他的好友小</span><span style="font-family: 'Times New Roman';">Y</span><span style="">约好了要去穿越丛林，不过好斗的小</span><span style="font-family: 'Times New Roman';">Y</span><span style="">提出要兵分两路，比一比谁走的最快。他们选定了一块</span><span style="font-family: 'Times New Roman';">n*n</span><span style="">的丛林，取左上角为</span><span style="font-family: 'Times New Roman';">(1,1)</span><span style="">，右下角为</span><span style="font-family: 'Times New Roman';">(n,n)</span><span style="">，在每个</span><span style="font-family: 'Times New Roman';">1*1</span><span style="">的区域内都有一个丛林系数</span><span style="font-family: 'Times New Roman';">K</span>ij，丛林系数越高也就越难走。他们约定好，只能往坐标变大的方向走【从(x,y)到(x+1,y)或者(x,y+1)】，走过2n-1个区域到达(n,n)。在丛林中，环境难免不同，因此为了公平起见，小<span style="font-family: 'Times New Roman';">X</span><span style="">定义了一个公平值</span><span style="font-family: 'Times New Roman';">D,</span><span style="">这个公平值等于俩人所走过的区域的丛林系数一一对应相减的差的绝对值之和.</span></p>
<p><span>小<span style="font-family: 'Times New Roman';">X</span><span style="">找到了你，他想让你编程帮他计算公平值的最大值。</span></span></p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，一个正整数<span style="font-family: 'Times New Roman';">n</span></p>
<p>接下来的<span style="font-family: 'Times New Roman';">n</span><span style="">行，每行</span><span style="font-family: 'Times New Roman';">n</span><span style="">个数，表示丛林中每个区域的丛林系数</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一个整数<span style="font-family: 'Times New Roman';">D</span>max，即公平值的最大值</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>1 2 3 4</p>
<p>1 5 3 2</p>
<p>8 1 3 4</p>
<p>3 2 1 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>13</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>对于<span style="font-family: 'Times New Roman';">20%</span><span style="">的数据，保证</span><span style="font-family: 'Times New Roman';">0</span><span style="">＜</span>n≤20</p>
<p>对于<span style="font-family: 'Times New Roman';">50%</span><span style="">的数据，保证</span><span style="font-family: 'Times New Roman';">0</span><span style="">＜</span>n≤50</p>
<p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据，保证</span><span style="font-family: 'Times New Roman';">0</span><span style="">＜</span>n≤100且对于所有的i<span style="">，</span><span style="font-family: 'Times New Roman';">j</span><span style="">保证</span><span style="font-family: 'Times New Roman';">|</span>Kij|<span style="">≤</span><span style="font-family: 'Times New Roman';">300</span></p>
</div>
</div>
</div>