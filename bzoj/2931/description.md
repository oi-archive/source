
# Description

<div class="content"><p><font face="宋体" size="3">一场溜冰比赛在<span lang="EN-US">Byteland</span>最大的溜冰场举行。溜冰场是一个大小为<span lang="EN-US">10000 * 10000</span>的正方形。一个选手在裁判选定的起点开始滑冰，他的任务是滑到由裁判选定的终点。起点和终点不相同。一个选手在滑冰场的平行赛道上滑行。在滑冰场上设置了一些障碍物。每一个障碍物是一个棱柱，它的底部是边与滑冰场的各边平行的多边形。底部的每两个相邻的边总是垂直的。障碍物没有公共点。每一个滑道完结于一个点，在一个选手首先碰到一个障碍物的垂直于滑道方向一面。换一句话说，仅当一个选手撞到墙或者到了终点才能停下来。摔到溜冰场外则取消参赛资格。选手可以沿着障碍物的墙滑行。</font></p>
<p></p>
<p></p>
<p><img height="243" width="490" alt="" src="/source/bzoj/2931/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIxMi8xMSgxKS5qcGc=.jpg"/></p>
<div>判断一个选手依照所给的规则是否可以到达终点，假设他从起点开始滑行。如果如此，那么他需要滑行的最少数目是多少？</div>
<div style="margin: auto 0cm"><b><font size="3">任务</font></b></div>
<div>写一个程序:</div>
<ul type="disc">
    <li>读取溜冰场，障碍物的描述和起点终点的坐标，</li>
    <li>检验，一个从起点出发，遵循上述规则滑行的选手是否可以到达终点，如果可以，计算他需要滑行的最少数目，</li>
    <li>把结果输出</li>
</ul></div>

# Input

<div class="content"><div style="margin: auto 0cm"><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">我们定义一个坐标系统来描述滑冰场物体的位置。滑冰场是一个顶点分别为(0,0),(10000,0),(10000,10000),(0,10000)的正方形。在输入文件LOD.IN的首行有两个被单空格号隔开的整数<i>z<sub>1</sub> </i>和 <i>z<sub>2</sub></i> ，0&lt;=<i>z<sub>1</sub>, z<sub>2</sub></i>&lt;=10000。数字对(<i>z<sub>1</sub>, z<sub>2</sub></i>)表示起点的坐标。在文件的第二行有两个被单空格号分开的整数<i>t<sub>1</sub> </i>和<i>t<sub>2</sub></i> （0&lt;=<i>t<sub>1</sub>, t<sub>2</sub></i>&lt;=10000）。数字对（<i>t<sub>1</sub>, t<sub>2</sub></i>）表示终点的坐标。在文件的第三行包含了一个整数<i>s</i>,（1&lt;=<i>s</i>&lt;=2500）。这是障碍物的数目。下面的几行是对障碍物的描述。每一个障碍物的描述由一行包括一个等于障碍物的墙数（底边）的正整数r开始。接下来的r行的每一行有两个由单空格号隔开的整数x和y。那是障碍物底部顶点的坐标，按照顺时针顺序给出。（当按照这个方向绕障碍物一圈，它的内部在左手边）。障碍物的墙的总数不超过10000。</span></div></div>

# Output

<div class="content"><ul type="disc">
    <li><span style="font-size: medium">如果从起点到终点是不可能的，则字符串为‘NIE’， </span></li>
    <li><span style="font-size: medium">如果可能，则写出到达终点的最小滑行数。 </span></li>
</ul></div>

# Sample Input

<div class="content"><span class="sampledata">40 10<br/>
5 40<br/>
3<br/>
6<br/>
0 15<br/>
0 60<br/>
20 60<br/>
20 55<br/>
5 55<br/>
5 15<br/>
12<br/>
30 55<br/>
30 60<br/>
60 60<br/>
60 0<br/>
0 0<br/>
0 5<br/>
55 5<br/>
55 35<br/>
50 35<br/>
50 40<br/>
55 40<br/>
55 55<br/>
6<br/>
30 25<br/>
15 25<br/>
15 30<br/>
35 30<br/>
35 15<br/>
30 15<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> <br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img height="559" width="564" alt="" src="/source/bzoj/2931/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIxMi8yMi5qcGc=.jpg"/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

