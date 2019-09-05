# 题目描述


<h3>
【题目描述】
</h3>
<p>
<img src="/upload/image/20140201/20140201153439_79181.jpg" alt=""/> 
</p>
<p>
疯狂火箭（Rocket Mania）是幻想游戏系列中我最喜欢的游戏之一。在这个游戏中，左边有一些火柴，右边有一些火箭。在中间，有许多种类的带有导火索的格子（见图A）。这些导火索可以被旋转0，90，180或270度。为了发射火箭，必须用导火索形成一条从火柴到火箭的连续通道。当一条完整的通路建立的时候，连接着火柴的所有火箭都将被发射（见图B）。
</p>
<p>
<img src="/upload/image/20140201/20140201152752_51687.jpg" alt=""/> 
</p>
<p>
【图A】
</p>
<p>
<img src="/upload/image/20140201/20140201153222_76671.jpg" alt=""/> 
</p>
<p>
【图B】
</p>
<p>
你的任务是，给出初始情况，旋转一些导火索，使点燃某一根火柴后，发射的火箭数量尽量多。
</p>
<p>
<img src="/upload/image/20140201/20140201153348_29602.gif" alt=""/> 
</p>
<p>
【导火索】
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件的第一行有一个正整数X（1&lt;=X&lt;=9），代表点燃火柴的位置。
</p>
<p>
接下来有9行，每行有6个字符，这些字符可以是‘.’‘L’‘T’或者‘+’，它们分别代表空格子和相应形状的导火索
</p>
<p>
<img src="/upload/image/20140201/20140201153728_31681.png" alt=""/> L型 <img src="/upload/image/20140201/20140201153740_71601.png" alt=""/> -型 <img src="/upload/image/20140201/20140201153751_35978.png" alt=""/> T型 <img src="/upload/image/20140201/20140201153810_79298.png" alt=""/> +型
</p>
<h3>
【输出格式】
</h3>
<p>
输出一行一个正整数，即点燃第X行的火柴后，最多发射的火箭数量。
</p>
<p>
如果无法发射火箭，输出0.
</p>
<h3>
【样例输入】
</h3>
<h4>
sample 1:
</h4>
<p>
<br/>
</p>
<p>
1
</p>
<p>
LLLLLL
</p>
<p>
LLLLLL
</p>
<p>
LLLLLL
</p>
<p>
LLLLLL
</p>
<p>
LLLLLL
</p>
<p>
LLLLLL
</p>
<p>
LLLLLL
</p>
<p>
LLLLLL
</p>
<p>
LLLLLL
</p>
<p>
<br/>
</p>
<h4>
sample 2:
</h4>
<p>
<br/>
</p>
<p>
3
</p>
<p>
......
</p>
<p>
.L----
</p>
<p>
-+----
</p>
<p>
.-....
</p>
<p>
.T---L
</p>
<p>
.L----
</p>
<p>
......
</p>
<p>
......
</p>
<p>
......
</p>
<p>
<br/>
</p>
<h4>
sample 3:
</h4>
<p>
<br/>
</p>
<p>
5
</p>
<p>
-L-L-L
</p>
<p>
-TL--T
</p>
<p>
-L-T-L
</p>
<p>
--+---
</p>
<p>
---T--
</p>
<p>
-TL---
</p>
<p>
---LT-
</p>
<p>
---T-T
</p>
<p>
-TL-T-
</p>
<p>
<br/>
</p>
<h4>
sample 4:
</h4>
<p>
<br/>
</p>
<p>
1
</p>
<p>
TTTTTT
</p>
<p>
TTTTTT
</p>
<p>
TTTTTT
</p>
<p>
TTTTTT
</p>
<p>
TTTTTT
</p>
<p>
TTTTTT
</p>
<p>
TTTTTT
</p>
<p>
TTTTTT
</p>
<p>
TTTTTT
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【样例输出】
</h3>
<h4>
sample 1:
</h4>
<p>
1
</p>
<h4>
sample 2:
</h4>
<p>
3
</p>
<h4>
sample 3:
</h4>
<p>
4
</p>
<h4>
sample 4:
</h4>
<p>
9
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://acm.zju.edu.cn/onlinejudge/showProblem.do?problemCode=2125" target="_blank">ZOJ2125 Rocket Mania</a> 
</p>
<p>
Author: CHEN, Shixi
</p>
<p>
Source: Online Contest of Fantastic Game
</p>