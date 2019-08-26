
# Description

<div class="content">
    在Y城,有n条街道,每条街道由两个路口连接. Y城的交通系统十分特别,任意两个路口都有唯一的路径可以互相到达. 作为Y城的交通局长的小O,决定在这个城市启用一些电子警察来监控这个城市的所有街道和路口.电子警察的设置有2种:
1)	设置在某个路口,那么这个路口,所有的被它连接的街道,和所有它连接的街道的另一端的路口将被监控.
2)	设置在某条街道的中央,那么这条街道和连接这条街道的两个路口以及这两个路口所连接的其他街道将被监控.
     当然,由于经费问题,小O希望设置最少的电子警察来监控所有的街道和路口.
</div>

# Input

<div class="content">第一行为一个正整数n,表示街道的数目.
接下来n行,每行两个数x,y(x&lt;&gt;y,x,y&lt;=100000000),表示连接这条街道的两个路口的编号,不同的路口的编号一定不同.(由于某些原因,Y城的路口编号不一定是1,2…)
</div>

# Output

<div class="content">只有一个正整数,表示最少需要的电子警察的数目.
</div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
1 10<br/>
10 100<br/>
100 1000<br/>
1000 10000<br/>
10000 100000<br/>
100000 1000000<br/>
1000000 10000000  <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
Hint : 3个电子警察分别设置在编号为10的路口,第4条街道的中央和编号为1000000的路口.<br/>
数据范围<br/>
30%的数据,n&lt;=1000<br/>
100%的数据,n&lt;=200000<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

