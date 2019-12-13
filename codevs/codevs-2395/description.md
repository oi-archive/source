<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小明的爸爸给他买了一盒玩具兵，其中有 K个步兵，K个骑兵和一个天兵，个个高大威猛，形象逼真。盒子里还有一个M*N棋盘，每个格子(i,j)都有一个高度H<sub>ij</sub>，并且大得足以容纳所有的玩具兵。小明把所有的玩具兵都放到棋盘上去，突然想到了一种很有趣的玩法：任意挑选T个不同的格子，并给每个格子i规定一个重要值R<sub>i­­</sub>，游戏的目标就是每次沿东南西北之一的方向把一个玩具兵移动到其相邻的格子中（但不能移动到棋盘外面去），最终使得每个挑选出的格子i上恰好有R<sub>i</sub>个玩具兵。小明希望所有的玩具兵都在某个选定的格子中，因此他总是使选出的T个格子的重要值之和等于玩具兵的个数。为了增加难度，小明给玩具兵们的移动方式做了一些规定：</p>
<p>●  步兵只会往高处爬，因此如果两个格子A和B相邻，当且仅当格子A的高度小于或等于B，步兵才可以从A移动到B。</p>
<ul>
<li>骑兵只会往低处跳，因此如果两个格子A和B相邻，当且仅当格子A的高度大于或等于B，骑兵才可以从A移动到B。</li>
<li>天兵技术全面，移动不受任何限制。</li>
</ul>
<p>       可是没玩几次，小明就发现这个游戏太难了，他常常玩了好半天也达不到目的。于是，他设计了一种“超能力”，每使用一次超能力的时候，虽然不能移动任何一个玩具兵，但可对它们进行任意多次交换操作，每次交换两个玩具兵。等这次超能力使用完后又可和平常一样继续移动这些玩具兵。借助强大的超能力，这个游戏是容易玩通的，但是怎样才能让使用超能力的次数最少呢？</p>
<p><strong> </strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含四个整数：M,N,K,T (2&lt;=M,N&lt;=100, 1&lt;=K&lt;=50, 1&lt;=T&lt;=2K+1)</p>
<p>    第二行包括2K+1个数对(x<sub>i</sub>,y<sub>i</sub>)，代表各个玩具兵的初始位置。前K个代表步兵，接下来的K个代表骑兵，最后一个代表天兵。</p>
<p>    第三行包含T个三元组(x<sub>i</sub>,y<sub>i</sub>,r<sub>i</sub>)，第i组代表第i个目标格的位置和重要值。</p>
<p>        以下M行，每行N个整数。其中第i行第j个数为即格子的高度H<sub>ij</sub>。高度是不超过100的正整数，注意：不同玩具兵的初始位置可能相同。输入数据保证无错，选定的T个格子的重要值之和保证等于2K+1。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一行，即使用超能力的最小次数T。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4  6  2  5</p>
<p>1  1     1  5     4  1     4  5     3  3</p>
<p>1  2  1    2  6  1    3  2  1    3  6  1    4  3  1</p>
<p>3  2  6  1  3  5</p>
<p>2  1  7  4  4  6</p>
<p>2  3  1  4  3  4</p>
<p>4  3  4  3  2  3</p>

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
<p>2&lt;=M,N&lt;=100, 1&lt;=K&lt;=50</p>
</div>
</div>