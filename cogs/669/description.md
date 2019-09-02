# 题目描述


<h2 style="background-image:none;border-bottom:#aaaaaa 1px solid;padding-bottom:0.17em;line-height:28px;overflow-x:hidden;overflow-y:hidden;margin:0px 0px 0.6em;font-family:sans-serif;font-size:29px;font-weight:normal;padding-top:0.5em;background-clip:initial;background-origin:initial;">
<span id=".E6.8F.8F.E8.BF.B0" class="mw-headline">描述 [USACO 1.4.3]</span> 
</h2>
<p style="line-height:28px;margin:0.4em 0px 0.5em;font-family:sans-serif;font-size:19px;">
一个等差数列是一个能表示成a, a+b, a+2b,..., a+nb (n=0,1,2,3,...)的数列。
</p>
<p style="line-height:28px;margin:0.4em 0px 0.5em;font-family:sans-serif;font-size:19px;">
在这个问题中a是一个非负的整数，b是正整数。写一个程序来找出在双平方数集合(双平方数集合是所有能表示成p的平方 + q的平方的数的集合)S中长度为n的等差数列。
</p>
<h2 style="background-image:none;border-bottom:#aaaaaa 1px solid;padding-bottom:0.17em;line-height:28px;overflow-x:hidden;overflow-y:hidden;margin:0px 0px 0.6em;font-family:sans-serif;font-size:29px;font-weight:normal;padding-top:0.5em;background-clip:initial;background-origin:initial;">
<span id=".E6.A0.BC.E5.BC.8F" class="mw-headline"><br/>
格式</span> 
</h2>
<p style="line-height:28px;margin:0.4em 0px 0.5em;font-family:sans-serif;font-size:19px;">
<b>TIME LIMIT</b>: 5 秒
</p>
<p style="line-height:28px;margin:0.4em 0px 0.5em;font-family:sans-serif;font-size:19px;">
<b>PROGRAM NAME</b>: ariprog
</p>
<p style="line-height:28px;margin:0.4em 0px 0.5em;font-family:sans-serif;font-size:19px;">
<b>INPUT FORMAT</b>:
</p>
<p style="line-height:28px;margin:0.4em 0px 0.5em;font-family:sans-serif;font-size:19px;">
(file ariprog.in)
</p>
<p style="line-height:28px;margin:0.4em 0px 0.5em;font-family:sans-serif;font-size:19px;">
第一行: N(3&lt;= N&lt;=25),要找的等差数列的长度。
</p>
<p style="line-height:28px;margin:0.4em 0px 0.5em;font-family:sans-serif;font-size:19px;">
第二行: M(1&lt;= M&lt;=250),搜索双平方数的上界0 &lt;= p,q &lt;= M。
</p>
<p style="line-height:28px;margin:0.4em 0px 0.5em;font-family:sans-serif;font-size:19px;">
<br/>
<b>OUTPUT FORMAT</b>:
</p>
<p style="line-height:28px;margin:0.4em 0px 0.5em;font-family:sans-serif;font-size:19px;">
(file ariprog.out)
</p>
<p style="line-height:28px;margin:0.4em 0px 0.5em;font-family:sans-serif;font-size:19px;">
如果没有找到数列,输出`NONE&#39;。
</p>
<p style="line-height:28px;margin:0.4em 0px 0.5em;font-family:sans-serif;font-size:19px;">
如果找到了，输出一行或多行, 每行由二个整数组成:a,b。
</p>
<p style="line-height:28px;margin:0.4em 0px 0.5em;font-family:sans-serif;font-size:19px;">
这些行应该先按b排序再按a排序。
</p>
<p style="line-height:28px;margin:0.4em 0px 0.5em;font-family:sans-serif;font-size:19px;">
<br/>
所求的等差数列将不会多于10,000个。
</p>
<h2 style="background-image:none;border-bottom:#aaaaaa 1px solid;padding-bottom:0.17em;line-height:28px;overflow-x:hidden;overflow-y:hidden;margin:0px 0px 0.6em;font-family:sans-serif;font-size:29px;font-weight:normal;padding-top:0.5em;background-clip:initial;background-origin:initial;">
<span id="SAMPLE_INPUT" class="mw-headline"><br/>
SAMPLE INPUT</span> 
</h2>
<pre style="border-bottom:#2f6fab 1px dashed;border-left:#2f6fab 1px dashed;padding-bottom:1em;line-height:1.1em;padding-left:1em;padding-right:1em;border-top:#2f6fab 1px dashed;border-right:#2f6fab 1px dashed;padding-top:1em;border-image:initial;">5
7
</pre>
<h2 style="background-image:none;border-bottom:#aaaaaa 1px solid;padding-bottom:0.17em;line-height:28px;overflow-x:hidden;overflow-y:hidden;margin:0px 0px 0.6em;font-family:sans-serif;font-size:29px;font-weight:normal;padding-top:0.5em;background-clip:initial;background-origin:initial;">
<span id="SAMPLE_OUTPUT" class="mw-headline"><br/>
SAMPLE OUTPUT</span> 
</h2>
<pre style="border-bottom:#2f6fab 1px dashed;border-left:#2f6fab 1px dashed;padding-bottom:1em;line-height:1.1em;padding-left:1em;padding-right:1em;border-top:#2f6fab 1px dashed;border-right:#2f6fab 1px dashed;padding-top:1em;border-image:initial;">1 4
37 4
2 8
29 8
1 12
5 12
13 12
17 12
5 20
2 24</pre>
