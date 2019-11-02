<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在大学期间，经常需要租借教室。大到院系举办活动，小到学习小组自习讨论，都需要</p><p>向学校申请借教室。教室的大小功能不同，借教室人的身份不同，借教室的手续也不一样。</p><p>面对海量租借教室的信息，我们自然希望编程解决这个问题。</p><p>我们需要处理接下来n天的借教室信息，其中第i天学校有ri个教室可供租借。共有m份</p><p>订单，每份订单用三个正整数描述，分别为dj, sj, tj，表示某租借者需要从第sj天到第tj天租</p><p>借教室（包括第sj天和第tj天），每天需要租借dj个教室。</p><p>我们假定，租借者对教室的大小、地点没有要求。即对于每份订单，我们只需要每天提</p><p>供dj个教室，而它们具体是哪些教室，每天是否是相同的教室则不用考虑。</p><p>借教室的原则是先到先得，也就是说我们要按照订单的先后顺序依次为每份订单分配教</p><p>室。如果在分配的过程中遇到一份订单无法完全满足，则需要停止教室的分配，通知当前申</p><p>请人修改订单。这里的无法满足指从第sj天到第tj天中有至少一天剩余的教室数量不足dj个。</p><p>现在我们需要知道，是否会有订单无法完全满足。如果有，需要通知哪一个申请人修改</p><p>订单。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个正整数n, m，表示天数和订单的数量。</p><p>提高组  day2 </p><p> </p><p>第二行包含n个正整数，其中第i个数为ri，表示第i天可用于租借的教室数量。</p><p>接下来有m行，每行包含三个正整数dj, sj, tj，表示租借的数量，租借开始、结束分别在</p><p>第几天。</p><p>每行相邻的两个数之间均用一个空格隔开。天数与订单均用从1开始的整数编号。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">如果所有订单均可满足，则输出只有一行，包含一个整数&nbsp;0。否则（订单无法完全满足）</p><p class="p0">输出两行，第一行输出一个负整数-1，第二行输出需要修改订单的申请人编号。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 3 </p><p>2 5 4 3 </p><p>2 1 3 </p><p>3 2 4 </p><p>4 2 4 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>-1 </p><p>2 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【输入输出样例说明】</p><p>classroom.out </p><p>-1 </p><p>2 </p><p> </p><p>第 1 份订单满足后，4 天剩余的教室数分别为 0，3，2，3。第 2 份订单要求第 2 天到</p><p>第 4 天每天提供 3 个教室，而第 3 天剩余的教室数为 2，因此无法满足。分配停止，通知第</p><p>2 个申请人修改订单。</p><p>【数据范围】</p><p>对于 10%的数据，有1 &amp;le;  n, m &amp;le;  10；</p><p>对于 30%的数据，有1 &amp;le;  n, m &amp;le; 1000；</p><p>对于 70%的数据，有1 &amp;le;  n, m &amp;le;   105；</p><p>对于 100%的数据，有1 &amp;le; n, m &amp;le; 10^6, 0 &amp;le; ri, dj&amp;le; 10^9, 1 &amp;le; sj&amp;le; tj&amp;le; n。</p>
</div>
</div>