# 题目描述


USACO/camelot
<div>
<div>
Camelot亚瑟王的宫殿
</div>
<div>
<p>
译 by leontea
</p>
<hr/>
</div>
</div>
描述
<p>
很久以前，亚瑟王和他的骑士习惯每年元旦去庆祝他们的友谊。为了纪念上述事件，我们把这些是看作是一个有一人玩的棋盘游戏。有一个国王和若干个骑士被放置在一个由许多方格组成的棋盘上，没有两个骑士在同一个方格内。
</p>
<p>
这个例子是标准的8*8棋盘
</p>
<a href="http://www.nocow.cn/index.php/%E6%96%87%E4%BB%B6:%E6%A3%8B%E7%9B%98.jpg"><img alt="棋盘.jpg" src="http://www.nocow.cn/images/b/b3/%E6%A3%8B%E7%9B%98.jpg" width="226" height="206"/></a> 
<p>
国王可以移动到任何一个相邻的方格，从下图中黑子位置到下图中白子位置前提是他不掉出棋盘之外。
</p>
<a href="http://www.nocow.cn/index.php/%E6%96%87%E4%BB%B6:%E5%9B%BD%E7%8E%8B.jpg"><img alt="国王.jpg" src="http://www.nocow.cn/images/f/fc/%E5%9B%BD%E7%8E%8B.jpg" width="103" height="69"/></a> 
<p>
一个骑士可以从下图中黑子位置移动到下图中白子位置(走“日”字形） 但前提是他不掉出棋盘之外。
</p>
<a href="http://www.nocow.cn/index.php/%E6%96%87%E4%BB%B6:%E9%AA%91%E5%A3%AB.jpg"><img alt="骑士.jpg" src="http://www.nocow.cn/images/7/70/%E9%AA%91%E5%A3%AB.jpg" width="167" height="130"/></a> 
<p>
在游戏中，玩家可在每个方格上放不止一个棋子，假定方格足够大，任何棋子都不会阻碍到其他棋子正常行动。
</p>
<p>
玩家的任务就是把所有的棋子移动到同一个方格里——用最小的步数。为了完成这个任务，他必须按照上面所说的规则去移动棋子。另外，玩家可以选择一个骑士跟国王从他们两个相遇的那个点开始一起行动，这时他们按照骑士的行动规则行动，其他的单独骑士则自己一直走到集中点。骑士和国王一起走的时候，只算一个人走的步数。
</p>
<p>
写一个程序去计算他们集中在一起的最小步数，而且玩家必须自己找出这个集中点。当然，这些棋子可以在棋盘的任何地方集合。
</p>
格式
<p>
PROGRAM NAME: camelot
</p>
<p>
INPUT FORMAT
</p>
<p>
(file camelot.in)
</p>
<p>
第一行： 两个用空格隔开的整数：R,C 分别为棋盘行和列的长。不超过26列，30行。
</p>
<p>
第二行..结尾： 输入文件包含了一些有空格隔开的字母/数字对，一行有一个或以上。第一对为国王的位置，接下来是骑士的位置。可能没有骑士，也可能整个棋盘都是骑士。行从1开始，列从大写字母A开始。
</p>
<p>
OUTPUT FORMAT
</p>
<p>
(file camelot.out)
</p>
<p>
单独一行表示棋子集中在一个方格的最小步数。
</p>
<p>
SAMPLE INPUT
</p>
<p>
8 8
D 4
A 3 A 8
H 1 H 8
</p>
<p>
国王位置在D4。一共有四个骑士，位置分别是A3,A8,H1和H8。
</p>
<p>
SAMPLE OUTPUT
</p>
<p>
10
</p>
<p>
SAMPLE OUTPUT ELABORATION
</p>
他们集中在B5。 
骑士1: A3 - B5 (1步)  
骑士2: A8 - C7 - B5 (2步) 
骑士3: H1 - G3 - F5 - D4 (此时国王开始与这个骑士一起走) - B5 (4步) 
骑士4: H8 - F7 - D6 - B5 (3步) 
1 + 2 + 4 + 3 = 10步<!-- 
NewPP limit report
Preprocessor node count: 62/1000000
Post-expand include size: 327/2097152 bytes
Template argument size: 126/2097152 bytes
Expensive parser function count: 0/100
--><!-- Saved in parser cache with key newnocow:pcache:idhash:853-0!*!0!!zh-cn!2!* and timestamp 20120711015557 -->
<p>
<br/>
</p>
