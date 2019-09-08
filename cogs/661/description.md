# 题目描述


<div style="margin:13pt 0cm;">
<b><span style="font-size:medium;"><span style="line-height:173%;font-size:12pt;font-weight:normal;">【问题描述】</span></span></b> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">小</span><span style="font-size:12pt;">Q</span><span style="font-size:12pt;">在电子工艺实习课上学习焊接电路板。一块电路板由若干个元件组成，我们不妨称之为节点，并将其用数字</span><span style="font-size:12pt;">1,2,3….</span><span style="font-size:12pt;">进行标号。电路板的各个节点由若干不相交的导线相连接，且对于电路板的任何两个节点，都存在且仅存在一条通路（通路指连接两个元件的导线序列）。</span> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">在电路板上存在一个特殊的元件称为“激发器”。当激发器工作后，产生一个激励电流，通过导线传向每一个它所连接的节点。而中间节点接收到激励电流后，得到信息，并将该激励电流传向与它连接并且尚未接收到激励电流的节点。最终，激烈电流将到达一些“终止节点”——接收激励电流之后不再转发的节点。</span> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">激励电流在导线上的传播是需要花费时间的，对于每条边</span><i><span style="font-size:12pt;">e</span></i><span style="font-size:12pt;">，激励电流通过它需要的时间为</span><i><span style="font-size:12pt;">t<sub>e</sub></span></i><span style="font-size:12pt;">，而节点接收到激励电流后的转发可以认为是在瞬间完成的。现在这块电路板要求每一个“终止节点”同时得到激励电路——即保持时态同步。由于当前的构造并不符合时态同步的要求，故需要通过改变连接线的构造。目前小</span><span style="font-size:12pt;">Q</span><span style="font-size:12pt;">有一个道具，使用一次该道具，可以使得激励电流通过某条连接导线的时间增加一个单位。请问小</span><span style="font-size:12pt;">Q</span><span style="font-size:12pt;">最少使用多少次道具才可使得所有的“终止节点”时态同步？</span> 
</div>
<div style="margin:13pt 0cm;">
<b><span style="font-size:medium;"><span style="line-height:173%;font-size:12pt;font-weight:normal;">【输入文件】</span></span></b> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">输入文件</span><span style="font-size:12pt;">synch.in</span><span style="font-size:12pt;">第一行包含一个正整数</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">，表示电路板中节点的个数。</span> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">第二行包含一个整数</span><i><span style="font-size:12pt;">S</span></i><span style="font-size:12pt;">，为该电路板的激发器的编号。</span> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">接下来</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">-1</span><span style="font-size:12pt;">行，每行三个整数</span><i><span style="font-size:12pt;">a</span></i><span style="font-size:12pt;"> , <i>b</i> , <i>t</i></span><span style="font-size:12pt;">。表示该条导线连接节点</span><i><span style="font-size:12pt;">a</span></i><span style="font-size:12pt;">与节点</span><i><span style="font-size:12pt;">b</span></i><span style="font-size:12pt;">，且激励电流通过这条导线需要</span><i><span style="font-size:12pt;">t</span></i><span style="font-size:12pt;">个单位时间。</span> 
</div>
<div style="margin:13pt 0cm;">
<b><span style="font-size:medium;"><span style="line-height:173%;font-size:12pt;font-weight:normal;">【输出文件】</span></span></b> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">输出文件</span><span style="font-size:12pt;">synch.out</span><span style="font-size:12pt;">仅包含一个整数</span><i><span style="font-size:12pt;">V</span></i><span style="font-size:12pt;">，为小</span><span style="font-size:12pt;">Q</span><span style="font-size:12pt;">最少使用的道具次数。</span> 
</div>
<div style="margin:13pt 0cm;">
<b><span style="font-size:medium;"><span style="line-height:173%;font-size:12pt;font-weight:normal;">【样例输入】</span></span></b> 
</div>
<div>
<span style="font-size:12pt;"> 3</span> 
</div>
<div>
<span style="font-size:12pt;"> 1</span> 
</div>
<div>
<span style="font-size:12pt;"> 1 2 1</span> 
</div>
<div>
<span style="font-size:12pt;"> 1 3 3</span> 
</div>
<div style="margin:13pt 0cm;">
<b><span style="font-size:medium;"><span style="line-height:173%;font-size:12pt;font-weight:normal;">【样例输出】</span></span></b> 
</div>
<div>
<span style="font-size:12pt;"> 2</span> 
</div>
<div style="margin:13pt 0cm;">
<b><span style="font-size:medium;"><span style="line-height:173%;font-size:12pt;font-weight:normal;">【数据规模】</span></span></b> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">对于</span><span style="font-size:12pt;">40%</span><span style="font-size:12pt;">的数据，</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">≤ </span><span style="font-size:12pt;">1000</span> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">对于</span><span style="font-size:12pt;">100%</span><span style="font-size:12pt;">的数据，</span><i><span style="font-size:12pt;">N</span></i><span style="font-size:12pt;">≤ </span><span style="font-size:12pt;">500000</span> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-size:12pt;">对于所有的数据，</span><i><span style="font-size:12pt;">t<sub>e </sub></span></i><span style="font-size:12pt;">≤ </span><span style="font-size:12pt;">1000000</span> 
</div>
