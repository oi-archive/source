<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>农民JOHN以拥有世界上最健康的奶牛为傲。他知道每种饲料中所包含的牛所需的最低的维他命量是多少。请你帮助农夫喂养他的牛，以保持它们的健康，使喂给牛的饲料的种数最少。</p>
<p>给出牛所需的最低的维他命量，输出喂给牛需要哪些种类的饲料，且所需的饲料剂量最少。</p>
<p>维他命量以整数表示，每种饲料最多只能对牛使用一次，数据保证存在解。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：一个整数V(1&lt;=V&lt;=25)，表示需要的维他命的种类数。</p>
<p>第2行：V个整数(1&lt;=每个数&lt;=1000)，表示牛每天需要的每种维他命的最小量。</p>
<p>第3行：一个整数G(1&lt;=G&lt;=15)，表示可用来喂牛的饲料的种数。</p>
<p>下面G行，第n行表示编号为n饲料包含的各种维他命的量的多少。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件只有一行，包括</p>
<p>牛必需的最小的饲料种数P</p>
<p>后面有P个数，表示所选择的饲料编号（按从小到大排列）。</p>
<p>如果有多个解，输出饲料序号最小的（即字典序最小）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>4
100 200 300 400
3
50 50 50 50
200 300 200 300
900 150 389 399</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>2 1 3</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见描述 </p>
</div>
</div>