<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">定义<span style="font-family: Times New Roman;">f(x,y)</span><span style="">为</span><span style="font-family: Times New Roman;">x,y</span><span style="">的所有公因数之和。现将f(i,j)填入n*m的表格中。</span></span></p><p><span style="">给出<span style="font-family: Times New Roman;">n,m,a</span><span style="">，求这个表格中不超过a的数之和。</span></span><span style="">为了降低程序的常数因子，答案用有符号</span><span style="font-family: 'Times New Roman';">32</span><span style="">位整数</span><span style="font-family: 'Times New Roman';">(C++</span><span style="">中的</span><span style="font-family: 'Times New Roman';">int / Pascal</span><span style="">中的</span><span style="font-family: 'Times New Roman';">longint)</span><span style="">自然溢出即可。</span></p><p><span style="">题目要求在线算法。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入包含多组数据。</span></p><p><span style="">输入的第一行一个整数<span style="font-family: Times New Roman;">Q</span><span style="">表示测试点内的数据组数。接下来</span><span style="font-family: Times New Roman;">Q</span><span style="">行，每行四个整数</span><span style="font-family: Times New Roman;">n,m,a0,p</span><span style="">描述一组数据。</span></span></p><p><span style="">注意：所有的<span style="font-family: Times New Roman;">a</span><span style="">均被加密。设</span><span style="font-family: Times New Roman;">last</span><span style="">为上一次询问的答案的绝对值，则这次询问实际的</span><span style="font-family: Times New Roman;">a</span><span style="">为</span><span style="font-family: Times New Roman;">(a0 xor last) mod p</span><span style="">。一开始</span><span style="font-family: Times New Roman;">last=0</span><span style="">。</span></span></p><p><span style="">C++<span style="">语言中可表示为</span><span style="font-family: Times New Roman;">a = 1LL*(a^last)%p, </span><span style="">每次询问后你需要记录</span><span style="font-family: Times New Roman;">last = abs(ans)</span><span style="">。</span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 宋体; font-size: 14px;">对每组数据，输出一行一个整数，由于自然溢出的结果，答案可能是负数。</span><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">2</span></p><p><span style="">4 4 3 9999</span></p><p><span style="">1 2 54 123</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">20</span></p><p><span style="">2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">1&lt;=n,m&lt;=30000, Q&lt;=10000,  |a0|,|k|,|p|&lt;=10^9<span style="">， </span><span style="font-family: Times New Roman;">p!=0</span></span></p><p><span style=""><span style="font-family: Times New Roman;">样例数据中：</span></span></p><p><span style="">第一次讯问时实际的<span style="font-family: Times New Roman;">a</span><span style="">为</span><span style="font-family: Times New Roman;">3</span><span style="">。</span></span></p><p><span style="">第二次讯问时实际的<span style="font-family: Times New Roman;">a</span><span style="">为</span><span style="font-family: Times New Roman;">34</span><span style="">。</span></span></p><p><br></p>
</div>
</div>