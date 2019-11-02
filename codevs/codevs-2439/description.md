<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>我们常常会说这样的话：“X年是自Y年以来降雨量最多的”。它的含义是X年的降雨量不超过Y年，且对于任意Y&lt;Z&lt;X，Z年的降雨量严格小于X年。例如2002，2003，2004和2005年的降雨量分别为4920，5901，2832和3890，则可以说“2005年是自2003年以来最多的”，但不能说“2005年是自2002年以来最多的”由于有些年份的降雨量未知，有的说法是可能正确也可以不正确的。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入仅一行包含一个正整数<em>n</em>，为已知的数据。以下<em>n</em>行每行两个整数<em>y<sub>i</sub></em>和<em>r<sub>i</sub></em>，为年份和降雨量，按照年份从小到大排列，即<em>y<sub>i</sub></em>&lt;<em>y<sub>i</sub></em><sub>+1</sub>。下一行包含一个正整数<em>m</em>，为询问的次数。以下<em>m</em>行每行包含两个数Y和X，即询问“X年是自Y年以来降雨量最多的。”这句话是必真、必假还是“有可能”。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每一个询问，输出true，false或者maybe。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6</p>
<p>2002 4920</p>
<p>2003 5901</p>
<p>2004 2832</p>
<p>2005 3890</p>
<p>2007 5609</p>
<p>2008 3024</p>
<p>5</p>
<p>2002 2005</p>
<p>2003 2005</p>
<p>2002 2007</p>
<p>2003 2007</p>
<p>2005 2008</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>false</p>
<p>true</p>
<p>false</p>
<p>maybe</p>
<p>false</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>100%的数据满足：1&lt;=<em>n</em>&lt;=50000, 1&lt;=<em>m</em>&lt;=10000, -10<sup>9</sup>&lt;=<em>y<sub>i</sub></em>&lt;=10<sup>9</sup>, 1&lt;=<em>r<sub>i</sub></em>&lt;=10<sup>9</sup></p>
</div>
</div>