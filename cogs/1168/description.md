# 题目描述


<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    我们知道机器调度是计算机科学中一个非常经典的问题。调度问题有很多种，具体条件不同，问题就不同。现在我们要处理的是两个机器的调度问题。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    有两个机器<span>A</span><span>和</span><span>B</span><span>。机器</span><span>A</span><span>有</span><span>n</span><span>种工作模式，我们称之为</span><span>mode_0</span><span>，</span><span>mode_l</span><span>，……，</span><span>mode_n</span></span><span style="font-size:10.5000pt;font-family:&#39;隶书&#39;;">-</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1<span>。同样，机器</span><span>B</span><span>有</span><span>m</span><span>种工作模式，我们称之为</span><span>mode_0</span><span>，</span><span>mode_1,</span><span>……，</span><span>mode_m</span></span><span style="font-size:10.5000pt;font-family:&#39;隶书&#39;;">-</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1<span>。初始时，两台机器的工作模式均为</span><span>mode_0</span><span>。现在有</span><span>k</span><span>个任务，每个工作都可以在两台机器中任意一台的特定的模式下被加工。例如，</span><span>job</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">能在机器<span>A</span><span>的</span><span>mode_3</span><span>或机器</span><span>B</span><span>的</span><span>mode_4</span><span>下被加工，</span><span>job</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">l</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">能在机器<span>A</span><span>的</span><span>mode_2</span><span>或机器</span><span>B</span><span>的</span><span>mode_4</span><span>下被加工，等等。因此，对于任意的</span><span>job</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">i</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，我们可以用三元组</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">i,x,y</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">来表示<span>job</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">i</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">在机器<span>A</span><span>的</span><span>mode_x</span><span>或机器</span><span>B</span><span>的</span><span>mode_y</span><span>下被加工。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    显然，要完成所有工作，我们需要不时的改变机器的工作模式。但是，改变机器的工作状态就必须重启机器，这是需要代价的。你的任务是，合理的分配任务给适当的机器，使机器的重启次数尽量少。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第一行三个整数<span>n</span><span>，</span><span>m</span><span>（</span><span>n,m</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">&lt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">100<span>），</span><span>k</span><span>（</span><span>k</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">&lt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1000<span>）。接下来的</span><span>k</span><span>行，每行三个整数</span></span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">i,x,y</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">只一行一个整数，表示最少的重启次数。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">machine.in                  </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">machine.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5 5 10</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">                       </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0 1 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1 1 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 1 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3 1 4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4 2 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5 2 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">6 2 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">7 2 4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">8 3 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">9 4 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<br/>
</p>
