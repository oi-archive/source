<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">现在有</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>1</strong></span></span></span><span style="">把大锁，由</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>n</strong></span></span></span><span style="">个开关控制，现在开关都在开的状态。解锁的方法是这样的：第</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>1</strong></span></span></span><span style="">次，从</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>1</strong></span></span></span><span style="">开始，每隔</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>0</strong></span></span></span><span style="">个开关（其实就是每个开关）改变开关的状态（开的变成关的，关的变成开的）；第</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>2</strong></span></span></span><span style="">次，从</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>1</strong></span></span></span><span style="">开始，每隔</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>1</strong></span></span></span><span style="">个开关（就是</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>1,3,5,7(</strong></span></span></span>每次加<span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>2</strong></span><span style=""><strong>)</strong></span><span style=""><span style=""><strong>…</strong></span></span></span></span><span style="">这样下去）改变开关的状态；第</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>3</strong></span></span></span><span style="">次，从</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>1</strong></span></span></span><span style="">开始，每隔</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>2</strong></span></span></span><span style="">个开关（就是</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>1,4,7,10(</strong></span></span></span>每次加<span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>3</strong></span><span style=""><strong>)</strong></span><span style=""><span style=""><strong>…</strong></span></span></span></span><span style="">这样下去）改变开关的状态</span><span style=""><strong>……</strong></span><span style="">第</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>n</strong></span></span></span><span style="">次，从</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>1</strong></span></span></span><span style="">开始，每隔</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>n-1</strong></span></span></span><span style="">个开关（就是</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>1,n+1,2n+1,3n+1(</strong></span></span></span>每次加<span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>n)</strong></span><span style=""><span style=""><strong>…</strong></span></span></span></span><span style="">这样下去）改变开关的状态。所有开关最后的状态，将开转化为</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>0</strong></span></span></span><span style="">，关转化为</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>1</strong></span></span></span><span style="">后，就是大锁的解锁密码。现在输入</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>n</strong></span></span></span><span style="">，求解锁密码。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">一个数</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>n</strong></span></span></span><span style="">（</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>n&lt;=1000</strong></span></span></span><span style="">）</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-left: 0.85cm; margin-bottom: 0cm;"><span style="font-size: small;">一个含有</span><span style="font-family: Calibri,sans-serif;"><span lang="en-US"><span style="font-size: small;"><strong>n</strong></span></span></span><span style="font-size: small;">个字符的串即密码</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入样例</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>1</strong></span></span></span></p>
<p style=""><span style="font-family: Calibri,sans-serif;"><span style=""><span><strong>3</strong></span></span></span></p>
<p style=""><span style="">输入样例</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>2</strong></span></span></span></p>
<p style=""><span style="font-family: Calibri,sans-serif;"><span style=""><span><strong>4</strong></span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输出样例</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>1</strong></span></span></span></p>
<p style=""><span style="font-family: Calibri,sans-serif;"><span style=""><span><strong>110</strong></span></span></span></p>
<p style=""> </p>
<p style=""><span style="">输出样例</span><span style="font-family: Calibri,sans-serif;"><span><span style=""><strong>2</strong></span></span></span></p>
<p style=""> </p>
<p style=""><span style="font-family: Calibri,sans-serif;"><span style=""><span><strong>0100</strong></span></span></span></p>
<p style=""><span style="font-family: Calibri,sans-serif;"><span style=""><span><strong><br></strong></span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>详见试题</p>
</div>
</div>