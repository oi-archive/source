<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>对于二进制串a，b，他们之间的海明距离是指两个串异或之后串中1的个数。异或的规则为：</p>
<p>0 XOR 0 = 0</p>
<p>1 XOR 0 = 1</p>
<p>0 XOR 1 = 1</p>
<p>1 XOR 1 = 0</p>
<p>       计算两个串之间的海明距离的时候，他们的长度必须相同。现在我们给出N个不同的二进制串，请计算出这些串两两之间的最短海明距离。</p>
<p><strong></strong> </p>
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
<p>第一个数字是整数T（T≤10），代表数据的组数。</p>
<p>接下来有T组数据，每组数据的第一行是一个正整数N，代表不同的二进制串的个数。接下来是N行，每行都是一个二进制串。我们用数字(0-9)和字符(A-F)来表示这个二进制串。它代表这个二进制串的16进制码。例如，“12345”代表的二进制串为“00010010001101000101”。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个数据，请输出一个整数，即答案值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p> </p>
<div>
<p>2</p>
<p>2</p>
<p>12345</p>
<p>54321</p>
<p>4</p>
<p>12345</p>
<p>6789A</p>
<p>BCDEF</p>
<p>0137F</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div>
<p>6</p>
<p>7</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据有1≤<em>N</em>≤100</p>
<p>对于全部数据，有1≤<em>N</em>≤100000<strong></strong></p>
</div>
</div>