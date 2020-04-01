<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给你n根火柴棍，你可以拼出多少个形如“A+B=C”的等式？等式中的A、B、C是用火柴棍拼出的整数（若该数非零，则最高位不能是0）。用火柴棍拼数字0-9的拼法如图所示：</p>
<p>注意：</p>
<p>1. 加号与等号各自需要两根火柴棍</p>
<p>2. 如果A≠B，则A+B=C与B+A=C视为不同的等式（A、B、C&gt;=0）</p>
<p>3. n根火柴棍必须全部用上</p>

<img src="/source/codevs/codevs-1168/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMTY4L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8xMTY4LnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件共一行，又一个整数n（n&lt;=24）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件共一行，表示能拼成的不同等式的数目。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1：</p>
<p>14</p>
<p> </p>
<p>样例2：</p>
<p>18</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1：</p>
<p>2</p>
<p> </p>
<p>样例2：</p>
<p>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【输入输出样例1解释】</p>
<p>2个等式为0+1=1和1+0=1。</p>
<p>【输入输出样例2解释】</p>
<p>9个等式为：</p>
<p>0+4=4</p>
<p>0+11=11</p>
<p>1+10=11</p>
<p>2+2=4</p>
<p>2+7=9</p>
<p>4+0=4</p>
<p>7+2=9</p>
<p>10+1=11</p>
<p>11+0=11</p>
</div>
</div>