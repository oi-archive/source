# 题目描述


<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id=".E9.A2.98.E7.9B.AE.E6.8F.8F.E8.BF.B0">题目描述 [USACO 1.1.2]</span>
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
对于一群（NP个）要互送礼物的朋友，GY要确定每个人送出的钱比收到的多多少。 在这一个问题中，每个人都准备了一些钱来送礼物，而这些钱将会被平均分给那些将收到他的礼物的人。 然而，在任何一群朋友中，有些人将送出较多的礼物(可能是因为有较多的朋友)，有些人有准备了较多的钱。 给出一群朋友，没有人的名字会长于 14 字符，给出每个人将花在送礼上的钱，和将收到他的礼物的人的列表， 请确定每个人收到的比送出的钱多的数目。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id=".E8.BE.93.E5.85.A5.E6.A0.BC.E5.BC.8F.EF.BC.88gift1.in.EF.BC.89"><br/>
输入格式<b>（gift1.in）</b></span>
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
第 1 行: 人数NP,2&lt;= NP&lt;=10 
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
第 2 行 到 第NP+1 行:这NP个在组里人的名字　一个名字一行
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
第NP＋2到最后：
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
这里的I段内容是这样组织的：
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
第一行是将会送出礼物人的名字。
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
第二行包含二个数字:　第一个是原有的钱的数目（在0到2000的范围里），第二个 NG<sub>i</sub> 是将收到这个人礼物的人的个数 如果 NG<sub>i</sub> 是非零的, 在下面 NG<sub>i</sub> 行列出礼物的接受者的名字，一个名字一行。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id=".E8.BE.93.E5.87.BA.E6.A0.BC.E5.BC.8F.EF.BC.88gift1.out.EF.BC.89"><br/>
输出格式<b>（gift1.out）</b></span>
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
输出 NP 行 
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
每行是一个的名字加上空格再加上收到的比送出的钱多的数目。
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
对于每一个人，他名字的打印顺序应和他在输入的2到NP＋1行中输入的顺序相同。所有的送礼的钱都是整数。
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
每个人把相同数目的钱给每位要接受礼物的朋友，而且尽可能多给，不能给出的钱由送礼者本人持有。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id=".E9.87.8D.E8.A6.81.E6.8F.90.E7.A4.BA"><br/>
重要提示</span>
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:22px;font-family:sans-serif;font-size:15px;">
评测程序是基于UNIX的LINUX系统：换行符只是一个&#34;\n &#34;,这与WINDOWS下换行符有两个字符&#34;  \r与\n &#34;是不同的。<br/>
不要让你的程序踏入这个陷阱！
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id=".E6.A0.B7.E4.BE.8B.E8.BE.93.E5.85.A5"><br/>
样例输入</span>
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">5
dave
laura
owen
vick
amr
dave
200 3
laura
owen
vick
owen
500 1
dave
amr
150 2
vick
owen
laura
0 2
amr
vick
vick
0 0
</pre>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:19px;font-family:sans-serif;line-height:22px;">
<span class="mw-headline" id=".E6.A0.B7.E4.BE.8B.E8.BE.93.E5.87.BA"><br/>
样例输出</span>
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#F9F9F9;line-height:1.1em;font-size:15px;">dave 302
laura 66
owen -359
vick 141
amr -150</pre>
