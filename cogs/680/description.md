# 题目描述


<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id=".E6.8F.8F.E8.BF.B0">描述 [USACO 1.3.4]</span> 
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
下面是一个乘法竖式，如果用我们给定的那n个数字来取代*，可以使式子成立的话，我们就叫这个式子牛式。
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">        * * *
    x     * *
   ----------
        * * *
      * * *
   ----------
      * * * *
</pre>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
数字只能取代*，当然第一位不能为0,况且给定的数字里不包括0。
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
注意一下在美国的学校中教的“部分乘积”，第一部分乘积是第二个数的个位和第一个数的积，第二部分乘积是第二个数的十位和第一个数的乘积.
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
写一个程序找出所有的牛式。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id=".E6.A0.BC.E5.BC.8F"><br/>
格式</span> 
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
<b>PROGRAM NAME</b>: crypt1
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
<b>INPUT FORMAT</b>:
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
(file crypt1.in)
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;"> Line 1:数字的个数n。

 Line 2:N个用空格分开的数字（每个数字都属于{1,2,3,4,5,6,7,8,9}）。
</pre>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
<b>OUTPUT FORMAT</b>:
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
(file crypt1.out)
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;"> 共一行，一个数字。表示牛式的总数。
</pre>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id="SAMPLE_INPUT"><br/>
SAMPLE INPUT</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">5
2 3 4 6 8
</pre>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id="SAMPLE_OUTPUT"><br/>
SAMPLE OUTPUT</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">1
</pre>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id=".E6.A0.B7.E4.BE.8B.E5.88.86.E6.9E.90"><br/>
样例分析</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">        2 2 2
    x     2 2
   ----------
        4 4 4
      4 4 4
   ----------
      4 8 8 4
</pre>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
注意：结果只能为4位
</p>
