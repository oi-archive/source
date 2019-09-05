# 题目描述


<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:29px;font-family:sans-serif;line-height:28px;">
<span class="mw-headline" id=".E6.8F.8F.E8.BF.B0">描述 [USACO 2.1.1]</span>
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
我们憨厚的USACO主人公农夫约翰(Farmer John)以无法想象的运气,在他生日那天收到了一份特别的礼物：一张“幸运爱尔兰”（一种彩票）。结果这张彩票让他获得了这次比赛唯一的奖品——坐落于爱尔兰郊外的一座梦幻般的城堡！
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
喜欢吹嘘的农夫约翰立刻回到有着吹嘘传统的威斯康辛老家开始吹嘘了, 农夫约翰想要告诉他的奶牛们关于他城堡的一切。他需要做一些吹嘘前的准备工作：比如说知道城堡有多少个房间，每个房间有多大。另外，农夫约翰想要把一面单独的墙（指两个单位间的墙）拆掉以形成一个更大的房间。 你的工作就是帮农夫约翰做以上的准备，算出房间数与房间的大小。
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
城堡的平面图被划分成M*N(1 &lt;=M,N&lt;=50）个正方形的单位，一个这样的单位可以有0到4面墙环绕。城堡周围一定有外墙环绕以遮风挡雨。（就是说平面图的四周一定是墙。）
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
<br/>
请仔细研究下面这个有注解的城堡平面图：
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;line-height:1.1em;">    1   2   3   4   5   6   7
  #############################
1 #   |   #   |   #   |   |   #
  #####---#####---#---#####---#   
2 #   #   |   #   #   #   #   #
  #---#####---#####---#####---#
3 #   |   |   #   #   #   #   #   
  #---#########---#####---#---#
4 # -&gt;#   |   |   |   |   #   #   
  #############################
</pre>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
 
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;line-height:1.1em;"># =墙壁    -,| = 没有墙壁
-&gt; =指向一面墙，这面墙推掉的话我们就有一间最大的新房间
</pre>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
友情提示，这个城堡的平面图是7×4个单位的。一个“房间”的是平面图中一个由“#”、“-”、“|”围成的格子（就是图里面的那一个个的格子）。比如说这个样例就有5个房间。（大小分别为9、7、3、1、8个单位（排名不分先后））
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
移去箭头所指的那面墙，可以使2个房间合为一个新房间，且比移去其他墙所形成的房间都大。（原文为：Removing the wall marked by the arrow merges a pair of rooms to make the largest possible room that can be made by removing a single wall. ）
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
城堡保证至少有2个房间，而且一定有一面墙可以被移走。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:29px;font-family:sans-serif;line-height:28px;">
<span class="mw-headline" id=".E6.A0.BC.E5.BC.8F"><br/>
格式</span>
</h2>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
<b>PROGRAM NAME</b>: castle
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
<b>INPUT FORMAT</b>: 第一行有两个整数：M和N 城堡的平面图用一个由数字组成的矩阵表示，一个数字表示一个单位，矩阵有N行M列。输入与样例的图一致。
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
每一个单位的数字告诉我们这个单位的东西南北是否有墙存在。每个数字是由以下四个整数的某个或某几个或一个都没有加起来的。
</p>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;line-height:1.1em;">1: 在西面有墙
2: 在北面有墙
4: 在东面有墙
8: 在南面有墙
</pre>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
城堡内部的墙会被规定两次。比如说（1，1）南面的墙，亦会被标记为（2，1）北面的墙。
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
<br/>
<b>OUTPUT FORMAT</b>:
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
(file castle.out)
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
输出包含如下4行:
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
第 1 行: 城堡的房间数目。
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
第 2 行: 最大的房间的大小
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
第 3 行: 移除一面墙能得到的最大的房间的大小
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
第 4 行: 移除哪面墙可以得到面积最大的新房间。
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
选择最佳的墙来推倒。有多解时选最靠西的，仍然有多解时选最靠南的。同一格子北边的墙比东边的墙更优先。
</p>
<p style="margin-top:0.4em;margin-right:0px;margin-bottom:0.5em;margin-left:0px;line-height:28px;font-family:sans-serif;font-size:19px;">
用该墙的南邻单位的北墙或西邻单位的东墙来表示这面墙，方法是输出邻近单位的行数、列数和墙的方位（&#34;N&#34;（北）或者&#34;E&#34;（东））。
</p>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:29px;font-family:sans-serif;line-height:28px;">
<span class="mw-headline" id="SAMPLE_INPUT"><br/>
SAMPLE INPUT</span>
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;line-height:1.1em;">7 4
11 6 11 6 3 10 6
7 9 6 13 5 15 5
1 10 12 7 13 7 5
13 11 10 8 10 12 13
</pre>
<h2 style="background-image:none;background-attachment:initial;background-origin:initial;background-clip:initial;font-weight:normal;margin-top:0px;margin-right:0px;margin-bottom:0.6em;margin-left:0px;overflow-x:hidden;overflow-y:hidden;padding-top:0.5em;padding-bottom:0.17em;border-bottom-width:1px;border-bottom-style:solid;border-bottom-color:#AAAAAA;font-size:29px;font-family:sans-serif;line-height:28px;">
<span class="mw-headline" id="SAMPLE_OUTPUT"><br/>
SAMPLE OUTPUT</span>
</h2>
<pre style="padding-top:1em;padding-right:1em;padding-bottom:1em;padding-left:1em;border-top-width:1px;border-right-width:1px;border-bottom-width:1px;border-left-width:1px;border-top-style:dashed;border-right-style:dashed;border-bottom-style:dashed;border-left-style:dashed;border-top-color:#2F6FAB;border-right-color:#2F6FAB;border-bottom-color:#2F6FAB;border-left-color:#2F6FAB;border-image:initial;line-height:1.1em;">5
9
16
4 1 E</pre>
