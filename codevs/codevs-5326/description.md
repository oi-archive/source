<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">经过不懈的努力，Hzwer召唤了很多陨石。已知Hzwer的地图上共有n个区域，且一开始的时候第i个陨石掉在了第i个区域。有电力喷射背包的ndsf很自豪，他认为搬陨石很容易，所以他将一些区域的陨石全搬到了另外一些区域。</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">在ndsf愉快的搬运过程中，Hzwer想知道一些陨石的信息。对于Hzwer询问的每个陨石i，你必须告诉他，在当前这个时候，i号陨石在所在区域x、x区域共有的陨石数y、以及i号陨石被搬运的次数z。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">输入的第一行是一个正整数T。表示有多少组输入数据。</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">接下来共有T组数据，对于每组数据，第一行包含两个整数：N和Q。</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">接下来Q行，每行表示一次搬运或一次询问，格式如下：</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">T A B：表示搬运，即将所有在A号球所在地区的陨石都搬到B号球所在地区去。</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">Q A：悟空想知道Ａ号陨石的x，y，z。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &#39;Helvetica Neue&#39;, &#39;Trebuchet MS&#39;, Helvetica, &#39;Microsoft YaHei&#39;, Georgia, &#39;sans Microsoft YaHei&#39;, sans-serif; font-size: 16px; line-height: 25.59375px; background-color: rgb(255, 255, 255);">对于第ｉ组数据，第一行输出“Case i：”接下来输出每一个询问操作的x，y，z，每一个询问操作的答案占一行。每组数据之间没有空行。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">2</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">3 3</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">T 1 2</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">T 3 2</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">Q 2</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">3 4</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">T 1 2</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">Q 1</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">T 1 3</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">Q 1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">Case 1：</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">2 3 0</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">Case 2：</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">2 2 1</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">3 3 2</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">20%的数据保证：0≤T≤20，2＜N＜＝100，2＜Q＜＝100。</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">100%的数据保证：0≤T≤100，2＜N＜＝10000，2＜Q＜＝10000。</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">对于所有数据保证搬运操作中AB在Ｎ的范围内且所在区域不相同。</p><p><br></p>
</div>
</div>