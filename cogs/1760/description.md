# 题目描述


<p class="Default">
<b>【背景】<span></span></b> 
</p>
<p class="Default">
<span>    </span>警报、警报，有不明精灵闯入实验室，请全体船员戒备，一级防御系统打开……
</p>
<p class="MsoNormal">
<b><span style="font-size:12.0pt;font-family:&#34;">【问题描述】<span></span></span></b> 
</p>
<p class="MsoNormal" style="text-indent:24.0pt;">
<span style="font-size:12.0pt;font-family:&#34;">……那个不明精灵，其实就是卡顿嘟嘟（和啾啾没有关系……），普通系，长得像个蘑菇，头顶上有两个大角……（这是神马<span>-_-|||</span>）。<span></span></span> 
</p>
<p class="MsoNormal" style="text-indent:24.0pt;">
<span style="font-size:12.0pt;font-family:&#34;">嘟嘟看到啾啾去玩捉迷藏了，于是他也想去。（题外话：等等，你不是说这俩家伙没关系么？）嗯，到底有没有关系呢？我也不知道……（呃啊！！！）<span></span></span> 
</p>
<p class="MsoNormal" style="text-indent:24.0pt;">
<span style="font-size:12.0pt;font-family:&#34;">咳咳（咳出一口逆血），嘟嘟比啾啾还要霸道，直接拖家带口一波流地拉来了几十只嘟嘟……，然后卡顿嘟嘟一声令下，<span>(</span>⊙<span>_</span>⊙<span>)</span>，几十只嘟嘟直接进了格子……<span></span></span> 
</p>
<p class="MsoNormal" style="text-indent:24.0pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">船长给了你一个</span><span style="font-size:12.0pt;font-family:&#34;">m</span><span style="font-size:12.0pt;font-family:&#34;">×<span>n</span>的矩阵，矩阵中的字母表示格子状态，</span><span style="font-size:12pt;font-family:微软雅黑, sans-serif;">其中若返回为<span>X</span>，则该点可能嘟嘟藏身的格子，但也有可能是距离嘟嘟很远的格子；若返回为<span>N</span>，则嘟嘟就在以该点为中心的<span>7*7</span>的矩阵中的某个格子；若返回为<span>C,<span class="apple-converted-space"> </span></span>则嘟嘟就在以该点为中心的<span>5*5</span>的矩阵中的某个格子；若返回为<span>Z</span>；则嘟嘟就在以该点为中心的<span>3*3</span>的矩阵中的某个格子。</span><span style="font-size:11.0pt;font-family:&#34;"></span> 
</p>
<p class="MsoNormal" style="text-indent:24.0pt;">
<span style="font-size:12.0pt;font-family:&#34;">就算是船长求你了吧，帮他找出嘟嘟来……<span></span></span> 
</p>
<p class="MsoNormal">
<b><span style="font-size:12.0pt;font-family:&#34;">【输入数据格式】<span></span></span></b> 
</p>
<p class="MsoNormal" style="text-indent:24.0pt;">
<span style="font-size:12.0pt;font-family:&#34;">第一行两个整数<span>n</span>、<span>m</span>和<span>k</span>，表示一个<span>m</span>×<span>n</span>的矩阵，矩阵中一共藏着<span>k</span>个嘟嘟。<span></span></span> 
</p>
<p class="MsoNormal" style="text-indent:24.0pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">第二行到第</span><span style="font-size:12pt;font-family:微软雅黑, sans-serif;">m−1</span><span style="font-size:12pt;font-family:微软雅黑, sans-serif;">行每行一个长度为</span><span style="font-size:12pt;font-family:微软雅黑, sans-serif;">n</span><span style="font-size:12pt;font-family:微软雅黑, sans-serif;">的字符串，表示矩阵状态。<span></span></span> 
</p>
<p class="MsoNormal">
<b><span style="font-size:12.0pt;font-family:&#34;">【输出数据格式】<span></span></span></b> 
</p>
<p class="MsoNormal" style="text-indent:24.0pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">一共<span>k</span>行，每行两个数，分别为嘟嘟藏身的格子的列数和行数。<span></span></span> 
</p>
<p class="MsoNormal" style="text-indent:24.0pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">对于每行坐标，你应该从上往下输出。</span> 
</p>
<p class="MsoNormal">
<b><span style="font-size:12.0pt;font-family:&#34;">【输入样例】<span></span></span></b> 
</p>
<p class="default0" style="margin-left:0cm;text-indent:24.0pt;">
<span style="font-family:&#39;Times New Roman&#39;, serif;">6 4 1</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default0" style="margin-left:0cm;text-indent:24.0pt;">
<span style="font-family:&#39;Times New Roman&#39;, serif;">ZZZCNX</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default0" style="margin-left:0cm;text-indent:24.0pt;">
<span style="font-family:&#39;Times New Roman&#39;, serif;">ZXZCNX</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default0" style="margin-left:0cm;text-indent:24.0pt;">
<span style="font-family:&#39;Times New Roman&#39;, serif;">ZZZCNX</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default0" style="margin-left:0cm;text-indent:24.0pt;">
<span style="font-family:&#39;Times New Roman&#39;, serif;">CCCCNX</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="MsoNormal">
<b><span style="font-size:12.0pt;font-family:&#34;">【输出样例】<span></span></span></b> 
</p>
<p class="MsoNormal" style="text-indent:24.0pt;">
<span style="font-size:12.0pt;font-family:&#34;">2 2</span> 
</p>
<p class="MsoNormal">
<b><span style="font-size:12.0pt;font-family:&#34;">【数据范围及约定】</span></b><b><span> </span></b><b><span style="font-size:12.0pt;font-family:&#34;"> </span></b> 
</p>
<p class="MsoNormal" style="text-indent:24.0pt;">
<span style="font-size:12.0pt;font-family:&#34;">40%</span><span style="font-size:12.0pt;font-family:&#34;">的数据：<span>2≤n,m≤100;</span></span> 
</p>
<p class="MsoNormal" style="text-indent:24.0pt;">
<span style="font-size:12.0pt;font-family:&#34;">100%</span><span style="font-size:12.0pt;font-family:&#34;">的数据：<span>1≤n,m≤1005;</span></span> 
</p>
<p class="MsoNormal" style="text-indent:24.0pt;">
<span style="font-size:12.0pt;font-family:&#34;">对于<span>100%</span>的数据都有<span>k</span>≤<span>10</span>。</span><span> </span><span style="font-size:12.0pt;font-family:&#34;"> </span> 
</p>
<p class="MsoNormal">
<b><span style="font-size:12.0pt;font-family:&#34;">【<span>Hite</span>】</span></b><b><span> </span></b><b><span style="font-size:12.0pt;font-family:&#34;"> </span></b><span style="font-size:12.0pt;font-family:&#34;"></span> 
</p>
<p class="MsoNormal" style="text-indent:24.0pt;">
<span style="font-size:12.0pt;font-family:&#34;">看不懂题可以参照<span>cogs1755</span>。<span></span></span> 
</p>
