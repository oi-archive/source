<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定n个01编码串S1,S2,…,Sn，你的任务是寻找一个编码串T，使得它至少可以被分解为两种不同的S<sub>i</sub>的排列。</p>
<p>例如：</p>
<p>给定5个01编码串：S1=0110，S2=00，S3=111，S4=001100，S5=110。那么一个符合要求的编码串T是：001100110，它有以下两种分解方法：</p>
<p> 00+110+0110 (S2+S5+S1) 或 001100+110 (S4+S5)</p>
<p>而0110110就不符合要求，它只有一种分解方法 0110+110 (S1+S5)。</p>
<p>你要寻找长度最短的符合要求的编码串T。若有多个符合要求的最短编码串T，则输出字典顺序最小的。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入文件第一行包含一个整数n，n不超过20，表示01编码串总数。接下来的n行每行给出一个长度不超过20的01编码串。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp;&nbsp;输出文件共有两行，第一行为要求的编码串T的长度，第二行输出编码串T。对所有的测试数据，问题总有解。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>0110</p>
<p>00</p>
<p>111</p>
<p>001100</p>
<p>110</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>9</p>
<p>001100110</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n不超过20</p>
<p>长度不超过20</p>
</div>
</div>