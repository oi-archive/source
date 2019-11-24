<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>任何一个正整数都可以用2的幂次方表示.<br> 例如:137=2^7+2^3+2^0<br>同时约定次方用括号来表示,即a^b可表示为a(b)<br> 由此可知,137可表示为:2(7)+2(3)+2(0)<br> 进一步:7=2^2+2+2^0 (2^1用2表示)<br> 3=2+2^0<br> 所以最后137可表示为:2(2(2)+2+2(0))+2(2+2(0))+2(0)<br> 又如:1315=2^10+2^8+2^5+2+1<br> 所以1315最后可表示为:2(2(2+2(0))+2)+2(2(2+2(0)))+2(2(2)+2(0))+2+2(0)</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>正整数n</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>符合约定的n的0,2表示(在表示中不能有空格)</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【输入样例1】<br>137<br>【输入样例2】<br>1315</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【输出样例1】<br>2(2(2)+2+2(0))+2(2+2(0))+2(0)<br>【输出样例2】<br>2(2(2+2(0))+2)+2(2(2+2(0)))+2(2(2)+2(0))+2+2(0)</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n为2的指数&lt;=1100586419200</p>
</div>
</div>