<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>     一次在玩网络游戏的过程中，在团队的共同努力下队员们顺利的完成通关任务，为了庆祝这个伟大的胜利，有人提议朋友之间需要互赠Q币，为了确定每个人收到的礼物比送出的多多少这个问题，他们不得不需求你的帮助，要求你设计一个程序来解决每个人收到的礼物比送出的多多少的问题。 在这一个问题中，每个人都准备了一些Q币来赠送，而这些Q币将会被平均分给那些将收到他的Q币的人。 然而，在任何一群朋友中，有些人将送出较多的Q币(可能是因为有较多的朋友)，有些人有准备了较多的Q币。</p>
<p>给出一群队友名单，但没有人的名字会长于 14 字符，给出每个人将送出的Q币，和将收到他的Q币的人的列表，请确定每个人收到的比送出的Q币多的数目。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第 1 行：人数N(2≤N≤10)。</p>
<p>第 2到 N+1 行:这N个在组里人的名字，一个名字一行。</p>
<p>第N＋2到最后：</p>
<p>这里的N段内容是这样组织的：</p>
<p>第一行是将会送出Q币人的名字。</p>
<p>第二行包含二个数字:　第一个是原有的Q币数目（在0到2000的范围里），第二个数值是将收到这个送Q币的人的个数 如果该数值是非零的, 在下面数值行列出礼物的接受者的名字，一个名字一行。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出 N 行。</p>
<p>每行是一个的名字加上空格再加上收到的比送出的Q币多的数目。</p>
<p>对于每一个人，他名字的打印顺序应和他在输入的2到N＋1行中输入的顺序相同。所有的送礼的钱都是整数。</p>
<p>每个人把相同数目的Q币给每位要送礼的朋友，而且尽可能多给，不能给出的Q币被送礼者自己保留。</p>

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
<p>dave</p>
<p>laura</p>
<p>owen</p>
<p>vick</p>
<p>amr</p>
<p>dave</p>
<p>200 3</p>
<p>laura</p>
<p>owen</p>
<p>vick</p>
<p>owen</p>
<p>500 1</p>
<p>dave</p>
<p>amr</p>
<p>150 2</p>
<p>vick</p>
<p>owen</p>
<p>laura</p>
<p>0 2</p>
<p>amr</p>
<p>vick</p>
<p>vick</p>
<p>0 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>dave 302</p>
<p>laura 66</p>
<p>owen -359</p>
<p>vick 141</p>
<p>amr –150</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>解决方法：直叙模拟。根据题意和样例数据分析。首先读入n个需要互赠Q币的队友，然后依次读入这n个人的姓名，从n+1行开始至最后一共有n组数据，每一组数据的第一行表示需要送礼者的名字，第二行是送礼者的所拥有的Q币的数量（变量money_to_give）,和需要赠送的人数（变量n_receive），接下来的m行为礼物接收者的名单。从题意结果可以看出，可以用记录性描述送Q币者属性：name（姓名)、account（自己所拥有的Q币）、received（收到的Q币）和remain(自己保留的Q币)。</p>
<p>在理解题意后较为简单，在完成数据的读入过程中，直接模拟赠与过程。需要考虑一下几种情况：</p>
<p>（1）       赠送者没有Q币可以赠送，则不实施赠送方法，对后面获赠者不处理；</p>
<p>（2）       赠送者有Q币但没有获赠对象，则所拥有的钱自己保留；</p>
<p>（3）       赠送者既没有Q币又没有赠送对象，则不实施赠送方法；</p>
<p>（4）       赠送者既有Q币又有赠送对象，则按照题意尽可能的实行整数赠送，实施赠送办法；</p>
<p>输出者较为简单，输出要求按照读入姓名的顺序输出，顺序打印记录型数组a的属性received（收到的Q币）减掉account（自己所拥有的Q币）和remain(自己保留的Q币)的差值即可。</p>
</div>
</div>