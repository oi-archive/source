<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>假设有一个需要使用某一资源的n（n≤1000）个活动组成的集合S，S={1，…，n}。该资源一次只能被一个活动占有，每一个活动有一个开始时间b<sub>i</sub>和结束时间e<sub>i</sub>（b<sub>i</sub>≤e<sub>i</sub>）。若b<sub>i</sub>&gt;e<sub>j</sub>或者b<sub>j</sub>&gt;e<sub>i</sub>，则活动i和活动j兼容。</p>
<p>你的任务是是：选择由互相兼容的活动组成的最大集合。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>共n+1行，其中第1行为n，第2行到第n+1行表示n个活动的开始时间和结束时间（中间用一个空格隔开），格式为：</p>
<p>n</p>
<p>b1  e1</p>
<p>…….</p>
<p>bn  en</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共有两行，第1行为满足要求的活动占用的时间t，第2行为最大集合中的活动序号，每个序号之间用一个空格隔开。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>11</p>
<p>3 5</p>
<p>1 4</p>
<p>12 14</p>
<p>8 12</p>
<p>0 6</p>
<p>8 11</p>
<p>6 10</p>
<p>5 7</p>
<p>3 8</p>
<p>5 9</p>
<p>2 13</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>14</p>
<p>2 3 6 8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据范围不大，不用考虑。</p>
</div>
</div>