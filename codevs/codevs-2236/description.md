<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在最后的诺曼底登陆战开始之前，盟军与德军的情报部门围绕着最终的登陆地点展开了一场规模空前的情报战。</p>
<p>这场情报战中，盟军的战术是利用那些潜伏在敌军内部的双重间谍，将假的登陆消息发布给敌军的情报机关的负责人。那些已经潜入敌后的间谍们都是盟军情报部的精英，忠实可靠；但是如何选择合适的人选，以及最佳的消息传递方法，才能保证假消息能够尽快而且安全准确地传递到德军指挥官们的耳朵里，成了困扰盟军情报部长的最大问题。他需要你的帮助。</p>
<p> </p>
<p>以下是情报部长提供的作战资料：</p>
<p> </p>
<p>在敌后一共潜伏着我方最优秀的N名间谍，分别用数字1, 2, …, N编号。在给定的作战时间内，任意两人之间至多只进行一次点对点的双人联系。</p>
<p>我将给你一份表格，表格中将提供任意两位间谍i和j之间进行联系的安全程度，用一个 [0, 1] 的实数S<sub>i j</sub>表示；以及他们这次联系时，能够互相传递的消息的最大数目，用一个正整数表示M<sub>i j</sub> (如果在表格中没有被提及，那么间谍i和j之间不进行直接联系)。</p>
<p>假消息从盟军总部传递到每个间谍手里的渠道也不是绝对安全，我们用 [0, 1] 的实数AS<sub>j</sub>表示总部与间谍j之间进行联系的安全程度，AM<sub>j</sub>则表示总部和间谍j之间进行联系时传递的消息的最大数目。对于不和总部直接联系的间谍，他的AM<sub>j</sub>=0（而表格中给出的他的AS<sub>j</sub>是没有意义的）。</p>
<p>当然，假消息从间谍手中交到敌军的情报部官员的办公桌上的过程是绝对安全的，也即是说，间谍与敌军情报部门之间要么不进行直接联系，要么其联系的安全程度是1（即完全可靠）。</p>
<p> </p>
<p>现在情报部打算把K条假消息“透露”到德军那里。消息先由总部一次性发给N名间谍中的一些人，再通过他们之间的情报网传播，最终由这N名间谍中的某些将情报送到德军手中。</p>
<p>对于一条消息，只有安全的通过了所有的中转过程到达敌军</p>
<p>次联系时，能够互相传递的消息的最大数目，用一个正整数表示M<sub>i j</sub> (如果在表格中没有被提及，那么间谍i和j之间不进行直接联系)。</p>
<p>假消息从盟军总部传递到每个间谍手里的渠道也不是绝对安全，我们用 [0, 1] 的实数AS<sub>j</sub>表示总部与间谍j之间进行联系的安全程度，AM<sub>j</sub>则表示总部和间谍j之间进行联系时传递的消息的最大数目。对于不和总部直接联系的间谍，他的AM<sub>j</sub>=0（而表格中给出的他的AS<sub>j</sub>是没有意义的）。</p>
<p>当然，假消息从间谍手中交到敌军的情报部官员的办公桌上的过程是绝对安全的，也即是说，间谍与敌军情报部门之间要么不进行直接联系，要么其联系的安全程度是1（即完全可靠）。</p>
<p> </p>
<p>现在情报部打算把K条假消息“透露”到德军那里。消息先由总部一次性发给N名间谍中的一些人，再通过他们之间的情报网传播，最终由这N名间谍中的某些将情报送到德军手中。</p>
<p>对于一条消息，只有安全的通过了所有的中转过程到达敌军情报部，这个传递消息的过程才算是安全的；因此根据乘法原理，它的安全程度P就是从总部出发，经多次传递直到到达德军那里，每一次传递该消息的安全程度的乘积。</p>
<p>而对于整个计划而言，只有当N条消息都安全的通过情报网到达德军手中，没有一条引起怀疑时，才算是成功的。所以计划的可靠程度是所有消息的安全程度的乘积。</p>
<p>显然，计划的可靠性取决于这些消息在情报网中的传递方法。</p>
<p>我需要一个方案，确定消息应该从哪些人手中传递到哪些人手中，使得最终计划的可靠性最大。</p>
<p> </p>
<p>你可以利用计算机，来求得这个最可靠的消息传递方案。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包括两个整数N和K，分别是间谍的总人数和计划包含的消息总数。</p>
<p>第二行包括2N个数，前N个数是实数AS<sub>1</sub>, AS<sub>2</sub>, …, AS<sub>N</sub>（范围在[0, 1]以内）；后N个数是整数AM<sub>1</sub>, AM<sub>1</sub>, …, AM<sub>N</sub>。</p>
<p>第三行包含了N个整数，其中第i（i = 1, 2, …, N）个整数如果为0表示间谍i与德军情报部不进行联系，如果为1则表示间谍与德军情报部进行联系。</p>
<p>第四行开始，每行包括4个数，依次分别是：代表间谍编号的正整数i和j，间谍i和j联系的安全性参数S<sub>i j</sub>（[0，1]范围内的实数），以及i、j之间传递的最大消息数 M<sub>i j</sub>（每一行的i均小于j ）。</p>
<p>最后的一行包含两个整数-1  -1，表示输入数据的结束。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>只有一行。这一行中包含一个实数P，给出的是整个计划的可靠程度P，保留5位有效数字（四舍五入）。</p>
<p>如果情报网根本不能将K条消息传到德军手中，那么计划的可靠性为0。</p>
<p>&nbsp;</p>
<p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6  13</p>
<p>0.9  0.7  0.8  0  0  0  2  6  8  0  0  0</p>
<p>0  0  0  1  0  1</p>
<p>1  4  0.5  2</p>
<p>2  3  0.9  5</p>
<p>2  5  0.8  2</p>
<p>2  6  0.8  7</p>
<p>3  5  0.8  2</p>
<p>5  6  0.8  4</p>
<p>-1  -1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0.00021184</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>0&lt;N&lt;300；0&lt;K&lt;300。</p>
<p>你可以假定，如果计划存在，那么它的可靠性大于1e-12</p>
</div>
</div>