<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Farmer John最近为奶牛们的图书馆添置了一个巨大的书架，尽管它是如此<br>的大，但它还是几乎瞬间就被各种各样的书塞满了。现在，只有书架的顶上还留<br>有一点空间。</p>
<p>所有N(1 &lt;= N &lt;= 20,000)头奶牛都有一个确定的身高H_i<br>(1 &lt;= H_i &lt;= 10,000)。设所有奶牛身高的和为S。书架的高度为B，并且保证<br>1 &lt;= B &lt;= S &lt; 2,000,000,007。</p>
<p>为了够到比最高的那头奶牛还要高的书架顶，奶牛们不得不象演杂技一般，<br>一头站在另一头的背上，叠成一座“奶牛塔”。当然，这个塔的高度，就是塔中<br>所有奶牛的身高之和。为了往书架顶上放东西，所有奶牛的身高和必须不小于书<br>架的高度。显然，塔中的奶牛数目越多，整座塔就越不稳定，于是奶牛们希望在<br>能够到书架顶的前提下，让塔中奶牛的数目尽量少。</p>
<p>现在，奶牛们找到了你，希望你帮她们计算这个最小的数目。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>* 第1行: 2个用空格隔开的整数：N 和 B</p>
<p>* 第2..N+1行: 第i+1行是1个整数：H_i</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>* 第1行: 输出1个整数，即最少要多少头奶牛叠成塔，才能够到书架顶部</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 40<br>6<br>18<br>11<br>13<br>19<br>11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>输入说明:</p>
<p>一共有6头奶牛，书架的高度为40，奶牛们的身高在6..19之间。</p>
<p>输出说明:</p>
<p>一种只用3头奶牛就达到高度40的方法：18+11+13。当然还有其他方法，在<br>此不一一列出了。</p>
</div>
</div>