<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>你有n个砝码，均为1克，2克或者3克。你并不清楚每个砝码的重量，但你知道其中一些砝码重量的大小关系。你把其中两个砝码A和B放在天平的左边，需要另外选出两个砝码放在天平的右边。问：有多少种选法使得天平的左边重(c1)、一样重(c2)、右边重(c3)？（只有结果保证惟一的选法才统计在内）</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行包含三个正整数n，A，B（1&lt;=A，B&lt;=N，A和B不相等）。砝码编号为1~N。以下n行包含重量关系矩阵，其中第i行第j个字符为加号“+”表示砝码i比砝码j重，减号“-”表示砝码i比砝码j轻，等号“=”表示砝码i和砝码j一样重，问号“?”表示二者的关系未知。存在一种情况符合该矩阵。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>仅一行，包含三个整数，即c1，c2和c3。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>6 2 5</span><br><span> ?+????</span><br><span> -?+???</span><br><span> ?-????</span><br><span> ????+?</span><br><span> ???-?+</span><br><span> ????-?</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>1 4 1</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>4&lt;=n&lt;=50</span></p>
</div>
</div>