<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>21 世纪，许多人得了一种奇怪的病：起床困难综合症，其临床表现为：起床难，起床后精神不佳。作为一名青春阳光好少年，atm 一直坚持与起床困难综合症作斗争。通过研究相关文献，他找到了该病的发病原因：在深邃的太平洋海底中，出现了一条名为 drd 的巨龙，它掌握着睡眠之精髓，能随意延长大家的睡眠时间。正是由于 drd 的活动，起床困难综合症愈演愈烈，以惊人的速度在世界上传播。为了彻底消灭这种病，atm 决定前往海底，消灭这条恶龙。<br>历经千辛万苦，atm 终于来到了 drd 所在的地方，准备与其展开艰苦卓绝的战斗。drd 有着十分特殊的技能，他的防御战线能够使用一定的运算来改变他受到的伤害。具体说来，drd 的防御战线由 n扇防御门组成。每扇防御门包括一个运算op和一个参数t，其中运算一定是OR,XOR,AND中的一种，参数则一定为非负整数。如果还未通过防御门时攻击力为x，则其通过这扇防御门后攻击力将变为x op t。最终drd 受到的伤害为对方初始攻击力x依次经过所有n扇防御门后转变得到的攻击力。<br>由于atm水平有限，他的初始攻击力只能为0到m之间的一个整数（即他的初始攻击力只能在0,1,...,m中任选，但在通过防御门之后的攻击力不受 m的限制）。为了节省体力，他希望通过选择合适的初始攻击力使得他的攻击能让 drd 受到最大的伤害，请你帮他计算一下，他的一次攻击最多能使 drd 受到多少伤害。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行包含2个整数，依次为n,m，表示drd有n扇防御门，atm的初始攻击力为0到m之间的整数。接下来n行，依次表示每一扇防御门。每行包括一个字符串op和一个非负整数t，两者由一个空格隔开，且op在前，t在后，op表示该防御门所对应的操作， t表示对应的参数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行一个整数，表示atm的一次攻击最多使 drd 受到多少伤害。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 10<br>AND 5<br>OR 6<br>XOR 7</p>

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
<p>2&lt;=n&lt;=10^5<br>2&lt;=m&lt;=10^9<br>0&lt;=t&lt;=10^9</p>
</div>
</div>