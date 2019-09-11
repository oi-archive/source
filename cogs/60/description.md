# 题目描述


<b><span style="font-size:large;">题目描述</span></b>
<div>
DD 有一个不太听话的机器人，这个机器人总是会有自己的想法，而不会完全遵守<span> DD 给它的指令。</span> 
</div>
<div>
现在<span> DD 在试图命令机器人走迷宫。迷宫是一个 N*N 个格子组成的区域，格子自左上角到右下角从 (1,1) 到 (N,N) 编号。第 i 行、第 j 列的格子编号为 (i,j)。迷宫中的某些区域是障碍物，机器人不能移动到那里。</span> 
</div>
<div>
DD 给了机器人<span> M 条指令，指令的类型包括“前进一步”“后退一步”“左转九十度”“右转九十度”。但问题是机器人并不能完全遵守这些指令，因为如果机器人完全遵守这些指令，它可能会走到障碍物的格子里或者走到迷宫外面去，那样就会有危险。机器人希望从这个指令序列里面去掉一些，然后执行剩下的指令时，可以保证整个过程中都不会有危险。</span> 
</div>
<div>
机器人虽然不太听话，但它并不想惹恼了<span> DD，否则 DD 可能会把它拆掉的。所以机器人希望去掉的指令尽量少。</span> 
</div>
<div>
那么，机器人最少需要去掉多少条指令才能保证不会有危险呢？
</div>
<div>
<b><span style="font-size:large;">输入格式</span></b> 
</div>
<p>
第一行有四个整数<span> N、M、X0、Y0。表示迷宫的大小是 N*N，指令共有 M 条，机器人初始时的位置是<span> (X0,Y0)</span>。机器人初始时面朝的方向是上方。也就是说，若机器人按照初始时的方向走，效果是所在的 X 坐标越来越小。</span> 
</p>
<div>
下面有<span> N 行，每行有 N 个字符，可能是点号 &#39;.&#39; 或星号 &#39;*&#39;。&#39;.&#39; 表示空地，&#39;*&#39; 表示障碍。初始位置肯定是一个空地。</span> 
</div>
<div>
下面的<span> M 行，每行有一个字符串，表示指令。字符串可能是：FORWARD（前进一步）、BACK（后退一步）、LEFT（左转）、RIGHT（右转）。</span> 
</div>
<div>
<b><span style="font-size:large;">输出格式</span></b> 
</div>
<div>
只需要输出一个整数，表示机器人最少需要去掉多少条指令才能保证不出危险。
</div>
<div>
<b><span style="font-size:large;">样例输入</span></b> 
</div>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">4 7 3 3</pre>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">.***</pre>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">..**</pre>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">*..*</pre>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">****</pre>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">LEFT</pre>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">FORWARD</pre>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">LEFT</pre>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">BACK</pre>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">FORWARD</pre>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">RIGHT</pre>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">FORWARD</pre>
<div>
<b><span style="font-size:large;">样例输出</span></b> 
</div>
<pre style="margin:0cm 24pt 0pt;background:#EEEEEE;-moz-background-clip:-moz-initial;-moz-background-origin:-moz-initial;-moz-background-inline-policy:-moz-initial;">1</pre>
<div>
<b><span style="font-size:large;">样例说明</span></b> 
</div>
<div>
去掉第<span> 3 条、第 5 条或者第 7 条指令都可以保证机器人无危险。</span> 
</div>
<div>
<b><span style="font-size:large;">数据范围</span></b> 
</div>
<div>
迷宫的边长<span> N&lt;=100。</span> 
</div>
<div>
指令数<span> M&lt;=1000。</span> 
</div>
<div>
30%的数据M，N≤50
</div>
<p>
 
</p>
