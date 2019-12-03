<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>FJ的农场内种有若干种（不超过26）植物，每种植物用一个大写字母来表示。FJ非常喜欢等<span style="">腰直角三角形，因此他想统计自己的农场内有多少个由同种植物构成等腰直角三角形。方阵中的</span><span style="">等腰直角三角形只有下面两种情况：</span></p><p>（i） 两条直角边分别跟方阵的边平行，例如：</p><p>ＡＡＡ　　Ｂ</p><p>ＡＡ　　　ＢＢ</p><p>Ａ　　　　ＢＢＢ ……。</p><p>（ii） 等腰直角三角形的斜边与方阵的边平行，例如：</p><p>　　Ａ　　　　Ｂ</p><p>　ＡＡＡ　　　ＢＢ</p><p>ＡＡＡＡＡ　　ＢＢＢ</p><p>　　　　　　　ＢＢ</p><p>　　　　　　　Ｂ……。</p><p>每个等腰直角三角形都不能少于3个字母。</p><p>（注意题目没说清楚的坑点(大三角形里包含的小三角形也算)，懒得说清楚-.-）</p><p>那个3620是我同学发的，AC了这道可以顺便过去刷一刷</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">第一行：N。 </p><p style="">第二至第N+1行：N个大写字母，中间没有空格。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="white-space: normal;"><span style="font-size: 16px;">第一行一个整数，等腰直角三角形的个数。</span><br/></p><p style="white-space: normal;">对每种植物，求出由它所组成的等腰直角三角形的个数，并按照字典顺序逐行输出。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 </p><p>AAB </p><p>ABB </p><p>BBC</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">4 </span><br></p><p>A 1 </p><p>B 3 </p><p>C 0</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1≤N≤600</p>
</div>
</div>