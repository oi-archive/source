# 

 
 # 题目背景 
NOIP2011&nbsp;day1&nbsp;第三题<BR> 

 
 # 题目描述 

![file](/source/joyoi/tyvj-1694/img/aHR0cDovL2FwaS5vai5qb3lvaS5jbi9hcGkvZmlsZS9kb3dubG9hZC8wMDg0NDYwOS02MzJkLTEwMzAtNjUzMS1lOTYyYjBhNTg0ODM=)

![file](/source/joyoi/tyvj-1694/img/aHR0cDovL2FwaS5vai5qb3lvaS5jbi9hcGkvZmlsZS9kb3dubG9hZC8wMDg0NDYwOS02YzBjLTEwMzAtNjczMS1lOTYyMzBkYTYzOGM=)

![file](/source/joyoi/tyvj-1694/img/aHR0cDovL2FwaS5vai5qb3lvaS5jbi9hcGkvZmlsZS9kb3dubG9hZC8wMDg0NDYwOS03MjNhLTEwMzctNjkzMS1lOTYyZjc3ZjkxOTI=)



<BR>&nbsp;&nbsp;&nbsp;&nbsp;Mayan&nbsp;puzzle是最近流行起来的一个游戏。游戏界面是一个&nbsp;7&nbsp;行5&nbsp;列的棋盘，上面堆放着一些方块，方块不能悬空堆放，即方块必须放在最下面一行，或者放在其他方块之上。游戏通关是指在规定的步数内消除所有的方块，消除方块的规则如下：&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;、&nbsp;&nbsp;每步移动可以且仅可以沿横向（即向左或向右）拖动某一方块一格：当拖动这一方块时，如果拖动后到达的位置（以下称目标位置）也有方块，那么这两个方块将交换位置（参见输入输出样例说明中的图6&nbsp;到图7&nbsp;）；如果目标位置上没有方块，那么被拖动的方块将从原来的竖列中抽出，并从目标位置上掉落（直到不悬空，参见下面图1&nbsp;和图2&nbsp;）；&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;、&nbsp;&nbsp;任一时刻，如果在一横行或者竖列上有连续三个或者三个以上相同颜色的方块，则它们将立即被消除（参见图1&nbsp;到图3）。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;注意：&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;a)&nbsp;如果同时有多组方块满足消除条件，几组方块会同时被消除（例如下面图4&nbsp;，三个颜色为1&nbsp;的方块和三个颜色为&nbsp;2&nbsp;的方块会同时被消除，最后剩下一个颜色为&nbsp;2&nbsp;的方块）。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;b)&nbsp;当出现行和列都满足消除条件且行列共享某个方块时，行和列上满足消除条件的所有方块会被同时消除（例如下面图5&nbsp;所示的情形，5&nbsp;个方块会同时被消除）。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;3&nbsp;、&nbsp;&nbsp;方块消除之后，消除位置之上的方块将掉落，掉落后可能会引起新的方块消除。注意：掉落的过程中将不会有方块的消除。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;上面图1&nbsp;到图&nbsp;3&nbsp;给出了在棋盘上移动一块方块之后棋盘的变化。棋盘的左下角方块的坐标为（0,&nbsp;0&nbsp;），将位于（3,&nbsp;3&nbsp;）的方块向左移动之后，游戏界面从图&nbsp;1&nbsp;变成图&nbsp;2&nbsp;所示的状态，此时在一竖列上有连续三块颜色为4&nbsp;的方块，满足消除条件，消除连续3&nbsp;块颜色为4&nbsp;的方块后，上方的颜色为3&nbsp;的方块掉落，形成图&nbsp;3&nbsp;所示的局面。&nbsp; 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行为一个正整数n&nbsp;，表示要求游戏通关的步数（这里指的是恰好n步通关）。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来的5&nbsp;行，描述&nbsp;7*5&nbsp;的游戏界面。每行若干个整数，每两个整数之间用一个空格隔开，每行以一个0&nbsp;结束，自下向上表示每竖列方块的颜色编号（颜色不多于10种，从1&nbsp;开始顺序编号，相同数字表示相同颜色）。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;输入数据保证初始棋盘中没有可以消除的方块。&nbsp; 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;如果有解决方案，输出&nbsp;n&nbsp;行，每行包含&nbsp;3&nbsp;个整数x，y，g&nbsp;，表示一次移动，每两个整数之间用一个空格隔开，其中（x&nbsp;，y）表示要移动的方块的坐标，g&nbsp;表示移动的方向，1&nbsp;表示向右移动，-1表示向左移动。注意：多组解时，按照&nbsp;x&nbsp;为第一关健字，y&nbsp;为第二关健字，1优先于-1&nbsp;，给出一组字典序最小的解。游戏界面左下角的坐标为（0&nbsp;，0&nbsp;）。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;如果没有解决方案，输出一行，包含一个整数-1。&nbsp; 

 
 # 提示 
对于30%&nbsp;的数据，初始棋盘上的方块都在棋盘的最下面一行；&nbsp;<BR>对于100%的数据，0&nbsp;&lt;&nbsp;n≤5&nbsp;。&nbsp; 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>3 
1 0 
2 1 0 
2 3 4 0 
3 1 0 
2 4 3 4 0 </td><td>2 1 1 
3 1 1 
3 0 1

对样例的解释
按箭头方向的顺序分别为图6 到图11 （图片暂缺）

样例输入的游戏局面如上面第一个图片所示，依次移动的三步是：（2 ，1 ）处的方格向
右移动，（3，1 ）处的方格向右移动，（3 ，0）处的方格向右移动，最后可以将棋盘上所有方
块消除。</td></tr></table>
