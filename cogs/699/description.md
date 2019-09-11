# 题目描述


<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
	<span class="mw-headline" id=".E9.A2.98.E7.9B.AE">题目 USACO 2.3.5</span> 
</h2>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
	有些公司是其他公司的部分拥有者，因为他们获得了其他公司发行的股票的一部分。例如，福特公司拥有马自达公司12%的股票。据说，如果至少满足了以下三个条件之一，公司A就可以控制公司B了：
</p>
<ol style="line-height:27px;margin-top:0.3em;margin-right:0px;margin-bottom:0px;margin-left:3.2em;padding-top:0px;padding-right:0px;padding-bottom:0px;padding-left:0px;list-style-image:none;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
	<li style="margin-bottom:0.1em;">
		公司A = 公司B。
	</li>
	<li style="margin-bottom:0.1em;">
		公司A拥有大于50%的公司B的股票。
	</li>
	<li style="margin-bottom:0.1em;">
		公司A控制K(K &gt;= 1)个公司，记为C<sub>1</sub>, ..., C<sub>K</sub>，每个公司C<sub>i</sub>拥有x<sub>i</sub>%的公司B的股票，并且x<sub>1</sub>+ .... + x<sub>K</sub> &gt; 50%。
	</li>
</ol>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
	给你一个表，每行包括三个数(i,j,p)；表明公司i享有公司j的p%的股票。计算所有的数对(h,s)，表明公司h控制公司s。至多有100个公司。
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
	写一个程序读入N组数(i,j,p)，i,j和p是都在范围(1..100)的正整数，并且找出所有的数对(h,s)，使得公司h控制公司s。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
	<span class="mw-headline" id=".E8.BE.93.E5.85.A5.E6.A0.BC.E5.BC.8F"><br/>
输入格式</span> 
</h2>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
	第一行： N，表明接下来三个数的数量，即(i,j,p)的数量。
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
	第二行到第N+1行： 每行三个整数作为一个三对数(i,j,p)，表示i公司拥有j公司 p%的股份。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
	<span class="mw-headline" id=".E6.A0.B7.E4.BE.8B.E8.BE.93.E5.85.A5_.28file_concom.in.29"><br/>
样例输入 (file concom.in)</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#FFFFFF;line-height:1.1em;">3
1 2 80
2 3 80
3 1 20
</pre>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
	<span class="mw-headline" id=".E8.BE.93.E5.87.BA.E6.A0.BC.E5.BC.8F"><br/>
输出格式</span> 
</h2>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
	输出零个或更多个的控制其他公司的公司。每行包括两个整数A、B,表示A公司控制了B公司。将输出的数对以升序排列。
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
	请不要输出控制自己的公司(应该是不输出自己，互相控制的公司还是要输出的）。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
	<span class="mw-headline" id=".E6.A0.B7.E4.BE.8B.E8.BE.93.E5.87.BA_.28file_concom.out.29"><br/>
样例输出 (file concom.out)</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#FFFFFF;line-height:1.1em;">1 2
1 3
2 3</pre>
