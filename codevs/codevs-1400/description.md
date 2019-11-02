<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>毕业于普通本科的小Q一直自称是资深屌丝，不仅学校不知名，甚至他自己在这个普通学校也是默默无闻——直到临近毕业的时候，班里5朵金花中的2位甚至从没和他说过话！</span><br><span>　　谁又能想到，如此不起眼的小Q在历经重重面试环节后，竟然如愿以偿加入了心仪已久的腾讯公司！消息刚刚传开的那几天，这在他们班甚至整个学院都是讨论的热门话题，如果这时候你还表示不知道小Q是谁，你都会被大家当作怪物的。</span><br><span>　　正所谓野百合也有春天，屌丝也有逆袭的那一天！</span><br><span>　　</span><br><span>　　刚到腾讯大厦上班的那几天，小Q眼中的一切都是那么新鲜，连每天见到的前台MM在他眼中都胖的那么可爱。小Q就这样在紧张与兴奋的情绪中度过了一天又一天，每天即勤奋认真又小心翼翼，很希望能给主管留下个好印象，以免失去这来之不易的工作机会。</span><br><span>　　一段时间以后，随着对工作环境以及同事的熟悉，小Q逐渐放松下来，在工作间隙，他细细观察了自己的工作环境，发现整个工作室是一个N行M列的矩形布局，或者是因为屌丝的本性逐步暴露，他还暗自给每个同事在心里进行了魅力值评分（为区别男女，男生一律用负整数表示，女生一律用正整数表示）。</span><br><span>　　现在，小Q把所有人的数据记录下来，并且这样定义一个位置的价值：</span><br><span>　　1、一个位置的价值只和其上下左右四个邻居的魅力值有关（对于靠边的位置，只考虑其存在的邻居）；</span><br><span>　　2、如果某位置的邻居和该位置主人性别不同，则总分加上邻居魅力值的绝对值，否则减去；</span><br><span>　　3、对周围所有邻居的数据处理后，最终的得分即为这个位置的最终得分，得分越高，则该位置越好；</span><br><br><span>　　现在你能帮助小Q计算一下哪里才是最佳位置吗？</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<div>输入包含多组测试数据；<br>每组测试数据的第一行包含2个整数N和M，表示工作室的布局是N行M列；<br>接下来的N行，每行有M个整数，分别表示对应位置员工的魅力值数据Ki，正整数表示女生的魅力值，负整数表示男生的魅力值；<br>N和M为0的时候表示输入数据结束。<br><br>[Technical Specification]<br>N&lt;=20<br>M&lt;=20<br>-100&lt;=Ki&lt;=100</div>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>请计算并输出最佳位置的行列号以及对应的得分，如果得分最高的位置有多个，则请输出行号最小的那个，行号还相同的话，再比较列号，只输出列号最小的那个即可。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>2 3</span></p>
<p><span> 5 -4 3</span></p>
<p><span> -6 3 7</span></p>
<p><span> 0 0</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>1 2 11</span></p>

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