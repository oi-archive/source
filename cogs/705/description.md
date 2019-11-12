# 题目描述


<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
<span class="mw-headline" id=".E6.8F.8F.E8.BF.B0">描述 USACO 2.4.4</span> 
</h2>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
现在是晚餐时间,而母牛们在外面分散的牧场中。 农民约翰按响了电铃,所以她们开始向谷仓走去。 你的工作是要指出哪只母牛会最先到达谷仓(在给出的测试数据中,总会有且只有一只最快的母牛)。 在挤奶的时候(晚餐前),每只母牛都在她自己的牧场上,一些牧场上可能没有母牛。 每个牧场由一条条道路和一个或多个牧场连接(可能包括自己)。 有时，两个牧场(可能是字母相同的)之间会有超过一条道路相连。 至少有一个牧场和谷仓之间有道路连接。 因此,所有的母牛最后都能到达谷仓,并且母牛总是走最短的路径。 当然,母牛能向着任意一方向前进,并且她们以相同的速度前进。 牧场被标记为&#39;a&#39;..&#39;z&#39;和&#39;A&#39;..&#39;Y&#39;,在用大写字母表示的牧场中有一只母牛,小写字母中则没有。 谷仓的标记是&#39;Z&#39;,注意没有母牛在谷仓中。
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
<br/>
<b>注意&#39;m&#39;和&#39;M&#39;不是同一个牧场</b> <b>否则错误</b> 上面的意思是说：输入数据中可能会同时存在M,m（郁闷ing)，比如
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
M a a m m z
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
<span class="mw-headline" id=".E6.A0.BC.E5.BC.8F"><br/>
格式</span> 
</h2>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
<b>PROGRAM NAME</b>: comehome
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
<b>INPUT FORMAT</b> 
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
第 1 行: 整数 P(1&lt;= P&lt;=10000),表示连接牧场(谷仓)的道路的数目。
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
第 2 ..P+1行: 用空格分开的两个字母和一个整数:
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
被道路连接牧场的标记和道路的长度(1&lt;=长度&lt;=1000)。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
<span class="mw-headline" id="SAMPLE_INPUT"><br/>
SAMPLE INPUT</span> 
</h2>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
(file comehome.in)
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#FFFFFF;line-height:1.1em;">5
A d 6
B d 3
C e 9
d Z 8
e Z 3
</pre>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
<b>OUTPUT FORMAT</b> 
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
单独的一行包含二个项目: 最先到达谷仓的母牛所在的牧场的标记,和这只母牛走过的路径的长度。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
<span class="mw-headline" id="SAMPLE_OUTPUT"><br/>
SAMPLE OUTPUT</span> 
</h2>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
(file comehome.out)
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#FFFFFF;line-height:1.1em;">B 11</pre>
