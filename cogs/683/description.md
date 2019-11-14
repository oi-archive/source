# 题目描述


<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
	<span class="mw-headline" id=".E6.8F.8F.E8.BF.B0">描述 [USACO 2.2.1]</span> 
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
	一类书的序言是以罗马数字标页码的。传统罗马数字用单个字母表示特定的数值，以下是标准数字表:
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">I 1  L 50  M 1000
V 5  C 100
X 10 D 500
</pre>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
	最多3个同样的可以表示为10<sup>n</sup>的数字(I,X,C,M)可以连续放在一起，表示它们的和:
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">III=3
CCC=300
</pre>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
	可表示为5x10<sup>n</sup>的字符(V,L,D)从不连续出现。
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
	除了下一个规则，一般来说，字符以递减的顺序接连出现:
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">CCLXVIII = 100+100+50+10+5+1+1+1 = 268
</pre>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
	有时，一个可表示为10<sup>n</sup>的数出现在一个比它大1级或2级的数前(I在V或X前面，X在L或C前面，等等)。在这种情况下，数值等于后面的那个数减去前面的那个数:
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">IV = 4
IX = 9
XL = 40
</pre>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
	<br/>
一个数 用罗马数字来表示 有且仅有一种 而且不能复合嵌套使用（比如I是1 X是10 有人可能要说 IXL就能表示50-10-1 但是IXL绝对不能用来表达39 ） （那么39用什么来表示呢 XXXIX是唯一 而且正确的选择- -）
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
	<br/>
像XD, IC, 和XM这样的表达是非法的，因为前面的数比后面的数小太多。对于XD(490的错误表达)，可以写成 CDXC; 对于IC(99的错误表达)，可以写成XCIX; 对于XM(990的错误表达)，可以写成CMXC。 90 写成 XC 而不是 LXL, 因为 L 后面的 X 意味着后继标记是 X 或者更小 (不管怎样，可能吧).
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
	<br/>
给定N(1 &lt;= N &lt; 3,500)， 序言的页码数，请统计在第1页到第N页中，有几个I出现，几个V出现，等等 (从小到大的顺序)。不要输出没有出现过的字符。
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
	比如N = 5, 那么页码数为: I, II, III, IV, V. 总共有7个I出现，2个V出现。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
	<span class="mw-headline" id=".E6.A0.BC.E5.BC.8F"><br/>
格式</span> 
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
	<b>PROGRAM NAME</b>: preface
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
	<b>INPUT FORMAT</b>:
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
	(preface.in)
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
	一个整数N。
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
	<b>OUTPUT FORMAT</b>:
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
	(preface.out)
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
	每行一个字符和一个数字k，表示这个字符出现了k次。字符必须按数字表中的递增顺序输出。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
	<span class="mw-headline" id="SAMPLE_INPUT"><br/>
SAMPLE INPUT</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">5
</pre>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
	<span class="mw-headline" id="SAMPLE_OUTPUT"><br/>
SAMPLE OUTPUT</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">I 7
V 2</pre>
