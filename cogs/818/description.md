# 题目描述


<dt style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;margin:0px;padding:0px;font-size:16px;font-weight:bold;line-height:56px;color:#231F17;white-space:normal;">
描述
</dt>
<dd style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;margin:0px;padding:0px;color:#231F17;line-height:22px;white-space:normal;">
<p style="margin-top:15px;margin-bottom:15px;padding:0px;">
通向自由的钥匙被放n个房间里，这n个房间由n-1条走廊连接。但是每个房间里都有特别的保护魔法，在它的作用下，我无法通过这个房间，也无法取得其中的钥匙。虽然我可以通过消耗能量来破坏房间里的魔法，但是我的能量是有限的。那么，如果我最先站在1号房间（1号房间的保护魔法依然是有效的，也就是，如果不耗费能量，我无法通过1号房间，也无法取得房间中的钥匙），如果我拥有的能量为P，我最多能取得多少钥匙？
</p>
</dd>
<dt style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;margin:0px;padding:0px;font-size:16px;font-weight:bold;line-height:56px;color:#231F17;white-space:normal;">
输入
</dt>
<dd style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;margin:0px;padding:0px;color:#231F17;line-height:22px;white-space:normal;">
第一行包含两个非负整数，第一个为N，第二个为P。<br/>
接下来n行，按1~n的顺序描述了每个房间。第i+1行包含两个非负整数cost和keys，分别为第i件房取消魔法需要耗费的能量和房间内钥匙的数量。<br/>
接下来n-1行，每行两个非负整数x,y，表示x号房间和y号是连通的。
</dd>
<dt style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;margin:0px;padding:0px;font-size:16px;font-weight:bold;line-height:56px;color:#231F17;white-space:normal;">
输出
</dt>
<dd style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;margin:0px;padding:0px;color:#231F17;line-height:22px;white-space:normal;">
一行一个整数，表示取得钥匙的最大值。
</dd>
<dt style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;margin:0px;padding:0px;font-size:16px;font-weight:bold;line-height:56px;color:#231F17;white-space:normal;">
样例输入
</dt>
<dd style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;margin:0px;padding:0px;color:#231F17;line-height:22px;white-space:normal;">
<pre style="font-family:&#39;Courier New&#39;;margin-top:0px;margin-bottom:0px;padding:11px;background-color:#F5F5F5;border:1px solid #DADADA;font-size:14px;line-height:1.3em;overflow:auto;">5 5
1 2
1 1
1 1
2 3
3 4
1 2
1 3
2 4
2 5</pre>
</dd>
<dt style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;margin:0px;padding:0px;font-size:16px;font-weight:bold;line-height:56px;color:#231F17;white-space:normal;">
样例输出
</dt>
<dd style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;margin:0px;padding:0px;color:#231F17;line-height:22px;white-space:normal;">
<pre style="font-family:&#39;Courier New&#39;;margin-top:0px;margin-bottom:0px;padding:11px;background-color:#F5F5F5;border:1px solid #DADADA;font-size:14px;line-height:1.3em;overflow:auto;">7</pre>
</dd>
<dt style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;margin:0px;padding:0px;font-size:16px;font-weight:bold;line-height:56px;color:#231F17;white-space:normal;">
提示
</dt>
<dd style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;margin:0px;padding:0px;color:#231F17;line-height:22px;white-space:normal;">
数据范围<br/>
对于20%的测试数据，有n&lt;=20<br/>
对于30%的测试数据，有n&lt;=30<br/>
对于所有测试数据，有p,n&lt;=100, cost &lt;= Maxint, keys&lt;= Maxint
</dd>
