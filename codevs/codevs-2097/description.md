<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>假设我们将序列中第<em>i</em>件物品的参数定义为<em>A<sub>i</sub></em>，那么排序就是指将<em>A</em><sub>1</sub>,…,<em>A</em><sub>n</sub>从小到大排序。若<em>i</em>&lt;<em>j</em>且<em>A</em><sub>i</sub>&gt;<em>A</em><sub>j</sub>，则&lt;<em>i</em>,<em>j</em>&gt;就为一个“逆序对”。SORT公司是一个专门为用户提供排序服务的公司，他们的收费标准就是被要求排序物品的“逆序对”的个数，简称“逆序数”。</p>
<p>Grant是这家公司的排序员，他想知道对于n个参数都不同的物品组成的序列集合中，逆序对数为t的物品有多少个，并试给出其中一个最小的物品序列。所谓最小，即若有两个物品序列(A<sub>1</sub>,A<sub>2</sub>,…,A<sub>n</sub>)，(B<sub>1</sub>,B<sub>2</sub>,…,B<sub>n</sub>)，存在1≤I≤n，使得(A<sub>1</sub>,A<sub>2</sub>,…,A<sub>i-1</sub>)＝(B<sub>1</sub>,B<sub>2</sub>,…,B<sub>i-1</sub>)且A<sub>i</sub>＜B<sub>i</sub>。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>即两个整数n和t ( 1≤n≤20，0≤t≤n*(n-1)/2 )。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="NormalText">第一行表示n个参数都不通的物品组成的序列集合中，逆序数为t的序列个数；</p>
<p class="NormalText">&nbsp;&nbsp;&nbsp; 第二行是所求物品参数序列。假设n个物品分别为1到n。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>
<p>1 4 3 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>   </p>
</div>
</div>