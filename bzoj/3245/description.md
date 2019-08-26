
# Description

<div class="content"><div><span style="font-size: medium">精明的小R每每开车出行总是喜欢走最快路线,而不是最短路线.很明显,每条道路的限速是小R需要考虑的关键问题.不过有一些限速标志丢失了,于是小R将不知道能开多快.不过有一个合理的方法是进入这段道路时不改变速度行驶.你的任务就是计算从小R家(0号路口)到D号路口的最快路线.</span></div>
<div><span style="font-size: medium">现在你得到了这个城市的地图,这个地图上的路都是单向的,而且对于两个路口A和B,最多只有一条道路从A到B.并且假设可以瞬间完成路口的转弯和加速.</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行是三个整数N,M,D(路口数目,道路数目,和目的地). 路口由0...N-1标号</span></div>
<div><span style="font-size: medium">接下来M行，每行描述一条道路:有四个整数A,B,V,L,(起始路口,到达路口,限速,长度) 如果V=0说明这段路的限速标志丢失.</span></div>
<div><span style="font-size: medium">开始时你位于0号路口,速度为70.</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">仅仅一行,按顺序输出从0到D经过的城市.保证最快路线只有一条.</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">6 15 1<br/>
0 1 25 68<br/>
0 2 30 50<br/>
0 5 0 101<br/>
1 2 70 77<br/>
1 3 35 42<br/>
2 0 0 22<br/>
2 1 40 86<br/>
2 3 0 23<br/>
2 4 45 40<br/>
3 1 64 14<br/>
3 5 0 23<br/>
4 1 95 8<br/>
5 1 0 84<br/>
5 2 90 64<br/>
5 3 36 40<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 5 2 3 1<br/>
</span></div>

# Hint

<div class="content"><p></p><p>【数据范围】<br/><br/>
30% N&lt;=20<br/><br/>
100% 2&lt;=N&lt;=150;0&lt;=V&lt;=500;1&lt;=L&lt;=500</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

