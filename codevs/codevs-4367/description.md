<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在儿童节，一个熊孩子来到了哲学的圣城，企图膜拜王♂の哲学。由于熊孩子本性大发，将哲学圣城弄得十分脏乱。控油肛对他非常生气。这也不能说控油肛的脾气差，因为他弄丢了很多重要的东西。尤其是dc最喜欢的哲学序列。幸运的是控油肛记得如何修复。于是乎他必须快一点，在dc敢来之前修复好.</p><p>最初，控油肛需要创建一个整数的序列a1,a2,…………an。然后控油肛就可以执行以下操作：</p><p>1.打印操作:给定两个整数l,k 打印区间[l,k]内所有数的和</p><p>2.取模操作:给定三个整数l,k,x对于[l,k]区间内的每一个数a[i],l&lt;=i&lt;=k,a[i]=a[i]mod x;</p><p>3.设置操作:给定两个整数k,x使a[k]=x;</p><p>话说如果是平时控油肛可以一边上舰一边修复数列，可是dc快要回来了，dc若是看见了又要大发雷霆，所以控油肛找到了你，希望你能帮他解决。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">输入的第一行包含了两个整数：n,m。第二行包含了n个整数，分别表示a1，a2………an的初始值。</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">一下m行分别对应着m条指令。每条指令的第一个整数对应着指令的类型</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">如果某行第一个整数是1，对应着打印操作，后面跟着两个整数l,k；</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">如果某行第一个整数是2，对应着取模操作，后面跟着三个整数l,k,x</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">如果某行第一个整数是3，对应着设置操作，后面跟着两个整数k,x</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="font-family: &#39;Microsoft YaHei UI&#39;, &#39;Microsoft YaHei&#39;, &#39;Segou UI&#39;; font-size: 14px; line-height: 20px; white-space: normal; background-color: rgb(255, 255, 255);">对于每个打印操作，输出一行结果。</p><p style="font-family: &#39;Microsoft YaHei UI&#39;, &#39;Microsoft YaHei&#39;, &#39;Segou UI&#39;; font-size: 14px; line-height: 20px; white-space: normal; background-color: rgb(255, 255, 255);">注意，输出数据可能超过32位整数范围</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">3 1</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">1 2 3</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">1 1 3</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';"> </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">6</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">对于30%数据，m，n&lt;=50000;</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">对于50%的数据，m,n&lt;=100000;</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">对于75%的数据，m,n&lt;=500000;</p><p style="font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">对于100%的数据，m,n&lt;=700000;a[i]&lt;=2^30-1并且所有输出均longlong以内.</p><p>备注：数据非常水放心做</p>
</div>
</div>