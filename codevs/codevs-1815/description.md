<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一对双胞胎兄妹同一天过生日，这一天，他们的朋友给他俩送来了礼物，每个人送的礼物都是2本书，一本给哥哥，一本给妹妹，但没有说明哪本是给妹妹的，哪本是给哥哥的，每本书都有自己的价值，为了避免冲突，让你来分配，要求使得两人所获得书本的价值和之间的差距尽可能的小。</p>
<p>例如，有4个礼物：(3,5),(7,11),(8,8),(2,9),可以把3,7,8,2分配给妹妹，其余的给哥哥，价值差为：5+11+8+9-3-7-8-2=13;如果把3，7，8，9给妹妹，其余的给哥哥，价值差为：3+7+8+9-5-11-8-2=1，这是最好的方案。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行包含一个正整数N，表示礼物的数量，接下来N行，每行两个整数，表示每份礼物两本书的价值(价值范围在1到300之间)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出包含一个非负整数，表示最小的价值差。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>3 5</p>
<p>7 11</p>
<p>8 8</p>
<p>2 9</p>

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
<p><strong>【数据规模】</strong></p>
<p>对于20%的数据，有N≤20；</p>
<p>对于40%的数据，有N≤50；</p>
<p>对于100%的数据，有N≤150。</p>
</div>
</div>