# 题目描述


<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:29px;font-family:sans-serif;line-height:28px;">
<span class="mw-headline" id=".E6.8F.8F.E8.BF.B0">描述  [USACO 2.1.3]<br/>
</span> 
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
排序是一种很频繁的计算任务。现在考虑最多只有三值的排序问题。一个实际的例子是，当我们给某项竞赛的优胜者按金银铜牌排序的时候。在这个任务中可能的值只有三种1，2和3。我们用交换的方法把他排成升序的。
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
写一个程序计算出，给定的一个1,2,3组成的数字序列，排成升序所需的最少交换次数。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:29px;font-family:sans-serif;line-height:28px;">
<span class="mw-headline" id=".E6.A0.BC.E5.BC.8F"><br/>
格式 </span> 
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
<b>PROGRAM NAME</b>: sort3
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
<b>INPUT FORMAT</b>:
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
(file sort3.in)
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
第一行：
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
奖牌个数N (1 &lt;= N &lt;= 1000)
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
第 2行到第N+1行:
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
每行一个数字，表示奖牌。共N行。（1..3）
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
<b>OUTPUT FORMAT</b>:
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
(file sort3.out)
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
共一行，一个数字。表示排成升序所需的最少交换次数。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:29px;font-family:sans-serif;line-height:28px;">
<span class="mw-headline" id="SAMPLE_INPUT"><br/>
SAMPLE INPUT</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;line-height:1.1em;">9
2
2
1
3
3
3
2
3
1
</pre>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:29px;font-family:sans-serif;line-height:28px;">
<span class="mw-headline" id="SAMPLE_OUTPUT"><br/>
SAMPLE OUTPUT</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;line-height:1.1em;">4</pre>
