# 题目描述


<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:29px;font-family:sans-serif;line-height:28px;">
<span class="mw-headline" id=".E6.8F.8F.E8.BF.B0">描述 [USACO 1.3.3]</span> 
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
据说如果你给无限只母牛和无限台巨型便携式电脑(有非常大的键盘),那么母牛们会制造出世上最棒的回文。你的工作就是去寻找这些牛制造的奇观(最棒的回文)。
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
在寻找回文时不用理睬那些标点符号、空格(但应该保留下来以便做为答案输出),只用考虑字母&#39;A&#39;-&#39;Z&#39;和&#39;a&#39;-&#39;z&#39;。要你寻找的最长的回文的文章是一个不超过20,000个字符的字符串。我们将保证最长的回文不会超过2,000个字符(在除去标点符号、空格之前)。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:29px;font-family:sans-serif;line-height:28px;">
<span class="mw-headline" id=".E6.A0.BC.E5.BC.8F"><br/>
格式</span> 
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
<b>PROGRAM NAME: calfflac</b> 
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
<b>INPUT FORMAT：</b> (file calfflac.in)
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
输入文件不会超过20,000字符。这个文件可能一行或多行，但是每行都不超过80个字符(不包括最后的换行符)。
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
<b>OUTPUT FORMAT：</b> (file calfflac.out)
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
输出的第一行应该包括找到的最长的回文的长度。
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
下一行或几行应该包括这个回文的原文（没有除去标点符号、空格），把这个回文输出到一行或多行（如果回文中包括换行符）。
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
如果有多个回文长度都等于最大值，输出最前面出现的那一个。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:29px;font-family:sans-serif;line-height:28px;">
<span class="mw-headline" id="SAMPLE_INPUT"><br/>
SAMPLE INPUT</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;line-height:1.1em;">Confucius say: Madam, I&#39;m Adam.
</pre>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:29px;font-family:sans-serif;line-height:28px;">
<span class="mw-headline" id="SAMPLE_OUTPUT"><br/>
SAMPLE OUTPUT</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;line-height:1.1em;">11
Madam, I&#39;m Adam</pre>
