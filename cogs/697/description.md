# 题目描述


<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
	<span class="mw-headline" id=".E6.8F.8F.E8.BF.B0">描述 USACO 2.3.3</span> 
</h2>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
	请考虑一个由1到N（N=3, 4, 5 ... 9）的数字组成的递增数列：1 2 3 ... N。 现在请在数列中插入“+”表示加，或者“-”表示减，“ ”表示空白(例如1-2 3就等于1-23)，来将每一对数字组合在一起（请不要在第一个数字前插入符号）。 计算该表达式的结果并判断其值是否为0。 请你写一个程序找出所有产生和为零的长度为N的数列。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
	<span class="mw-headline" id=".E6.A0.BC.E5.BC.8F"><br/>
格式</span> 
</h2>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
	PROGRAM NAME: zerosum
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
	INPUT FORMAT
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
	单独的一行表示整数N (3 &lt;= N &lt;= 9)。
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
	OUTPUT FORMAT
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
	按照ASCII码的顺序，输出所有在每对数字间插入“+”, “-”, 或 “ ”后能得到结果为零的数列。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
	<span class="mw-headline" id="SAMPLE_INPUT_.28file_zerosum.in.29"><br/>
SAMPLE INPUT (file zerosum.in)</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#FFFFFF;line-height:1.1em;">7
</pre>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
	<br/>
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
	<span class="mw-headline" id="SAMPLE_OUTPUT_.28file_zerosum.out.29"><br/>
SAMPLE OUTPUT (file zerosum.out)</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#FFFFFF;line-height:1.1em;">1+2-3+4-5-6+7
1+2-3-4+5+6-7
1-2 3+4+5+6+7
1-2 3-4 5+6 7
1-2+3+4-5+6-7
1-2-3-4-5+6+7</pre>
