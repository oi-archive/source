<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Z君是Wikioi上的下标程高手。他曾经创造过2分钟AC7题的神迹。</p>
<p>今天，Z君又想下标程了。他要下N个标程，每个占用带宽Ai，用时Bi。他家的带宽为K。</p>
<p>他用的Z for PC下载软件是这样下载的：</p>
<p>对于队列中的任务，(1)剩余带宽够时，开始下载。</p>
<p>（2）不够时，进入等待队列，等到够时再优先下载。</p>
<p>请你帮Z君算算，需要多少时间才能下完？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>N  K</p>
<p>之后N行，Ai，Bi。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>时间</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 5</p>
<p>3 2</p>
<p>3 1</p>
<p>2 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>（说明：先下标程1，用2分钟；标程2带宽不够，下完1后开始下。</p>
<p>同时下标程3，用2分钟。总时间4分钟。）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据很小。</p>
<p>N&lt;=10,K&lt;=30,Ai&lt;=K,Bi&lt;=10.</p>
</div>
</div>