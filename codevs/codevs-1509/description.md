<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>     LongDD 将军为了平息延续数年战乱，决定释放战俘营中所有的俘虏。然而，LongDD 将军不打算释放敌军的统帅LongMM——因为这个家伙异常聪明，是个难缠的对手。所以LongDD 将军决定把LongMM 用链子固定到墙上。链子由n 个环组成，每个环有可能在墙上，也可能不在墙上。<br>     “LongDD 将军，你为什么把我绑在墙上，不让我获得自由”，LongMM 咆哮道。<br>     “但是，LongMM，你并没有被绑在墙上。我很确定你可以自己把链子解开”，LongDD 将军回答道，“但是请你在天黑之前解开，否则我会因为你制造噪音把你重新抓起来。”<br>    请帮助LongMM 吧！链子由n 个环组成，编号为1,2,…,n。我们可以把每个环从墙上取下来或者从新放回墙上，但是需要遵循如下规则：<br> - 每一步只能取下或者装上一个环<br> - 编号为1 的环可以随意取下或装上<br> - 如果编号为1,…,k-1 的环都取下了，并且编号为k 的环在墙上，我们可以随意取下或者装上第k+1 个环<br> - 当所有环都取下来之后，LongMM 可以逃脱了<br> 给定每个环的初始状态，请你编写程序计算LongMM 最少需要多少步才能逃脱。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第 1 行: 有一个整数n，(1&lt;=n&lt;=1000)，表示环的个数<br>第 2 行: 有n 个整数，第i 个整数O<sub>i</sub>=0，表示第i 个环在初始的时候为摘下的<br> 状态；如果O<sub>i</sub>=1，表示第i 个环初始的时候为装在墙上的状态。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<div id="yass_top_edge_dummy" style="width: 1px; height: 1px; padding: 0px; margin: -9px 0px 0px; border-width: 0px; display: block;">&nbsp;</div>
<div id="yass_top_edge" style="background-image: url('chrome://yass/content/edgebgtop.png'); background-attachment: scroll; background-position: center bottom; padding: 0px; margin: 0px 0px 0px -8px; border-width: 0px; height: 0px; display: block; width: 1px;">&nbsp;</div>
<p style="margin-top: 8px;">仅&nbsp;1 行: 只有一个整数，表示最少需要多少步才能让LongMM 逃脱。</p>
<div id="yass_bottom_edge" style="background-image: url('chrome://yass/content/edgebgbot.png'); background-position: 0px 0px; position: absolute; margin: 0px; padding: 0px; border-width: 0px; height: 0px; left: 0px; top: 0px; width: 100%; display: block;">&nbsp;</div>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4<br> 1 0 1 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>可以尝试使用递推或动态规划求解</p>
</div>
</div>