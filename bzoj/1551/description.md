
# Description

<div class="content"> 小K终于进了宫殿大门，可是他发现却身陷一个巨大的迷宫之中。当小K以坚定的信念通过了一次迷宫后，他发现同样的迷宫又出现了，不过出口发生了变化，这时他才知道这个迷宫需要通过m次……由于小K希望尽快逃出这迷宫，所以小K又请来了你帮忙……
小K在一个迷宫里，迷宫里只有小K，障碍和出口，都可以用整数坐标(xk, yk)表示。小K可以向上下左右四个平行于某一个坐标轴的方向移动，但是每次移动会向一个方向不断前进直到遇到障碍在障碍的前一个整数点停止，此时小K才可以再次进行移动。若所要移动的方向上没有障碍或出口，这次的移动就是非法的。每次往一个方向移动的代价为1，当某次移动过程中经过出口此次游戏胜利。
　 　对于给定的迷宫，有n个障碍，小K起始坐标(X, Y)，以及m个出口（这m个出口不同时存在），即小K需要通过m次迷宫。对于每一个出口，问从同一个起始坐标移动到这个出口的最小代价是多少。

</div>

# Input

<div class="content">输入的第1行有四个正整数n，m，X，Y，分别描述了障碍的个数，出口的个数，以及起始坐标。
下面n行，每行两个正整数x1i，y1i，描述了这n个障碍的坐标为(x1i, y1i)。
接下来m行，每行两个正整数x2i，y2i，描述了这m个出口的坐标为(x2i, y2i)。
所有整数之间用一个空格隔开。
保证所有坐标各不相同。
	
</div>

# Output

<div class="content">输出包括1行，即对于每一个出口，问从起始点到出口的最小代价为多少，若不能到达则输出-1，数字之间用空格隔开，末尾换行。

</div>

# Sample Input

<div class="content"><span class="sampledata">7 3 6 4<br/>
5 1<br/>
4 3<br/>
1 4<br/>
4 5<br/>
3 6<br/>
6 7<br/>
2 8<br/>
1 2<br/>
2 2<br/>
4 8<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5 2 3<br/>
对于100%的数据，n≤100000，m≤100000，所有坐标涉及的正整数不大于 10^ 8。	<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=HNOI2009集训Day5">HNOI2009集训Day5</a></p></div>

