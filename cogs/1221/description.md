# 题目描述


<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    有一个取数的游戏。初始时，给出一个环，环上的每条边上都有一个非负整数。这些整数中至少有一个<span>0</span><span>。然后，将一枚硬币放在环上的一个节点上。两个玩家就是以这个放硬币的节点为起点开始这个游戏，两人轮流取数，取数的规则如下：</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    （<span>1</span><span>）选择硬币左边或者右边的一条边，并且边上的数非</span><span>0</span><span>；</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    （<span>2</span><span>）将这条边上的数减至任意一个非负整数</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">至少要有所减小</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">；</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    （<span>3</span><span>）将硬币移至边的另一端。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    如果轮到一个玩家走，这时硬币左右两边的边上的数值都是<span>0</span><span>，那么这个玩家就输了。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">如下图，描述的是<span>Alice</span><span>和</span><span>Bob</span><span>两人的对弈过程，其中黑色节点表示硬币所在节点。结果图</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">d</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">中，轮到<span>Bob</span><span>走时，硬币两边的边上都是</span><span>0</span><span>，所以</span><span>Alcie</span><span>获胜。</span></span>
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span><span></span></span></span><img src="/upload/image/20121026/20121026110213_54862.png" width="589" height="150" alt=""/>
</p>
<p style="text-align:center;text-indent:21.75pt;">
	<br/>
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">现在，你的任务就是根据给出的环、边上的数值以及起点（硬币所在位置），判断先走方是否有必胜的策略。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第一行一个整数<span>N</span><span>（</span><span>N</span><span>≤</span><span>20</span><span>），表示环上的节点数。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第二行<span>N</span><span>个数，数值不超过</span><span>30</span><span>，依次表示</span><span>N</span><span>条边上的数值。硬币的起始位置在第一条边与最后一条边之间的节点上。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">仅一行。若存在必胜策略，则输出“<span>YES</span><span>”，否则输出“</span><span>NO</span><span>”。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">cycle.in</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">                     </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">cycle.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">                            </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">YES</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 5 3 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">cycle.in</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">                     </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">cycle.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3                           </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">NO</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0 0 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<br/>
</p>
