# 

 
 # 题目背景 
<p>图论中求两点间的不同路径问题</p> 

 
 # 题目描述 
<p>中央城消防部门与交通部门合作维护反映当前城市街道状况的地图。在规定的某天<br />
里,一些街道将由于修复或施工而被关闭。消防队员需要能够选择从消防站到火警地点<br />
的不经过被关闭街道的路线。<br />
中央城被划分成为不重叠的消防区,每区设有一个消防站。当火警发生时,&nbsp;一个中央<br />
调度站向火警地点所在的消防站发出警报并向其提供一个从该消防站到火警地点的可能<br />
路线的列表。你必须写一个程序供中央调度站使用以生成从地区消防站到火警地点的路<br />
线。</p>

<p>1.&nbsp;输入<br />
城市的每个消防区有一个独立的地图。每张地图的街区用小于&nbsp;21&nbsp;的正数标识,&nbsp;消防<br />
站总是在街区&nbsp;#&nbsp;1。输入文件包括一些测试项,&nbsp;代表在不同街区发生的不同的火警。测试<br />
项的第一行均表示离火警最近街区的编号。接下来若干行由用空格隔开的表示开放的街<br />
道所邻接的街区的正整数对组成。(&nbsp;例如,&nbsp;如果数对&nbsp;4&nbsp;7&nbsp;是文件中的一行,&nbsp;那么街区&nbsp;4<br />
和&nbsp;7&nbsp;之间的街道是开放的。在街区&nbsp;4&nbsp;和&nbsp;7&nbsp;之间的路段上没有其他街区。)&nbsp;每个测试项的最<br />
后一行由一个&nbsp;0&nbsp;数对组成。<br />
2.&nbsp;输出<br />
对于每个测试项,你的输出必须用数字来标识测试项(&nbsp;case&nbsp;#&nbsp;1&nbsp;,&nbsp;case&nbsp;#&nbsp;2,&nbsp;等等&nbsp;)。输出<br />
必须将每条路线列在不同的行上,&nbsp;街区按路线顺序依次写出。输出必须给出从消防站到<br />
火警地点的所有路线的总数。其中只包括那些不经过重复街区的路线&nbsp;(由于显而易见的<br />
理由,消防部门不希望他们的车子兜圈子&nbsp;)。不同测试项的输出必须出现在不同的行上。<br />
接下来的样例输入和相应的输出代表了一个测试项。</p>

<p>&nbsp;</p>

<p>&nbsp;</p> 

 
 # 输入格式 
<p>6</p>

<p>1&nbsp;2</p>

<p>1&nbsp;3</p>

<p>3&nbsp;4</p>

<p>3&nbsp;5</p>

<p>4&nbsp;6</p>

<p>5&nbsp;6</p>

<p>2&nbsp;3&nbsp;</p>

<p>2&nbsp;4</p>

<p>0&nbsp;0</p>

<p>&nbsp;</p> 

 
 # 输出格式 
<p>CASE&nbsp;#&nbsp;1:<br />
1&nbsp;2&nbsp;3&nbsp;4&nbsp;6<br />
1&nbsp;2&nbsp;3&nbsp;5&nbsp;6<br />
1&nbsp;2&nbsp;4&nbsp;3&nbsp;5&nbsp;6<br />
1&nbsp;2&nbsp;4&nbsp;6<br />
1&nbsp;3&nbsp;2&nbsp;4&nbsp;6<br />
1&nbsp;3&nbsp;4&nbsp;6<br />
1&nbsp;3&nbsp;5&nbsp;6<br />
There&nbsp;are&nbsp;7&nbsp;routes&nbsp;from&nbsp;the&nbsp;firestation&nbsp;to&nbsp;streetcorner&nbsp;6&nbsp;.</p>

<p>&nbsp;</p> 
