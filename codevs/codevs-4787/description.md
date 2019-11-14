<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>hfz经过仔细的筛选，终于选出了最好的妹子树种子。他种下了这颗种子，长出了一颗茁壮的妹子树，终于到了收获的季节。</p><p>由于某些奇怪的原因，hfz每次需要同时找到两个妹子（QAQ），但是由于妹子是一种很奇怪的生物，她们总是手拉手形成一条链，所以hfz想要泡两个妹子，就要把连接她们的路径上的所有妹子全部泡到，当然泡妹子是需要软妹币的啦，hfz可是很穷的（雾）。<br>由于hfz疏于管理他的妹子树，这个妹子树长成了一片妹子森林（QAQ），但妹子们是会感到孤独的，有时候两个妹子会成为新的朋友啦。</p><p>hfz很苦恼，他不知道他应该泡哪对妹子，他需要提前知道泡她们的代价。于是他请yql帮忙，yql当然会辣，他想考考你。<br></p><p>支持两种操作Q u v：询问泡u和v的最小代价，保证u和v联通<br>                    L u v：连接u和v，保证u和v之前不联通。</p><p>我要强制在线QAQ：</p><p>每次读入的u和v实际上应当是u^lastans和v^lastans,lastans是上一次的答案，一开始为0<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是一个正整数n，表示一共有n个妹子，从1开始编号。<br>下面一行n个正整数Vi，Vi表示泡第i个妹子的代价。<br>然后是n行，每行给出两个1到n的数u和v，表示u和v之间有一条边，若u为0，则代表v是根节点。<br>接下来一个正整数m，表示共m次操作。<br>以下m行每行一个操作，格式见上。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每一个询问操作输出一个数，表示同时泡的最小代价，每行一个数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br>1 2 3<br>0 1<br>0 2<br>3 2<br>4<br>Q 2 3<br>L 7 4<br>Q 4 7<br>Q 2 0<br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5<br>3<br>6<br><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，保证1&lt;=n&lt;=3000,1&lt;=m&lt;=5000</p><p>对于70%的数据，保证1&lt;=n&lt;=30000,1&lt;=m&lt;=50000</p><p>对于90%的数据，保证1&lt;=n&lt;=100000,1&lt;=m&lt;=100000<br></p><p>对于100%的数据，保证:1&lt;=n&lt;=100000,1&lt;=m&lt;=200000,1&lt;=Vi&lt;=1000</p>
</div>
</div>