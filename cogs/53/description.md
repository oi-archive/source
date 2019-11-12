# 题目描述


<b><span style="font-size:large;">题目描述</span></b> 
<div>
DD 和好朋友们要去爬山啦！他们一共有<span> K 个人，每个人都会背一个包。这些包的容量是相同的，都是 V。可以装进背包里的一共有 N 种物品，每种物品都有给定的体积和价值。</span> 
</div>
<div>
在<span> DD 看来，合理的背包安排方案是这样的：</span> 
</div>
<ol start="1" type="1">
<li>
每个人背包里装的物品的总体积恰等于包的容量。
</li>
<li>
每个包里的每种物品最多只有一件，但两个不同的包中可以存在相同的物品。
</li>
<li>
任意两个人，他们包里的物品清单不能完全相同。
</li>
</ol>
<div>
在满足以上要求的前提下，所有包里的所有物品的总价值最大是多少呢？
</div>
<div>
<b><span style="font-size:large;">输入格式</span></b> 
</div>
<div>
第一行有三个整数：<span>K、V、N。</span> 
</div>
<div>
第二行开始的<span> N 行，每行有两个整数，分别代表这件物品的体积和价值。</span> 
</div>
<div>
<b><span style="font-size:large;">输出格式</span></b> 
</div>
<div>
只需输出一个整数，即在满足以上要求的前提下所有物品的总价值的最大值。
</div>
<div>
<b><span style="font-size:large;">样例输入</span></b> 
</div>
<pre style="margin:0cm 24pt 0.0001pt 24.05pt;background:#EEEEEE none repeat scroll 0% 0%;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">2 10 5</pre>
<pre style="margin:0cm 24pt 0.0001pt;background:#EEEEEE none repeat scroll 0% 0%;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">3 12</pre>
<pre style="margin:0cm 24pt 0.0001pt;background:#EEEEEE none repeat scroll 0% 0%;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">7 20</pre>
<pre style="margin:0cm 24pt 0.0001pt;background:#EEEEEE none repeat scroll 0% 0%;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">2 4</pre>
<pre style="margin:0cm 24pt 0.0001pt;background:#EEEEEE none repeat scroll 0% 0%;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">5 6</pre>
<pre style="margin:0cm 24pt 0.0001pt;background:#EEEEEE none repeat scroll 0% 0%;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">1 1</pre>
<div>
<b><span style="font-size:large;">样例输出</span></b> 
</div>
<pre style="margin:0cm 24pt 0.0001pt;background:#EEEEEE none repeat scroll 0% 0%;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">57</pre>
<div>
<b><span style="font-size:large;">样例说明</span></b> 
</div>
<div>
一种可以得到最优解的方案是：第一个人背体积为<span> 7、2、1 的三种物品，价值为 25。第二个人背体积为 3、7 的两种物品，价值为 32。总价值 57。</span> 
</div>
<div>
<b><span style="font-size:large;">数据范围</span></b> 
</div>
<div>
总人数<span> K&lt;=50。</span> 
</div>
<div>
每个背包的容量<span> V&lt;=5000。</span> 
</div>
<div>
物品种类数<span> N&lt;=200。</span> 
</div>
<div>
其它正整数都不超过<span> 5000。</span> 
</div>
<div>
输入数据保证存在满足要求的方案。
</div>
<p>
 
</p>
