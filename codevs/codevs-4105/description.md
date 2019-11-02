<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">saffah</span><span style="">喜欢打地鼠！</span></p><p style=""><span style="">一共有</span><span style="">n</span><span style="">只地鼠按照顺序出现，第</span><span style="">i</span><span style="">只地鼠的肥胖度为</span><span style="">a[i]</span><span style="">。每次</span><span style="">saffah</span><span style="">可以打地鼠，但是要保证之前没打过任何地鼠，或这只地鼠比之前的任何一只</span><span style="">saffah</span><span style="">打过的地鼠都要肥。</span></p><p style=""><span style="">当然题目没有这么简单。如果</span><span style="">saffah</span><span style="">没有打完所有地鼠，那么剩下的地鼠将会再次出现（来被</span><span style="">saffah</span><span style="">打）。当然，地鼠不是傻子，如果自己出现了</span><span style="">t</span><span style="">次以后还没被打死，那么就不会再出现了。</span></p><p style=""><span style="">现在问，</span><span style="">saffah</span><span style="">最多能打多少地鼠？</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行包含</span><span style="">4</span><span style="">个整数</span><span style="">k n max t</span><span style="">。分别表示数据组数，地鼠个数，</span><span style="">a[i]</span><span style="">的最大值，每个地鼠出现的最大次数。</span></p><p style=""><span style="">接下来</span><span style="">k</span><span style="">行，每行表示一组数据，包含</span><span style="">n</span><span style="">个整数，代表</span><span style="">a[1]</span><span style="">到</span><span style="">a[n]</span><span style="">。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent: 32px;">对于每组数据输出saffah最多能打到的地鼠个数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Courier New';">3 3 5 2</span></p><p style=""><span style="font-family: 'Courier New';">3 2 1</span></p><p style=""><span style="font-family: 'Courier New';">1 2 3</span></p><p style=""><span style="font-family: 'Courier New';">2 3 1</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Courier New';">2</span></p><p style=""><span style="font-family: 'Courier New';">3</span></p><p style=""><span style="font-family: 'Courier New';">3</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">对于</span><span style="">30%</span><span style="">的数据，</span><span style="">n*t≤1,000</span><span style="">。</span></p><p style=""><span style="">对于</span><span style="">60%</span><span style="">的数据，</span><span style="">n*t≤100,000</span><span style="">。</span></p><p style=""><span style="">对于</span><span style="">80%</span><span style="">的数据，</span><span style="">n*max≤100,000</span><span style="">。</span></p><p style=""><span style="">对于</span><span style="">100%</span><span style="">的数据，</span><span style="">1≤k≤10,1≤n,max≤10^5,1≤t≤10^9,n*max≤20,000,000</span><span style="">。</span></p><p><br></p>
</div>
</div>