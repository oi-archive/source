# 题目描述


<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
<span style="font-size:32px;">The Tamworth Two 两只塔姆沃斯牛  USACO 2.4.1</span> 
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
By BOI &#39;98? - Richard Forster
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
<br/>
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
<span class="mw-headline" id=".E9.A2.98.E7.9B.AE.E6.8F.8F.E8.BF.B0">题目描述</span> 
</h2>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
两只牛逃跑到了森林里。农夫John开始用他的专家技术追捕这两头牛。你的任务是模拟他们的行为(牛和John)。
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
追击在10x10的平面网格内进行。一个格子可以是：
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
一个障碍物, 两头牛(它们总在一起), 或者 农民John. 两头牛和农民John可以在同一个格子内(当他们相遇时)，但是他们都不能进入有障碍的格子。
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
一个格子可以是：
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#FFFFFF;line-height:1.1em;">. 空地 
* 障碍物 
C 两头牛 
F 农民John 
</pre>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
这里有一个地图的例子：
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#FFFFFF;line-height:1.1em;">*...*.....
......*...
...*...*..
..........
...*.F....
*.....*...
...*......
..C......*
...*.*....
.*.*......

</pre>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
牛在地图里以固定的方式游荡。每分钟，它们可以向前移动或是转弯。如果前方无障碍(地图边沿也是障碍)，它们会按照原来的方向前进一步。否则它们会用这一分钟顺时针转90度。 同时，它们不会离开地图。
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
农民John深知牛的移动方法，他也这么移动。
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
每次(每分钟)农民John和两头牛的移动是同时的。如果他们在移动的时候穿过对方，但是没有在同一格相遇，我们不认为他们相遇了。当他们在某分钟末在某格子相遇，那么追捕结束。
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
读入十行表示农夫John,两头牛和所有障碍的位置的地图。每行都只包含10个字符，表示的含义和上面所说的相同，你可以确定地图中只有一个&#39;F&#39;和一个&#39;C&#39;.&#39;F&#39;和&#39;C&#39;一开始不会处于同一个格子中。
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
计算农夫John需要多少分钟来抓住他的牛，假设牛和农夫John一开始的行动方向都是正北（即上）。 如果John和牛永远不会相遇，输出0。
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
<br/>
PROGRAM NAME: ttwo
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
<span class="mw-headline" id="INPUT_FORMAT"><br/>
INPUT FORMAT</span> 
</h2>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
第1-10行:
</p>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
每行10个字符，表示如上文描述的地图。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
<span class="mw-headline" id="SAMPLE_INPUT_.28file_ttwo.in.29"><br/>
SAMPLE INPUT (file ttwo.in)</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#FFFFFF;line-height:1.1em;">*...*.....
......*...
...*...*..
..........
...*.F....
*.....*...
...*......
..C......*
...*.*....
.*.*......
</pre>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
<span class="mw-headline" id="OUTPUT_FORMAT"><br/>
OUTPUT FORMAT</span> 
</h2>
<p style="margin-top:0.4em;margin-bottom:0.5em;line-height:27px;font-family:sans-serif;font-size:18px;white-space:normal;background-color:#FFFFFF;">
输出一个数字，表示John需要多少时间才能抓住牛们。如果John无法抓住牛，则输出0。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
<span class="mw-headline"><br/>
</span> 
</h2>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;background-color:#FFFFFF;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:28px;font-family:sans-serif;line-height:27px;white-space:normal;">
<span class="mw-headline" id="SAMPLE_OUTPUT_.28file_ttwo.out.29">SAMPLE OUTPUT (file ttwo.out)</span> 
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;background-color:#FFFFFF;line-height:1.1em;">49</pre>
<p>
<br/>
</p>
