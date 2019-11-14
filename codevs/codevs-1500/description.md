<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>天凯是MIT的新生。Prof. HandsomeG给了他一个长度为n的由小写字母构成的字符串，要求他把该字符串的n个后缀(suffix)从小到大排序。</p>
<p>何谓后缀？假设字符串是S=S1S2……Sn，定义Ti=SiSi+1……Sn。T1, T2, …, Tn就叫做S的n个后缀。</p>
<p>关于字符串大小的比较定义如下（比较规则和PASCAL中的定义完全相同，熟悉PASCAL的同学可以跳过此段）：</p>
<p>若A是B的前缀，则A&lt;B；否则令p满足：A1A2…Ap-1=B1B2…Bp-1，Ap&lt;&gt;Bp。如果Ap&lt;Bp，则A&lt;B；否则A&gt;B。</p>
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
<p>第一行一个整数n(n&lt;=15000)</p>
<p>第二行是一个长度为n字串。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件包含n行，第i行是一个整数pi。表示所有的后缀从小到大排序后是Tp1,&nbsp;Tp2,&nbsp;&hellip;,&nbsp;Tpn。</p>

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
<p>abab</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>1</p>
<p>4</p>
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>说明：后缀排序后的顺序是T3=”ab”, T1=”abab”, T4=”b”, T2=”bab”。所以输出是3, 1, 4, 2。</p>
</div>
</div>