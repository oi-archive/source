# 题目描述


<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id=".E6.8F.8F.E8.BF.B0">描述  [USACO 2.2.2]</span> 
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
对于从1到N (1 &lt;= N &lt;= 39) 的连续整数集合，能划分成两个子集合，且保证每个集合的数字和是相等的。举个例子，如果N=3，对于{1，2，3}能划分成两个子集合，每个子集合的所有数字和是相等的：
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">{3} 和 {1,2}
</pre>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
这是唯一一种分法（交换集合位置被认为是同一种划分方案，因此不会增加划分方案总数） 如果N=7，有四种方法能划分集合{1，2，3，4，5，6，7}，每一种分法的子集合各数字和是相等的:
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">{1,6,7} 和 {2,3,4,5} {注 1+6+7=2+3+4+5}
{2,5,7} 和 {1,3,4,6}
{3,4,7} 和 {1,2,5,6}
{1,2,4,7} 和 {3,5,6}
</pre>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
给出N，你的程序应该输出划分方案总数，如果不存在这样的划分方案，则输出0。<b>程序不能预存结果直接输出（不能打表）。</b> 
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id=".E6.A0.BC.E5.BC.8F"><br/>
格式</span> 
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
<b>PROGRAM NAME</b>: subset
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
<b>INPUT FORMAT</b>:
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
(file subset.in)
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
输入文件只有一行，且只有一个整数N
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
<b>OUTPUT FORMAT</b>:
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
(file subset.out)
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
输出划分方案总数，如果不存在则输出0。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id="SAMPLE_INPUT"><br/>
SAMPLE INPUT</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">7
</pre>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id="SAMPLE_OUTPUT"><br/>
SAMPLE OUTPUT</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">4</pre>
