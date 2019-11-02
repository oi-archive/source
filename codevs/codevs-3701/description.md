<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">设计一个数据结构</span>. <span style="">给定一个正整数数列</span> a_0, a_1, ..., a_{n - 1}<span style="">，你需要支持以下两种操作：</span></p><p> </p><p style="">1. MODIFY id x: <span style="">将</span> a_{id} <span style="">修改为</span> x.</p><p style="">2. QUERY x: <span style="">求最小的整数</span> p (0 &lt;= p &lt; n)<span style="">，使得</span> gcd(a_0, a_1, ..., a_p) * XOR(a_0, a_1, ..., a_p) = x. <span style="">其中</span> XOR(a_0, a_1, ..., a_p) <span style="">代表</span> a_0, a_1, ..., a_p <span style="">的异或和，</span>gcd<span style="">表示最大公约数。</span></p><p> </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入数据的第一行包含一个正整数</span> n.</p><p style=""><span style="">接下来一行包含</span> n <span style="">个正整数</span> a_0, a_1, ..., a_{n - 1}.</p><p style=""><span style="">之后一行包含一个正整数</span> q<span style="">，表示询问的个数。</span></p><p style=""><span style="">之后</span> q <span style="">行，每行包含一个询问。格式如题目中所述。</span></p><p style=""> </p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:28px"><span style="font-family:宋体">对于每个</span> QUERY <span style="font-family:宋体">询问，在单独的一行中输出结果。如果不存在这样的</span> p<span style="font-family:宋体">，输出</span> no.</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10</p><p>1353600 5821200 10752000 1670400 3729600 6844320 12544000 117600 59400 640</p><p>10</p><p>MODIFY 7 20321280</p><p>QUERY 162343680</p><p>QUERY 1832232960000</p><p>MODIFY 0 92160</p><p>QUERY 1234567</p><p>QUERY 3989856000</p><p>QUERY 833018560</p><p>MODIFY 3 8600</p><p>MODIFY 5 5306112</p><p>QUERY 148900352</p><p> </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p><p>0</p><p>no</p><p>2</p><p>8</p><p>8</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于</span> 30% <span style="">的数据，</span>n &lt;= 10000<span style="">，</span>q &lt;= 1000.</p><p><span style="">对于</span> 100% <span style="">的数据，</span>n &lt;= 100000<span style="">，</span>q &lt;= 10000<span style="">，</span>a_i &lt;= 10^9 (0 &lt;= i &lt; n)<span style="">，</span>QUERY x <span style="">中的</span> x &lt;= 10^18<span style="">，</span>MODIFY id x <span style="">中的</span> 0 &lt;= id &lt; n<span style="">，</span>1 &lt;= x &lt;= 10^9.</p><p> </p><p> </p><p><br></p>
</div>
</div>