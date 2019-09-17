# 题目描述


<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">你的任务是把一些人分成两组，使得：</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">·每个人都被分到其中一组；</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">·每个组都至少有一个人；</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">·一组中的每个人都认识其他同组成员；</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">·两组的成员人数近两接近。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">这个问题可能有多个解决方案，你只要输出任意一个即可，或者输出这样的分组法不存在。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">为了简单起见，所有的人都用一个整数标记，每个人号码不同，从<span>1</span><span>到</span><span>N</span><span>。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输入文件的第一行包括一个整数<span>N</span><span>（</span><span>2</span><span>≤</span><span>N</span><span>≤</span><span>100</span><span>），</span><span>N</span><span>就是需要分组的总人数；接下来的</span><span>N</span><span>行对应了这</span><span>N</span><span>个人，按每个人号码的升序排列，每一行给出了一串号码</span><span>A</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">ij</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">（<span>1</span><span>≤</span><span>A</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">ij</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">≤<span>N</span><span>，</span><span>A</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">ij</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">≠<span>i</span><span>），代表了第</span><span>i</span><span>个人所认识的人的号码，号码之间用空格隔开，并以一个“</span><span>0</span><span>”结束。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">如果分组方法不存在，就输出信息“<span>No solution</span><span>”（输出时无需加引号）至输出文件；否则用两行输出分组方案；第一行先输出第一组的人数，然后给出第一组成员的号码，每个号码前有一个空格，同理给出第二组的信息。每组的成员号码顺序和组别顺序并不重要。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">teams.in                    </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">teams.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">                            </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3 1 3 5</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 3 5 0                     </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 2 4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1 4 5 3 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1 2 5 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1 2 3 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4 3 2 1 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<br/>
</p>
