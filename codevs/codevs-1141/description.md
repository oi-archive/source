<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">给定一个正整数</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">k(3</span><span style="">≤</span><span style="font-family: Courier New,monospace;">k</span><span style="">≤</span><span style="font-family: Courier New,monospace;">15),</span></span></span></span><span style="">把所有</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">k</span></span></span></span><span style="">的方幂及所有有限个互不相等的</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">k</span></span></span></span><span style="">的方幂之和构成一个递增的序列，例如，当</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">k=3</span></span></span></span><span style="">时，这个序列是：</span></p>
<p style=""><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">3</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">4</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">9</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">10</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">12</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">13</span></span></span></span><span style="">，…</span></p>
<p style=""><span style="">（该序列实际上就是：</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">3</span><sup><span style="font-family: Courier New,monospace;">0</span></sup></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">3</span><sup><span style="font-family: Courier New,monospace;">1</span></sup></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">3</span><sup><span style="font-family: Courier New,monospace;">0</span></sup><span style="font-family: Courier New,monospace;">+3</span><sup><span style="font-family: Courier New,monospace;">1</span></sup></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">3</span><sup><span style="font-family: Courier New,monospace;">2</span></sup></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">3</span><sup><span style="font-family: Courier New,monospace;">0</span></sup><span style="font-family: Courier New,monospace;">+3</span><sup><span style="font-family: Courier New,monospace;">2</span></sup></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">3</span><sup><span style="font-family: Courier New,monospace;">1</span></sup><span style="font-family: Courier New,monospace;">+3</span><sup><span style="font-family: Courier New,monospace;">2</span></sup></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">3</span><sup><span style="font-family: Courier New,monospace;">0</span></sup><span style="font-family: Courier New,monospace;">+3</span><sup><span style="font-family: Courier New,monospace;">1</span></sup><span style="font-family: Courier New,monospace;">+3</span><sup><span style="font-family: Courier New,monospace;">2</span></sup></span></span></span><span style="">，…）</span></p>
<p style=""><span style="">请你求出这个序列的第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">N</span></span></span></span><span style="">项的值（用</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">10</span></span></span></span><span style="">进制数表示）。</span></p>
<p style=""><span style="">例如，对于</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">k=3</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">N=100</span></span></span></span><span style="">，正确答案应该是</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">981</span></span></span></span><span style="">。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">只有</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span></span></span></span><span style="">行，为</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2</span></span></span></span><span style="">个正整数，用一个空格隔开：</span></p>
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>k N</span></span></span><span style=""><span style="">（</span></span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style=""><span style="font-family: Courier New,monospace;">k</span></span></span></span></span><span style=""><span style="">、</span></span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style=""><span style="font-family: Courier New,monospace;">N</span></span></span></span></span><span style=""><span style="">的含义与上述的问题描述一致，且</span></span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style=""><span style="font-family: Courier New,monospace;">3</span></span><span style=""><span style="">≤</span></span><span style=""><span style="font-family: Courier New,monospace;">k</span></span><span style=""><span style="">≤</span></span><span style=""><span style="font-family: Courier New,monospace;">15</span></span></span></span></span><span style=""><span style="">，</span></span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style=""><span style="font-family: Courier New,monospace;">10</span></span><span style=""><span style="">≤</span></span><span style=""><span style="font-family: Courier New,monospace;">N</span></span><span style=""><span style="">≤</span></span><span style=""><span style="font-family: Courier New,monospace;">1000</span></span></span></span></span><span style=""><span style="">）</span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="cjk" style="text-indent: 0.74cm; margin-top: 0.49cm; margin-bottom: 0.49cm; line-height: 0.64cm; widows: 2; orphans: 2;" align="LEFT"><span style="font-size: small;">为计算结果，是一个正整数(可能较大你懂的)</span><span style="font-size: small;">。（整数前不要有空格和其他符号）</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 100</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>981</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>