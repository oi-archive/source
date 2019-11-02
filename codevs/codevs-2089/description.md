<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    小T最近在学着买股票，他得到内部消息：F公司的股票将会疯涨。 <br>    股票每天的价格已知是正整数，并且由于客观上的原因，最多只能为N。在疯涨的K天中小T观察到：除第一天外每天的股价都比前一天高，且高出的价格（即当天的股价与前一天的股价之差）不会超过M，M为正整数。并且这些参数满足M(K-1)&lt;N。 <br>    小T忘记了这K天每天的具体股价了，他现在想知道这K天的股价有多少种可能。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件只有一行用空格隔开的四个数：N、K、M、P。对P的说明参见后面“输出格式”中对P的解释。 <br>输入保证20%的数据M,N,K,P≤20000，保证100%的数据M,K,P≤10<sup>9</sup>，N≤10<sup>18</sup>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一个数，表示这 K 天的股价的可能种数对于 P 的模值。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7 3 2 997</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>16 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>输出样例的16表示输入样例的股价有16种可能： <br>{1，2，3}，{1，2，4}，{1，3，4}，{1，3，5}， <br>{2，3，4}，{2，3，5}，{2，4，5}，{2，4，6}， <br>{3，4，5}，{3，4，6}，{3，5，6}，{3，5，7}， <br>{4，5，6}，{4，5，7}，{4，6，7}，{5，6，7}。</p>
</div>
</div>