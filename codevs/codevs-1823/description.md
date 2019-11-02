<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>你的公司接到了一批订单。订单要求你的公司提供n类产品，产品被编号为1-n，其中第i类产品共需要Ci件。公司共有m名员工，员工被编号为1-m，不同的员工能够制造的产品种类有所区别。一件产品必须完整地由一名员工制造，不可以由某名员工制造一部分配件后，再转交给另外一名员工继续进行制造。</p>
<p>我们用一个由<span style="font-family: 'Times New Roman';">0</span><span style="">和</span><span style="font-family: 'Times New Roman';">1</span><span style="">组成的m*n</span>的矩阵A来描述每名员工能够制造哪些产品。矩阵的行和列分别被编号为1-m和1-n，为<span style="font-family: 'Times New Roman';">1</span><span style="">表示员工i</span>能够制造产品j，为<span style="font-family: 'Times New Roman';">0</span><span style="">表示员工i</span>不能制造产品j。</p>
<p>如果公司分配了过多工作给一名员工，这名员工会变得不高兴。我们用愤怒值来描述某名员工的心情状态。愤怒值越高，表示这名员工心情越不爽，愤怒值越低，表示这名员工心情越愉快。员工的愤怒值与他被安排制造的产品数量存在某函数关系，鉴于员工们的承受能力不同，不同员工之间的函数关系也是有所区别的。</p>
<p>对于员工i，他的愤怒值与产品数量之间的函数是一个S<sub>i+1</sub>段的分段函数。当他制造第1-T<sub>i,1</sub>件产品时，每件产品会使他的愤怒值增加W<sub>i,1</sub>，当他制造第T<sub>i,1</sub>+1-T<sub>i,2</sub>件产品时，每件产品会使他的愤怒值增加……为描述方便，设T<sub>i,0</sub>=0，T<sub>i,si+1</sub>=无限大，那么当他制造第T<sub>i,j-1</sub>+1-T<sub>i,j</sub>件产品时，每件产品会使他的愤怒值增加W<sub>i,j</sub>，1≤j≤S<sub>i</sub>+1。</p>
<p>你的任务是制定出一个产品的分配方案，使得订单条件被满足，并且所有员工的愤怒值之和最小。由于我们并不想使用<span style="font-family: 'Times New Roman';">Special Judge</span><span style="">，你只需要输出最小的愤怒值之和就可以了。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个正整数m和n，分别表示员工数量和产品的种类数；</p>
<p>第二行包含n个正整数，第i个正整数为Ci；</p>
<p>以下m行每行n个整数描述矩阵A；</p>
<p>下面m个部分，第i部分描述员工的愤怒值与产品数量的函数关系。每一部分由三行组成：第一行为一个非负整数S<sub>i</sub>，第二行包含个S<sub>i</sub>正整数，其中第j个正整数为T<sub>i,j</sub>，如果S<sub>i</sub>=0那么输入将不会留空行（即这一部分只由两行组成）。第三行包含个正整数S<sub>i+1</sub>，其中第j个正整数为W<sub>i,j</sub>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p16">仅输出一个整数，表示最小的愤怒值之和。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 3</p>
<p>2 2 2</p>
<p>1 1 0</p>
<p>0 0 1</p>
<p>1</p>
<p>2</p>
<p>1 10</p>
<p>1</p>
<p>2</p>
<p>1 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>24</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>存在<span style="font-family: 'Times New Roman';">30%</span><span style="">的数据，m,n≤30</span>；</p>
<p>均匀分布着约<span style="font-family: 'Times New Roman';">30%</span><span style="">的数据，满足S</span><sub><span>i</span></sub><span>=0</span>；</p>
<p>均匀分布着约<span style="font-family: 'Times New Roman';">30%</span><span style="">的数据，满足S</span><sub><span>i</span></sub><span>≤1</span>（不包含上述的数据）；</p>
<p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据，1≤m,n≤250</span>，0≤S<sub>i</sub>≤5，0≤A<sub>i,j</sub>≤1，0&lt;T<sub>i,j</sub>&lt;T<sub>i,j+1</sub>，0&lt;W<sub>i,j</sub>&lt;W<sub>i,j+1</sub>，所有数据不大于10<sup>5</sup>。</p>
</div>
</div>