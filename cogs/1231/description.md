# 题目描述


<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">给出一个正小数，找出分子</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">非负</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">不超过<span>M</span><span>，分母不超过</span><span>N</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">正数</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">的最简分数或整数，使其最接近给出的小数。“最接近”是指在数轴上该分数距离给出的小数最近，如果这个分数不惟一，输出“<span>TOO MANY</span><span>”。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输入文件共有二行，第一行包含两个用空格隔开的正整数<span>M</span><span>和</span><span>N</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">&lt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">＝<span>M</span><span>，</span><span>N</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">&lt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">=10</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:super;">7</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，表示要求的分数其分子不超过<span>M</span><span>，分母不超过</span><span>N</span><span>；第二行为小数</span><span>R</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">R</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">&gt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，<span>R</span><span>的整数部分为一个阿拉伯数字，小数部分最多有十位。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输出文件仅一行，若解唯一则输出“分子<span>/</span><span>分母”（整数</span><span>K</span><span>写成</span><span>K/1</span><span>），否则输出“</span><span>TOO MANY</span><span>”。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">close.in</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">360 120</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3.1415926536</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">close.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">355/113</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<br/>
</p>
