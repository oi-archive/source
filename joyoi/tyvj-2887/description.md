# 

 
 # 题目描述 
<p>
【问题背景】<br>小K终于进了宫殿大门，可是他发现却身陷一个巨大的迷宫之中，突然一阵声音传来“想要Orz教主的勇士是需要经受考验的……”。当小K以坚定的信念通过了一次迷宫后，他发现同样的迷宫又出现了，不过出口发生了变化，这时他才知道这个迷宫需要通过m次……由于小K迫切希望Orz教主，为了尽快逃出这迷宫，所以小K又请来了你帮忙……<br><br>【问题描述】<br>小K在一个迷宫里，迷宫里只有小K，障碍和出口，都可以用整数坐标(xk, yk)表示。小K可以向上下左右四个平行于某一个坐标轴的方向移动，但是每次移动会向一个方向不断前进直到遇到障碍在障碍的前一个整数点停止，此时小K才可以再次进行移动。若所要移动的方向上没有障碍或出口，这次的移动就是非法的。每次往一个方向移动的代价为1，当某次移动过程中经过出口此次游戏胜利。<br>对于给定的迷宫，有n个障碍，小K起始坐标(X, Y)，以及m个出口（这m个出口不同时存在），即小K需要通过m次迷宫。对于每一个出口，问从同一个起始坐标移动到这个出口的最小代价是多少。<br></p> 

 
 # 输入格式 
<p>
输入文件escape.in的第1行有四个正整数n，m，X，Y，分别描述了障碍的个数，出口的个数，以及起始坐标。<br>下面n行，每行两个正整数x1i，y1i，描述了这n个障碍的坐标为(x1i, y1i)。<br>接下来m行，每行两个正整数x2i，y2i，描述了这m个出口的坐标为(x2i, y2i)。<br>所有整数之间用一个空格隔开。<br>保证所有坐标各不相同。<br></p> 

 
 # 输出格式 
<p>
输出文件escape.out包括m行，即对于每一个出口，问从起始点到出口的最小代价为多少，若不能到达则输出-1。</p> 

 
 # 提示 
<p>
<br><img src="/source/joyoi/tyvj-2887/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjg4Ny9wcm9ibGVtc19pbWFnZXMvMzQ0OS9wZy5qcGc=.jpg"></img></p> 
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
<tr><td>7 3 6 4
5 1
4 3
1 4
4 5
3 6
6 7
2 8
1 2
2 2
4 8
</td><td>5
2
3</td></tr></table>
