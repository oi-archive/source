<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>伐木工人米尔科需要砍倒M米长的木材。这是一个对米尔科来说很容易的工作，因为他有一个漂亮的新伐木机，可以像野火一样砍倒森林。不过，米尔科只被允许砍倒单行树木。</p>
<p>       米尔科的伐木机工作过程如下：米尔科设置一个高度参数H（米），伐木机升起一个巨大的锯片到高度H，并锯掉所有的树比H高的部分（当然，树木不高于H米的部分保持不变）。米尔科就得到树木被锯下的部分。</p>
<p>       例如，如果一行树的高度分别为20,15,10和17米，米尔科把锯片升到15米的高度，切割后树木剩下的高度将是15,15,10和15米，而米尔科将从第1棵树得到5米，从第4棵树得到2米，共得到7米木材。</p>
<p>       米尔科非常关注生态保护，所以他不会砍掉过多的木材。这正是他为什么要尽可能高地设定伐木机锯片的原因。帮助米尔科找到伐木机锯片的最大的整数高度H，使得他能得到的木材至少为M米。换句话说，如果再升高1米，则他将得不到M米木材。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：2个整数N和M，N表示树木的数量（1&lt;=N&lt;=1000000）,M表示需要的木材总长度（1&lt;=M&lt;=2000000000）</p>
<p>       第2行：N个整数表示每棵树的高度，值均不超过1000000000.所有木材长度之和大于M，因此必然有解</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第1行：1个整数，表示砍树的最高高度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 20</p>
<p>4 42 40 26 46</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>36</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>