<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>网络已经成为当今世界不可或缺的一部分。每天都有数以亿计的人使用网络 进行学习、科研、娱乐等活动。然而，不可忽视的一点就是网络本身有着庞大的 运行费用。所以，向使用网络的人进行适当的收费是必须的，也是合理的。 <br>MY 市 NS 中学就有着这样一个教育网络。网络中的用户一共有 2N个，编号 依次为 1, 2, 3, …, 2N。这些用户之间是用路由点和网线组成的。用户、路由点与 网线共同构成一个满二叉树结构。树中的每一个叶子结点都是一个用户，每一个 非叶子结点（灰色）都是一个路由点，而每一条边都是一条网线（见下图，用户 结点中的数字为其编号）。</p>
<p>MY 网络公司的网络收费方式比较奇特，称为“ 配对收费 ”。即对于每两个 用户 i, j (1≤i &lt; j ≤2N ) 进行收费。由于用户可以自行选择两种付费方式 A、B 中的一种，所以网络公司向学校收取的费用与每一位用户的付费方式有关。该费 用等于每两位不同用户配对产生费用之和。 <br>为了描述方便，首先定义这棵网络树上的一些概念： 祖先：根结点没有祖先，非根结点的祖先包括它的父亲以及它的父亲的祖先； 管辖叶结点：叶结点本身不管辖任何叶结点，非叶结点管辖它的左儿子所管 辖的叶结点与它的右儿子所管辖的叶结点； 距离：在树上连接两个点之间的用边最少的路径所含的边数。 <br>对于任两个用户 i, j (1≤i&lt;j≤2N )，首先在树上找到与它们距离最近的公共 祖先：路由点 P，然后观察 P 所管辖的叶结点（即用户）中选择付费方式 A 与 B 的人数，分别记为 nA 与 nB，接着按照网络管理条例第 X 章第 Y 条第 Z 款进行<span style="">收费（如下表），其中 Fi, j为 i 和 j 之间的流量，且为已知量。</span></p>
<p>由于最终所付费用与付费方式有关，所以 NS 中学的用户希望能够自行改变 自己的付费方式以减少总付费。然而，由于网络公司已经将每个用户注册时所选 择的付费方式记录在案，所以对于用户 i，如果他/她想改变付费方式（由 A 改为 B或由 B改为A），就必须支付Ci元给网络公司以修改档案（修改付费方式记录）。 现在的问题是，给定每个用户注册时所选择的付费方式以及 Ci，试求这些用 户应该如何选择自己的付费方式以使得 NS 中学支付给网络公司的总费用最少 （更改付费方式费用+配对收费的费用）。</p>
<p><span style=""><br></span></p>

<img src="/source/codevs/codevs-1787/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNzg3L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NTc3MjA2OS40MC4yNjE2Mzk5MTA3OTQucG5n.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件中第一行有一个正整数 N。 第二行有 2<sup>N</sup>个整数，依次表示 1 号，2 号，…，2N号用户注册时的付费方式， 每一个数字若为 0，则表示对应用户的初始付费方式为 A，否则该数字为 1，表 示付费方式为 B。 第三行有 2<sup>N</sup>个整数，表示每一个用户修改付费方式需要支付的费用，依次为 C1, C2, …,CM 。( M=2<sup>N</sup> ) 以下 2N-1 行描述给定的两两用户之间的流量表 F，总第(i + 3)行第 j 列的整 数为 Fi, j+i 。（1≤i&lt;2<sup>N</sup>，1≤j≤2<sup>N</sup> – i） 所有变量的含义可以参见题目描述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>你的程序只需要向输出文件输出一个整数，表示 NS 中学支付给网络公司的 最小总费用。（单位：元）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>1 0 <span style="">1 0</span></p>
<p>2 2 <span style="">10 9 </span></p>
<p>10 1 2</p>
<p>2 1</p>
<p>3</p>
<p><span style=""><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>将 1 号用户的付费方式由 B 改为 A，NS 中学支付给网络公司的费用达到最 小。</p>
<p>40%的数据中 N≤4；</p>
<p>80%的数据中 N≤7；</p>
<p>100%的数据中 N≤10，0≤Fi, j≤500，0≤Ci≤500 000。 </p>
</div>
</div>