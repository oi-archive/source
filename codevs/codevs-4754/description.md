<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style=""><strong>此题因数据有误已清空数据。</strong></span></p><p><span style=""><strong><span style="">管理员看到本题后请帮助删除，谢谢。</span></strong></span><span style=""><br></span></p><p><span style=""><strong><br></strong></span></p><p><span style=""><strong><br></strong></span></p><p><br></p><p>N则运算是普通运算和位运算的集合。你需要根据输入的N，来输出以下规则中规则1~规则n的运算结果。如果n&gt;20或n≤0，则你要视为n=20；</p><p>1.加法运算 2.减法运算 3.乘法运算 4.整除运算（向下取整） 5.除法运算（保留两位小数） 6.或运算 7.异或运算 8.与运算 9.左移运算 10.右移运算 11~19.输出对应值（如11输出11,12输出12） 20.取反运算（取反x）</p><p>若无数据组，请输出"No Case"，否则你要在最后一行以"Total case:x"的形式输出总共的测试点数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行输入一个a，若a=0，则表示无数据组，请直接按照题目描述中无数据组的处理方式进行处理，否则请继续执行程序。</p><p>每组输入一个n，以及两个操作数x和y，中间以空格隔开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>每行输出n个结果，两组数据间以一个单独的“a”隔开。</p><p>最后一行以&quot;Total case:x&quot;的形式输出总共的测试点数，在该行前也要有一行&quot;a&quot;。</p><p>若无数据组，则直接输出一行&quot;No Case&quot;！</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1</p><p>1 1 1</p><p>5 1 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2<br></p><p>a</p><p>5 -3 4 0 0.25</p><p>a</p><p>Total case:2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n在±10000的范围内,a只会是1或0,0≤x和y≤50</p>
</div>
</div>