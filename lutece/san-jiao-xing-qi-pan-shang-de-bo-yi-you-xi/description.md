
# Content

柱爷有天上课无聊，于是和同桌卿学姐一起下一种奇特的棋：

棋盘如图：

![title](/source/lutece/san-jiao-xing-qi-pan-shang-de-bo-yi-you-xi/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTQwMi8yMDE2MDUyODIyMDEwMjE1MjY0LnBuZw==.png)

在开始游戏前，棋盘上已经放好了一些边，然后柱爷先手，开始在棋盘上没有边的位置添加一条边上去

如果添加边后围成一个三角形则获得一分（对于棋盘上游戏开始前已经围好了的三角形，两个人都不得分）并且下一轮还该他！否则下一轮该另一个人。

如果两个人都以最优策略下棋，那么柱爷能赢么？

注：只算最小的三角形！（三个边围成的三角形）

如果能赢输出“WIN!”

必败输出“LOSE!”

平局输出“Draw”

（都不输出引号）

愚人王感觉这规则太抽象了，都没人赶预测柱爷能不能赢了，于是画了个图解释了下题意：

![title](/source/lutece/san-jiao-xing-qi-pan-shang-de-bo-yi-you-xi/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTQwMi8yMDE2MDUzMDIyMzM1NDk3NDc1LnBuZw==.png)

对应：
5
1 2 3 4 5
的情况，如果这是开局情况，那么此时两个人都是0分，改柱爷先下，

如果他在6的位置填一条边，那么4,5,6将围城一个小三角形，柱爷得一分。接下来还是改柱爷下棋。

如果他在18的位置填一条边，那么将无法构成三角形，柱爷不得分，接下来改卿学姐下棋。

一直这样，直到填完所有边后，游戏结束。此时分高的人获胜，分相同则平局。

# Standard Input

第一行一个正整数n,表示开始游戏前有多少条边已经被放上去了。

第二行有n个正整数，a1...an代表已经放好的边的编号。


1<=a1...an<=18

# Standard Output

一行，输出柱爷的结局。

如果能赢输出“WIN!”

必败输出“LOSE!”

平局输出“Draw”

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>6
1 2 3 4 5 6
</td><td>WIN!
</td></tr><tr><td>5
4 5 6 7 8
</td><td>LOSE!
</td></tr></table>


# Constraints



# Note



# Source


