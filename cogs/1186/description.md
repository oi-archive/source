# 题目描述


<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">经过数月的精心准备，<span>Peer Brelstet</span><span>，一个出了名的盗画者，准备开始他的下一个行动。艺术馆的结构，每条走廊要么分叉为两条走廊，要么通向一个展览室。</span><span>Peer</span><span>知道每个展室里藏画的数量，并且他精确测量了通过每条走廊的时间。由于经验老到，他拿下一幅画需要</span><span>5</span><span>秒的时间。你的任务是编一个程序，计算在警察赶来之前，他最多能偷到多少幅画。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-align:center;">
	<img src="/upload/image/20121019/20121019170735_59678.png" alt=""/>
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第<span>1</span><span>行是警察赶到的时间，以</span><span>s</span><span>为单位。第</span><span>2</span><span>行描述了艺术馆的结构，是一串非负整数，成对地出现：每一对的第一个数是走过一条走廊的时间，第</span><span>2</span><span>个数是它末端的藏画数量；如果第</span><span>2</span><span>个数是</span><span>0</span><span>，那么说明这条走廊分叉为两条另外的走廊。数据按照深度优先的次序给出，请看样例。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">一个展室最多有<span>20</span><span>幅画。通过每个走廊的时间不超过</span><span>20s</span><span>。艺术馆最多有</span><span>100</span><span>个展室。警察赶到的时间在</span><span>10min</span><span>以内。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输出偷到的画的数量。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">gallery.in              </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">                    </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">gallery.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">60</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">                                          </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">7 0 8 0 3 1 14 2 10 0 12 4 6 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<br/>
</p>
