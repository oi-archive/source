<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一个神秘的国家，他们有不同的文明，他们所使用的数字表示法跟常见的十进制法不一样。对于一个十进制的数字 N，他们会表示成abc，其中  a &gt; b &gt; c &gt;= 0，且满足N= C(a, 3) + C( b, 2) + C(c, 1)，C 为二项系数，即 C(m, n)=m!/(n!(m-n)! )，但当 m &lt; n时，C(m, n) = 0。为帮助了解这个神秘国度的文化，请写一程序來将十进制数转换成这个神秘的进位法。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有一个整数 m，1≤ m≤ 10，代表要转换的十进制数的个数。接下來的 m 行（第2 行至第(m+1) 行）：每一行都有一个介于 0 和500 之间的整数，代表要转换的十进制数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>针对每一个十进制数分别在一行输出对应的abc，其间不需留空白，注意 <strong>a 、b 和c 未必只有一位数</strong>，若答案不唯一时请输出字典顺序最小的表示法，即尽可能取小的a 及b 值。</p>

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
<p>4</p>
<p>0</p>
<p>1</p>
<p>2</p>
<p>200 </p>
<p> </p>
<p>样例2：</p>
<p>3</p>
<p>18</p>
<p>19</p>
<p>20 </p>

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
<p>210</p>
<p>310</p>
<p>320</p>
<p>1187 </p>
<p> </p>
<p>样例2：</p>
<p>542</p>
<p>543</p>
<p>610</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1.   所有数字皆为非负整数。</p>
<p>2.   0  ≤ N  ≤ 500,1≤ m≤ 10。</p>
<p> </p>
<p>TW一百学年度全国高级中学咨询学科能力竞赛决赛2</p>
</div>
</div>