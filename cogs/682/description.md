# 题目描述


<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id=".E6.8F.8F.E8.BF.B0">描述 [USACO 2.1.5]</span> 
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
<span style="font-size:18px;">给出 N，B 和 D，要求找出 N 个由0或1组成的编码（1 &lt;= N &lt;= 64），每个编码有 B 位（1 &lt;= B &lt;= 8），使得两两编码之间至少有 D 个单位的“Hamming距离”（1 &lt;= D &lt;= 7）。“Hamming距离”是指对于两个编码，他们二进制表示法中的不同二进制位的数目。看下面的两个编码 0x554 和 0x234（0x554和0x234分别表示两个十六进制数）:</span> 
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
 
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">0x554 = 0101 0101 0100
0x234 = 0010 0011 0100
不同位   xxx  xx
</pre>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
<span style="font-size:18px;">因为有五个位不同，所以“Hamming距离”是 5。</span> 
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id=".E6.A0.BC.E5.BC.8F">格式</span> 
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
<b><span style="font-size:18px;">INPUT FORMAT</span></b><span style="font-size:18px;">:</span>
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
<span style="font-size:18px;">一行，包括 N, B, D。</span> 
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
<b><span style="font-size:18px;">OUTPUT FORMAT</span></b><span style="font-size:18px;">:</span>
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
<span style="font-size:18px;">N 个编码（用十进制表示），要排序，十个一行。如果有多解，你的程序要输出这样的解：假如把它化为2进制数，它的值要最小。</span> 
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id="SAMPLE_INPUT"><br/>
SAMPLE INPUT</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">16 7 3
</pre>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id="SAMPLE_OUTPUT"><br/>
SAMPLE OUTPUT</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">0 7 25 30 42 45 51 52 75 76
82 85 97 102 120 127
</pre>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
 
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id=".E6.8F.90.E7.A4.BA"><br/>
提示</span> 
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
<span style="color:#FF0000;"><b>必须与其他所有的数相比，Hamming距离都符合要求,这个数才正确</b></span> 什么意思啊？？？ 答：如样例输出，0和7，0和25，0和……比较都符合海明码，同样7和25，7和30，7和……比较也符合要求，以此类推。 就这样了。
</p>
