<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>A队和B队之间要进行一场团队赛，双方各有N名队员，并且需要在赛前安排好出场顺序。比赛规则是这样的，双方先各派顺序中的第一名队员上场进行比赛，每次比赛的败者所属的队伍需要派上顺序中的下一名队员。当某一队的最后一名队员失败时，该队被判做输掉这场团队赛。每名队员都有一个值为正的能力值，当一名能力值为x的队员和另一名能力值为y的队员进行比赛时，前者的胜率为x/(x+y)，后者的胜率为y/(x+y)。A队的领队知道两队各队员的能力值以及B队的出场顺序，他要决定一种A队的出场顺序使得A对的胜率最大。作为A队领队的好友你，必须接下这项任务，告诉他最大的胜率。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">第一行为正整数N。</p><p style="">第二行为N个正整数，表示A队各队员的能力值。</p><p style="">第三行为N个正整数，表示B队顺序下的各队员的能力值。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行，一个实数，为A队的最大胜率，保留6位小数。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1</p><p>2</p><p>3</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0.400000<br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于10%的数据，N&lt;=4；</p><p>对于20%的数据，N&lt;=8；</p><p>对于30%的数据，N&lt;=12；</p><p>对于50%的数据，N&lt;=1,500；</p><p>对于100%的数据，N&lt;=4,500。</p><p><br></p>
</div>
</div>