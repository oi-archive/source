<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Ztc想把他满屋子的书整理一下。为了应付繁重的学习任务，ztc已经筋疲力尽了，于是他向你求助，请你帮他计算他最少需要花费多少力气。 书本分为若干堆，呈直线排布。每一堆的书本都有重量w和价值v。Ztc的任务是将所有书合成一堆。因为Ztc很看重书本的价值，所以他认为合并i，j两堆得书所需要的力气为w[i]-v[i]+w[j]-v[j]。合并后的书堆的重量和价值均为合并前两堆书的重量和价值的综合。也就是说，合并i，j两堆的书后，w=w[i]+w[j],v=v[i]+v[j]。小智个人不愿意走来走去，所以合并只能在相邻两堆书本间进行。书本合并前后，位置不变。如将1，2，3中的1，2进行合并，那么合并结果为3，3，再将3，3合并为6（1，2，3，6指重量）。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行市一个整数n（2&lt;=n&lt;=400）。 第2-n+1行每行每个整数w和v（0&lt;v&lt;w&lt;=1000）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件共一行，这一行只有一个整数f，表示最小力气。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>6 5</p>
<p>9 7</p>
<p>11 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>15</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的数据满足：2&lt;=n&lt;=100</p>
<p>       100%的数据满足：2&lt;=n&lt;=400</p>
</div>
</div>