<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>【dzy493941464|yywyzdzr原创】 </p>
<p>小A将<em>N</em>张卡片整齐地排成一排，其中每张卡片上写了1~<em>N</em>的一个整数，每张卡片上的数各不相同。</p>
<p>比如下图是<em>N</em>=5的一种情况：3 4 2 1 5</p>
<p>接下来你需要按小A的要求反转卡片，使得左数第一张卡片上的数字是1。操作方法：令左数第一张卡片上的数是<em>K</em>，如果<em>K</em>=1则停止操作，否则将左数第1~<em>K</em>张卡片反转。</p>
<p>第一次(<em>K</em>=3)反转后得到：2 4 3 1 5</p>
<p>第二次(<em>K</em>=2)反转后得到：4 2 3 1 5</p>
<p>第三次(<em>K</em>=4)反转后得到：1 3 2 4 5</p>
<p>可见反转3次后，左数第一张卡片上的数变成了1，操作停止。</p>
<p>你的任务是，对于一种排列情况，计算要反转的次数。你可以假设小A不会让你操作超过100000次。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行一个整数<em>N</em>；</p>
<p>第2行<em>N</em>个整数，为1~<em>N</em>的一个全排列。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅1行，输出一个整数表示要操作的次数。</p>
<p>如果经过有限次操作仍无法满足要求，输出-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>3 4 2 1 5</p>
<p> </p>
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
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>0&lt;<em>N</em>≤300,000。</p>
</div>
</div>