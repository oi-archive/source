# 题目描述


<p align="center" style="text-align:center;">
	<b><span style="font-size:14.0pt;font-family:宋体;">题<span>1  </span></span></b><b><span style="font-size:14.0pt;font-family:宋体;">神奇的风<span></span></span></b>
</p>
<p>
	<b><span style="font-family:宋体;">【问题描述】<span></span></span></b>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">T</span><span style="font-family:宋体;">博士最近在研究一种神奇的风。<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">这种风有一个源头，称之为“风口”。风口的风要么是顺时针的，要么是逆时针的。<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">这种风是有能量的。<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">这种风是能传播的，如果风口周围都能传播风，风会像这样产生下一级的风：<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;"><span></span><span> <img src="http://media.openjudge.cn/images/upload/1338871035.PNG" alt=""/></span></span><span style="font-family:宋体;"></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">产生的下一级风的能量依据新产生的风所在的地形决定，有两种可以传递这种风的地形：<span></span></span>
</p>
<p style="text-indent:42.0pt;">
	<span style="font-family:宋体;">一、平地，下一级风的能量与风口的风能量相等，这种地形用“<span>.</span>”表示。<span></span></span>
</p>
<p style="text-indent:42.0pt;">
	<span style="font-family:宋体;">二、少量障碍物，下一级风的能量是风口的风能量的一半，这种地形用“<span>*</span>”表示。<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">每个新产生的风都能作为新的风口继续产生下一级风。<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">此外，还有一种地形是不能传递风的：大量障碍物，用“<span>#</span>”表示。<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">如果在风口的某一方向是“<span>#</span>”地形，则该方向不会产生下一级风，其他方向视该位置的地形而定，就是说，如果是“<span>.</span>”或“<span>*</span>”地形则该方向照样传播。<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">T</span><span style="font-family:宋体;">博士还发现了这种神奇的风的叠加规则：两股风叠加时，无论它们的转向是否相同，都只保留能量较大的那股风，即风叠加后的能量和转向都与叠加前能量较大的那股风相同。而如果叠加的两股风的能量相同且转向相同，则保留其中任意一股。两股风能量相同且转向不同时叠加的情况未知，因为<span>T</span>博士至今还没碰到这样的情况。<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">T</span><span style="font-family:宋体;">博士画了几张地图，他想知道地图上的某点风的转向和能量。<span></span></span>
</p>
<p>
	<b><span style="font-family:宋体;">【输入格式】<span></span></span></b>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">输入文件<span>wind.in</span>的第一行是两个整数<span>m</span>和<span>n</span>，表示地图大小为<span>m</span>行<span>n</span>列。<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">接下来的<span>m</span>行，每行是<span>n</span>个字符，只会是以下的几种：<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">“<span>S</span>”表示风口，保证图中有且仅有一个“<span>S</span>”。<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">“<span>E</span>”表示目的地，即<span>T</span>博士想知道的那个点。<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">“<span>.</span>”“<span>*</span>”“<span>#</span>”见描述。<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">第<span>m+2</span>行是一个整数“<span>0</span>”或“<span>1</span>”，分别表示风口的风是顺时针方向或逆时针方向。<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">约定“<span>S</span>”处的风能量为<span>16384</span>，“<span>S</span>”和“<span>E</span>”处的地形均为平地。<span></span></span>
</p>
<p>
	<b><span style="font-family:宋体;">【输出格式】<span></span></span></b>
</p>
<p>
	<span style="font-family:宋体;">    </span><span style="font-family:宋体;">输出文件为<span>wind.out</span>。<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">若目的地会有风传到，则输出两行：第一行为一个整数，为目的地的风的能量；第二行为一个整数“<span>0</span>”或“<span>1</span>”，表示意义同输入格式。此种情形下保证目的地的风的能量大于<span>0</span>。<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">若目的地没有风传到，则输出一行：“<span>There’s no wind!</span>”（双引号内的字符，全英文标点）。<span></span></span>
</p>
<p>
	<b><span style="font-family:宋体;">【样例输入<span>1</span>】<span></span></span></b>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">3 4</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">####</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">S**E</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">####</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">0</span>
</p>
<p>
	<b><span style="font-family:宋体;">【样例输出<span>1</span>】<span></span></span></b>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">4096  </span><span style="font-family:宋体;">（传递过程中经过两个“<span>*</span>”地形，能量变为原来的<span>1/4</span>，即变为<span>4096</span>）<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">1     </span><span style="font-family:宋体;">（<span>E</span>处的风是逆时针的）<span></span></span>
</p>
<p>
	<b><span style="font-family:宋体;">【样例输入<span>2</span>】<span></span></span></b>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">2 4</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">....</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">S**E</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">0</span>
</p>
<p>
	<b><span style="font-family:宋体;">【样例输出<span>2</span>】<span></span></span></b>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">16384</span><span style="font-family:宋体;">（传到目的地的风能量最大的为<span>16384</span>）<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">1</span><span style="font-family:宋体;">（<span>E</span>处的风是逆时针的）<span></span></span>
</p>
<p>
	<b><span style="font-family:宋体;">【样例输入<span>3</span>】<span></span></span></b>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">6 8</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">********</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">********</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">***S****</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">###*....</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">...#....</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">E..#....</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">1</span>
</p>
<p>
	<b><span style="font-family:宋体;">【样例输出<span>3</span>】<span></span></span></b>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">There’s no wind!</span>
</p>
<p>
	<b><span style="font-family:宋体;">【数据范围】<span></span></span></b>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">对于<span>20%</span>的数据，<span>m,n</span>均不超过<span>10</span>。<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">对于<span>50%</span>的数据，<span>m,n</span>均不超过<span>100</span>。<span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">对于<span>100%</span>的数据，<span>m,n</span>均不超过<span>200</span>。<span></span></span>
</p>
<p>
	<b><span style="font-family:宋体;">【提示】<span></span></span></b>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;">不要问我单引号怎么输出。<span></span></span>
</p>
