<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>幼儿园里有n个小朋友打算通过投票来决定睡不睡午觉。对他们来说，这个问题并不是很重要，于是他们决定发扬谦让精神。虽然每个人都有自己的主见，但是为了照顾一下自己朋友的想法，他们也可以投和自己本来意愿相反的票。我们定义一次投票的冲突数为好朋友之间发生冲突的总数加上和所有和自己本来意愿发生冲突的人数。</p>
<p>我们的问题就是，每位小朋友应该怎样投票，才能使冲突数最小？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>文件的第一行只有两个整数n，m，保证有2≤n≤300，1≤m≤n(n-1)/2。其中n代表总人数，m代表好朋友的对数。文件第二行有n个整数，第i个整数代表第i个小朋友的意愿，当它为1时表示同意睡觉，当它为0时表示反对睡觉。接下来文件还有m行，每行有两个整数i，j。表示i，j是一对好朋友，我们保证任何两对i，j不会重复。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>只需要输出一个整数，即可能的最小冲突数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p>
<p>1 0 0</p>
<p>1 2</p>
<p>1 3</p>
<p>3 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>2≤n≤300，1≤m≤n(n-1)/2。</p>
</div>
</div>