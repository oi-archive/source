<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　麻将是个风靡亚洲的游戏。麻将有下面这样的牌，每种牌最多4张：<br><img height="57" src="/source/codevs/codevs-2005/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9OUFtSDRKNDY=.do" width="457">　　我们分别用1m,2m,3m,…,9m来表示这些牌。<br><img height="63" src="/source/codevs/codevs-2005/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9RTNOOEZHOVE=.do" width="454">　　我们分别用1s,2s,3s,…,9s来表示这些牌。<br><img height="62" src="/source/codevs/codevs-2005/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9Z2VqZ0gzWVQ=.do" width="459">　　我们分别用1p,2p,3p,..,9p来表示这些牌。<br><img height="63" src="/source/codevs/codevs-2005/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ckVUVGZhRDU=.do" width="357">　　我们分别用1c,2c,3c,…,7c来表示这些字牌。<br>　　一个一般的胜利状态是指一个14张牌的集合，包含一对相同的牌（例：2s,2s或4c,4c），和四组牌，每组牌包含3张牌，要么是3张相同的牌（例：6m,6m,6m或2c,2c,2c），要么是三张连续的同种类的非字牌(例：4m,5m,6m或1p,2p,3p)。<br>　　还有两种特殊的胜利状态。第一种是“七对子”，即7个组，每组为一对相同的牌，不同组的牌不能相同（例：1m,1m,2m,2m,4m,4m,5m,5m,6c,6c,1s,1s是一个可行的方案，而1m,1m,2m,2m,4m,4m,5m,5m,2m,2m,1s,1s则不是，因为有一组牌相同了）。<br>　　第二种是“国士无双”，指1m,9m,1s,9s,1p,9p,1c,2c,3c,4c,5c,6c,7c各一张，再加上一张任意的之前提到的13张牌中的一张（例：1m,9m,1s,9s,1p,9p,1c,2c,3c,4c,5c,6c,7c,9p）即为一个胜利状态。<br>　　现在，已知有N张牌，每种牌的数量不会超过4张，求天和(即拿14张牌，这14张牌恰好是胜利状态)的概率。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　多组数据。对于每个测试点，第一行有一个数T，表示共T组数据。对于每组数据，第一行一个数N，接下来一行包含N个字符串，表示N张牌。具体参见样例。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　对于每组数据，输出一行，以最简分数形式表示所求的天和的概率。分子分母间用字母&rsquo;/&rsquo;分割（不含引号）。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>4</span><br><span>14</span><br><span>1s 2s 3s 2c 2c 2c 2p 3p 4p 5m 6m 7m 1p 1p</span><br><span>14</span><br><span>1s 2s 3s 2c 2c 2c 2p 3p 4p 5m 6m 7m 1p 2p</span><br><span>25</span><br><span>1m 1m 9m 9m 1s 1s 9s 9s 1p 1p 9p 9p 1c 1c 2c 2c 3c 3c 4c 4c 5c 5c 6c 6c 7c</span><br><span>27</span><br><span>1m 1m 1m 2m 2m 2m 3m 3m 3m 4m 4m 4m 5m 5m 5m 6m 6m 6m 7m 7m 7m 8m 8m 8m 9m 9m 9m</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>1/1</span><br><span>0/1</span><br><span>1057/185725</span><br><span>44171/371450</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>　　对于40%的数据，N&lt;=25。</span><br><span>　　对于100%的数据，数据组数T不超过10组，14&lt;=N&lt;=136。</span></p>
<p><span><br></span></p>
<p><span>来源：<span>中国国家队清华集训 2012-2013 第三天</span></span></p>
</div>
</div>