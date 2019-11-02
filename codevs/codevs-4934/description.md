<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="font-family: 'Arial Unicode MS','sans-serif';">hke</span><span style="">有一天学会了循环语句，感到很神奇。回到家，他用</span><span style="font-family: 'Arial Unicode MS','sans-serif';">c++</span><span style="">写下这段代码：</span></p><p>void work()</p><p>{</p><p><span style=""></span>  ans=0;</p><p><span style=""></span>    for(a[1]=1;a[1]&lt;=n;++a[1])</p><p><span style=""></span>      for(a[2]=1;a[2]&lt;a[1];++a[2])</p><p><span style=""></span>        for(a[3]=1;a[3]&lt;a[2];++a[3])</p><p><span style=""></span>          ......</p><p><span style=""></span>            for(a[k]=1;a[k]&lt;a[k-1];++a[k])</p><p><span style=""></span>              ans+=f(q);</p><p><span style=""></span> cout&lt;&lt;ans;</p><p>}</p><p style=""><span style="">其中，<span style="font-family: arial, helvetica, sans-serif;">q</span>是给定的常数，</span><span style="font-family: 'Arial Unicode MS','sans-serif';">f(x)</span><span style="">是一个关于</span><span style="font-family: 'Arial Unicode MS','sans-serif';">x</span><span style="">的</span><span style="font-family: 'Arial Unicode MS','sans-serif';">m</span><span style="">次多项式，它的表达式为</span></p><p style=""><span style="font-family: 'Arial Unicode MS','sans-serif';">f(x)=b<sub>m</sub>x<sup>m</sup>+b<sub>m-1</sub>x<sup>m-1</sup>+……+b<sub>1</sub>x+b<sub>0</sub></span></p><p style=""><span style="font-family: 'Arial Unicode MS','sans-serif';">hke</span><span style="">迫不及待地开始运行这个程序，但程序运行得实在太慢了。于是他找到了你，想知道这段程序输出的结果是？答案可能很大，你只需输出其对</span><span style="font-family: 'Arial Unicode MS','sans-serif';">10<sup>9</sup>+7</span><span style="">取模的结果即可。假设运算过程中不存在溢出。</span></p><p style=""><span style=""><br></span></p><p style=""><span style="">（5.30upd: QAQ出题人的标称中q打成了int……现在已经改成long long并重新生成数据了，在此对之前WA的几位表示深深地歉意qwqqqqqqq）</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行</span><span style="font-family: 'Arial Unicode MS','sans-serif';">4</span><span style="">个正整数，分别为</span><span style="font-family: 'Arial Unicode MS','sans-serif';">n,m,k,q</span><span style="font-family: 'Arial Unicode MS','sans-serif';">；</span></p><p style=""><span style="">第二行</span><span style="font-family: 'Arial Unicode MS','sans-serif';">m+1</span><span style="">个正整数，分别为</span><span style="font-family: 'Arial Unicode MS','sans-serif';">b<sub>0</sub>,b<sub>1</sub>,b<sub>2</sub>……b<sub>m</sub></span><sub><span style="font-family: 'Arial Unicode MS','sans-serif';">；</span></sub></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:32px"><span style="font-size:16px;font-family:宋体">一个数，表示程序运行结果对</span><span style="font-size:16px;font-family:&#39;Arial Unicode MS&#39;,&#39;sans-serif&#39;">10<sup>9</sup>+7</span><span style="font-size:16px;font-family:宋体">取模的结果。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Arial Unicode MS','sans-serif';">10 3 3 2</span></p><p style=""><span style="font-family: 'Arial Unicode MS','sans-serif';">1 3 3 1</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Arial Unicode MS','sans-serif';">3240</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Arial Unicode MS','sans-serif';">100%</span><span style="">的数据保证</span><span style="font-family: 'Arial Unicode MS','sans-serif';">n</span><span style="font-family: 'Arial Unicode MS','sans-serif';">≤500000，m≤500000，1≤k≤n，q≤10<sup>18</sup>，1≤b<sub>i</sub>≤100000</span></p><p><br></p>
</div>
</div>