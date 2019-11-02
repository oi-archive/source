<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一条街的一边有几座房子。因为环保原因居民想要在路边种些树。路边的地区被分割成块，并被编号为<span style="font-family: 'Times New Roman';">1</span><span style="">…</span><span style="font-family: 'Times New Roman';">n</span><span style="">。每个块的大小为一个单位尺寸并最多可种一裸树。每个居民想在门前种些树并指定了三个号码</span><span style="font-family: 'Times New Roman';">b</span><span style="">，</span><span style="font-family: 'Times New Roman';">e</span><span style="">，</span><span style="font-family: 'Times New Roman';">t</span><span style="">。这三个数表示该居民想在</span><span style="font-family: 'Times New Roman';">b</span><span style="">和</span><span style="font-family: 'Times New Roman';">e</span><span style="">之间最少种</span><span style="font-family: 'Times New Roman';">t</span><span style="">棵树。当然，</span><span style="font-family: 'Times New Roman';">b</span><span style="">≤</span><span style="font-family: 'Times New Roman';">e</span><span style="">，居民必须保证在指定地区不能种多于地区被分割成块数的树，即要求</span>T≤ <span style="font-family: 'Times New Roman';">e-b+1</span><span style="">。允许居民想种树的各自区域可以交叉。出于资金短缺的原因，环保部门请你求出能够满足所有居民的要求，需要种树的最少数量。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为<span style="font-family: 'Times New Roman';">n</span><span style="">，表示区域的个数；</span></p>
<p>    第二行为<span style="font-family: 'Times New Roman';">h</span><span style="">，表示房子的数目；</span></p>
<p>    下面<span style="font-family: 'Times New Roman';">h</span><span style="">行描述居民的需要：</span><span style="font-family: 'Times New Roman';">bet</span><span style="">（</span><span style="font-family: 'Times New Roman';">0&lt;b</span><span style="">≤</span><span style="font-family: 'Times New Roman';">30000,r </span><span style="">≤</span><span style="font-family: 'Times New Roman';">e-b+ 1</span><span style="">）分别用一个空格分开。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">&nbsp;输出为满足所有要求的最少树的数量。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>        9</p>
<p>        4</p>
<p>        1 4 2</p>
<p>        4 6 2</p>
<p>        8 9 2</p>
<p>        3 5 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p> 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据规模】</p>
<p>    30<span style="">％的数据满足</span><span style="font-family: 'Times New Roman';">0</span><span style="">＜</span><span style="font-family: 'Times New Roman';">n </span><span style="">≤</span><span style="font-family: 'Times New Roman';">1000</span><span style="">，</span><span style="font-family: 'Times New Roman';">0</span><span style="">＜</span><span style="font-family: 'Times New Roman';">h </span><span style="">≤ </span><span style="font-family: 'Times New Roman';">500</span><span style="">； </span><span style="font-family: 'Times New Roman';">100%</span><span style="">的数据满足</span><span style="font-family: 'Times New Roman';">n </span><span style="">≤</span><span style="font-family: 'Times New Roman';">30000</span><span style="">，</span><span style="font-family: 'Times New Roman';">h </span><span style="">≤</span><span style="font-family: 'Times New Roman';">5000</span><span style="">。</span></p>
</div>
</div>