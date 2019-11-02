<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定一个只包含加法和乘法的算术表达式，请你编程计算表达式的值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入仅有一行，为需要你计算的表达式，表达式中只包含数字、加法运算符“+”和乘法运算符“*”，且没有括号，所有参与运算的数字均为0到2^31-1之间的整数。输入数据保证这一行只有0~9、+、*这12种字符。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行，包含一个整数，表示这个表达式的值。注意：当答案长度多于4位时，请只输出最后4位，前导0不输出。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>[Sample 1]<br>1+1*3+4<br>[Sample 2]<br>1+1234567890*1<br>[Sample 3]<br>1+1000000003*1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>[Sample 1]<br>8<br>[Sample 2]<br>7891<br>[Sample 3]<br>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】<br>样例1计算的结果为8，直接输出8。<br>样例2计算的结果为1234567891，输出后4位，即7891。<br>样例3计算的结果为1000000004，输出后4位，即4。<br> <br>【数据范围】<br>对于30%的数据，0≤表达式中加法运算符和乘法运算符的总数≤100；<br>对于80%的数据，0≤表达式中加法运算符和乘法运算符的总数≤1000；<br>对于100%的数据，0≤表达式中加法运算符和乘法运算符的总数≤100000。</p>
</div>
</div>