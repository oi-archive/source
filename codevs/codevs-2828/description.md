<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    有一枚硬币，抛出正面H的概率为a/b，抛出反面T的概率为 1-a/b。现在TT小朋友开始玩丢硬币的游戏，并且把每次抛出的结果记录下来，正面记为H，反面记为T，于是她得到了一个抛硬币序列HTHHT…。她突然想到一个问题：在抛出正面和反面概率都是 1/2 的情况下，要使得抛出的序列出现目标序列HT，期望要抛多少次。然而经过 1 秒的思考以后她发现，若第一次抛出的是T，那么还需要期望抛出HT的次数，如果第一次抛出的是H，则期望只需要抛出T的次数，而期望抛出T的次数显然是 2。她设抛出HT的期望次数是x，则得到了方程：</p>
<p>x=1+(1/2*x+1/2*2)</p>
<p>解得 x=4，所以抛出 HT 的期望次数是 4 次。</p>
<p>    她在解决了这个弱化很多的问题以后，开始思考对于一般情况下，抛出正反面的概率不一定相同，且抛出的目标序列不一定为HT时需要的期望步数。然而经过很长一段时间的苦思冥想仍然无果，于是她开始求助于你。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个数 a,b。意义如题目描述。 <br> 接下来 1 行一个只包含’H’和’T’的字符串 S。表示要抛出的目标序列。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出仅一行 p/q，其中 p 和 q 均为正整数且互质，表示抛出目标序列 S 所需要的期望步数。 <br />注意，若q为 1 时，不省略/1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 2 <br>HT</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4/1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>a b |S| <br>1 =1 =2 =3 <br>2 =1 =2 =3 <br>3 =1 =2 ≤10 <br>4 =1 =2 ≤20 <br>5 &lt;b ≤10 ≤15 <br>6 &lt;b ≤30 ≤50 <br>7 &lt;b ≤50 ≤100 <br>8 &lt;b ≤100 ≤300 <br>9 &lt;b ≤100 ≤500 <br>10 &lt;b ≤100 ≤1000</p>
</div>
</div>