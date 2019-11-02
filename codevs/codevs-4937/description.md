<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>你被要求设计一个计算器完成以下三项任务：</p><p>1、给定y,z,p,计算Y^Z Mod P 的值；</p><p>2、给定y,z,p，计算满足xy≡ Z ( mod P )的最小非负整数；</p><p>3、给定y,z,p，计算满足Y^x ≡ Z ( mod P)的最小非负整数。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p> 输入包含多组数据。</p><p>第一行包含两个正整数T,K分别表示数据组数和询问类型（对于一个测试点内的所有数据，询问类型相同）。</p><p>以下行每行包含三个正整数y,z,p，描述一个询问。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个询问，输出一行答案。对于询问类型2和3，如果不存在满足条件的，则输出“Orz, I cannot find x!”，注意逗号与“I”之间有一个空格。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>【样例输入1】<br>3 1<br>2 1 3<br>2 2 3<br>2 3 3<br>【样例输入2】<br>3 2<br>2 1 3<br>2 2 3<br>2 3 3<br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>【样例输出1】<br>2<br>1<br>2<br>【样例输出2】<br>2<br>1<br>0<br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据，1&lt;=y,z,p&lt;=10^9，为质数，1&lt;=T&lt;=10。</p>
</div>
</div>