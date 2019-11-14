<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>HURRICANE小组原来构建的网络由网络上的<span style="text-decoration: underline;">交换机</span>及其间的网路构成。<span style="text-decoration: underline;">交换机</span>分级连接，最高级的为顶级的网关<span style="text-decoration: underline;">交换机</span>，其他<span style="text-decoration: underline;">交换机</span>分级相连到该网关<span style="text-decoration: underline;">交换机</span>上。但值得注意的是，任一台非网关<span style="text-decoration: underline;">交换机</span>与一台高一级的交换机直接相连。而任一台<span style="text-decoration: underline;">交换机</span>均可以与几台低一级的<span style="text-decoration: underline;">交换机</span>直接相连。</p>
<p>但最近，由于原来架设的网络服务有限，需要把网络中的一些<span style="text-decoration: underline;">交换机</span>（包括网关交换机）升级为<span style="text-decoration: underline;">核心交换机</span>。由于改造的时间所限，只来得及把不超过<em>p</em>台（含<em>p</em>台）<span style="text-decoration: underline;">交换机</span>升级为<span style="text-decoration: underline;">核心交换机</span>，而所有剩下的交换机则需要通过改造网路的方法和这几台<span style="text-decoration: underline;">核心交换机</span>直接连接。</p>
<p>但是无论是升级<span style="text-decoration: underline;">交换机</span>还是改造网络都需要花费一定的资金。现在请你给出一个改造网络的方案。使得按照该方案升级后每一个<span style="text-decoration: underline;">交换机</span>要么是<span style="text-decoration: underline;">核心交换机</span>，要么直接和<span style="text-decoration: underline;">核心交换机</span>相连。并且要求提供的方案使改造所用的总费用最小。</p>
<p>你的程序必须根据给定的输入，给出符合题意的输出：</p>
<p>l  输入包括网络的拓扑结构，升级网络中每台<span style="text-decoration: underline;">交换机</span>的费用，以及改造网络的费用，还有可以升级的交换机的最大数目p；</p>
<p>l  你必须根据输入，找出一个升级的方案，满足升级后的<span style="text-decoration: underline;">核心交换机</span>的数目不超过给定的可升级交换机最大值<em>p</em>，且使得总费用最少；</p>
<p>l  其中总费用的计算包括两个部分：</p>
<p>n  一部分是升级<span style="text-decoration: underline;">交换机</span>为<span style="text-decoration: underline;">核心交换机</span>所需要的费用，该部分的费用按照所有的需要升级的<span style="text-decoration: underline;">交换机</span>所需的费用之和来计算；</p>
<p>n  另一部分是改造网络所需要的费用，该部分的费用按照所有未升级的<span style="text-decoration: underline;">交换机</span>到最近的<span style="text-decoration: underline;">核心交换机</span>的网络路径距离之和来计算；</p>
<p>n  <strong>注意：</strong>当网络中没有任何交换机升级到<span style="text-decoration: underline;">核心交换机</span>的时候，由于也没有<span style="text-decoration: underline;">交换机</span>可以连接到<span style="text-decoration: underline;">核心交换机</span>，所以我们定义此时的总费用为无穷大。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为两个正整数<em>n</em>（<em>n ≤ 4</em>00）和<em>p</em>，分别表示网络中<span style="text-decoration: underline;">交换机</span>的数目（交换机按照1到<em>n</em>标号）和可升级交换机的最大值。接下来的<em>n</em>行每行一个正整数<em>c<sub>i</sub></em>，表示把标号为<em>i</em>的<span style="text-decoration: underline;">交换机</span>升级为<span style="text-decoration: underline;">核心交换机</span>所需要的费用。</p>
<p>接下来的<em>n-</em>1行每行三个正整数<em>i</em>、<em>j</em>、<em>d<sub>i,j</sub></em>（<em>d<sub>ij</sub></em> &lt; 20000），表示编号为<em>j</em>的<span style="text-decoration: underline;">交换机</span>为编号为<em>i</em>的<span style="text-decoration: underline;">交换机</span>的上层<span style="text-decoration: underline;">交换机</span>，而<em>d<sub>i,j</sub></em>表示两台<span style="text-decoration: underline;">交换机</span>之间的网路距离。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>你的输出第一行为一个整数<em>M</em>，表示你的方案的最小总费用。接下来一行包括一个整数<em>p<sub>0</sub></em>，表示你的方案所需要升级为<span style="text-decoration: underline;">核心交换机</span>的<span style="text-decoration: underline;">交换机</span>数目。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7 2<br>7<br>1<br>7<br>7<br>7<br>1<br>2<br>2 1 2<br>3 2 4<br>6 5 2<br>7 5 9<br>5 1 3<br>4 1 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>30</p>
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><em>n ≤ 4</em>00</p>
</div>
</div>