<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在《三体》系列中，一种十分重要的计算机科技就是自译解技术。自译解系统基于数学语言，可以将一种语言翻译成另一种语言。人类文明与三体文明、星舰文明与“魔戒”文明就是通过自译解系统沟通的。</p><p>（以下开始胡扯）</p><p>“蓝色空间”号与“万有引力”号广播了三体星系的坐标后，按预定计划向恒星<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">NH558J2</span>航行。途中他们收到了来自一艘光速飞船的不明信息。这些信息包括一个完整的自译解系统以及正文部分，但正文部分的信号几乎都是同时收到的。据关一帆博士猜测，可能这艘飞船发送信息时正在以低光速航行，但发送到正文部分时发现危险，进入光速航行，中途因不明原因被毁。现在科学家们想要分析这些信号可能的排列情况。</p><p><strong>科学家们已经通过自译解系统把信号转换成了那个文明的字母。那个文明共有n个字母，其中收到的第i个字母共在正文中出现ai次。求所有字母可能的排列数。<span style=""><em>因为科学家们很懒（呵呵，特别是丁仪和罗辑），所以你只要输出排列数对1000000007(它是一个质数)取余的结果即可。</em></span></strong><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，一个数n，表示字母数</p><p>第二至n+1行，每行一个数，第i+1(1&lt;=i&lt;=n的整数)行的数为ai，表示第i个字母出现的次数</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行一个数，表示<strong style="white-space: normal;"><strong style="white-space: normal;">所有字母</strong>可能的排列数</strong></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p><p>1</p><p>1</p><p>2</p><p>0</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>12<br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于数据1，ai均为1(1&lt;=i&lt;=n的整数)</p><p>对于数据2，n=5且1&lt;=ai&lt;=3(1&lt;=i&lt;=n的整数)</p><p>对于异于数据1与数据2的30%的数据，n&lt;=10且0&lt;=ai&lt;=5(1&lt;=i&lt;=n的整数)</p><p>对于100%的数据，n&lt;=1000且0&lt;=ai&lt;=1000(1&lt;=i&lt;=n的整数)</p>
</div>
</div>