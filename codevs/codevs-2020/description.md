<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Nimo 是小镇上最出色的木偶剧演员。他经常带着自己的木偶们在附近的镇上演出。<br>为了方便起见，我们给每个木偶设定一个特征值 i p ，每个木偶都有一个原装的提线，<br>提线的特征值和木偶是相等的，即也为i p 。<br>当一个木偶和一个提线的特征值相差超过 1 时，提线将不能组装到木偶上。<br>现在木偶和提线被 Nimo 不小心全部打乱了，Nimo 决定对这些木偶和提线重新配对。<br>他采取这样的策略：每次拿出一个木偶，再在未配对的提线里面随机抽一个可以组装到<br>这个木偶上的提线，将它们配对，如果当前木偶没有可以配对的提线，Nimo 将扔掉这个木<br>偶。<br>现在他想知道的是，在最坏情况下，他最多会扔掉多少个木偶。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>测试文件中包含若干个测试点。<br>每个测试点包含两行。第一行包含一个整数 N ，表示有N 个木偶。<br>接下来一行 N 个整数，第i 个整数i p ，表示第i 个木偶及其原装提线的特征值。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行一个整数，表示最多可能扔掉多少个木偶。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br>1 2 3<br>8<br>1 2 3 3 4 2 5 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1<br>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于10% 的数据，满足1 &lt;= N &lt;= 10。<br>对于 20% 的数据，满足1 &lt;= N &lt;= 20。<br>对于 100% 的数据，满足1 &lt;= N &lt;= 50，    i p 。</p>
</div>
</div>