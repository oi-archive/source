# 题目描述


<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
<span style="font-size:32px;">描述 USACO 2.4.2</span> 
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
农夫John在外面的田野上搭建了一个巨大的用栅栏围成的迷宫。幸运的是，他在迷宫的边界上留出了两段栅栏作为迷宫的出口。更幸运的是，他所建造的迷宫是一个“完美的”迷宫：即你能从迷宫中的任意一点找到一条走出迷宫的路。给定迷宫的宽度W(1&lt;=W&lt;=38)及高度H(1&lt;=H&lt;=100)。 2*H+1行，每行2*W+1的字符以下面给出的格式表示一个迷宫。然后计算从迷宫中最“糟糕”的那一个点走出迷宫所需的步数(就是从最“糟糕”的一点，走出迷宫的最少步数）。（即使从这一点以最优的方式走向最靠近的出口，它仍然需要最多的步数）当然了，牛们只会水平或垂直地在X或Y轴上移动，他们从来不走对角线。每移动到一个新的方格算作一步（包括移出迷宫的那一步）这是一个W=5,H=3的迷宫：
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#FFFFFF;line-height:1.1em;">+-+-+-+-+-+
|         |
+-+ +-+ + +
|     | | |
+ +-+-+ + +
| |     |  
+-+ +-+-+-+
</pre>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
如上图的例子，栅栏的柱子只出现在奇数行或奇数列。每个迷宫只有两个出口。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
<span class="editsection" style="float:right;margin-left:5px;font-size:18px;">[<a href="http://www.nocow.cn/index.php?title=Translate:USACO/maze1&amp;action=edit&amp;section=1" title="编辑段落：格式" style="text-decoration:none;color:#5A3696;background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:initial;background-position:initial initial;background-repeat:initial initial;">编辑</a>]</span><span class="mw-headline" id=".E6.A0.BC.E5.BC.8F">格式</span> 
</h2>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
<b>PROGRAM NAME</b>: maze1
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
<b>INPUT FORMAT</b>:
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
(file maze1.in)
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#FFFFFF;line-height:1.1em;">第一行： W和H（用空格隔开） 
第二行至第2 * H + 1行：  每行2 * W + 1个字符表示迷宫 
</pre>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
<b>OUTPUT FORMAT</b>:
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
(file maze1.out)
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#FFFFFF;line-height:1.1em;">输出一个单独的整数，表示能保证牛从迷宫中任意一点走出迷宫的最小步数。
</pre>
<h1 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:35px;font-family:sans-serif;line-height:27px;white-space:normal;">
<span class="editsection" style="float:right;margin-left:5px;font-size:18px;">[<a href="http://www.nocow.cn/index.php?title=Translate:USACO/maze1&amp;action=edit&amp;section=2" title="编辑段落：SAMPLE INPUT" style="text-decoration:none;color:#5A3696;background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:initial;background-position:initial initial;background-repeat:initial initial;">编辑</a>]</span><span class="mw-headline" id="SAMPLE_INPUT">SAMPLE INPUT</span> 
</h1>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#FFFFFF;line-height:1.1em;">5 3
+-+-+-+-+-+
|         |
+-+ +-+ + +
|     | | |
+ +-+-+ + +
| |     |  
+-+ +-+-+-+
</pre>
<h1 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:35px;font-family:sans-serif;line-height:27px;white-space:normal;">
<span class="editsection" style="float:right;margin-left:5px;font-size:18px;">[<a href="http://www.nocow.cn/index.php?title=Translate:USACO/maze1&amp;action=edit&amp;section=3" title="编辑段落：SAMPLE OUTPUT" style="text-decoration:none;color:#5A3696;background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:initial;background-position:initial initial;background-repeat:initial initial;">编辑</a>]</span><span class="mw-headline" id="SAMPLE_OUTPUT">SAMPLE OUTPUT</span> 
</h1>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#FFFFFF;line-height:1.1em;">9</pre>
