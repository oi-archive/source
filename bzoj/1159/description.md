
# Description

<div class="content"><div>在瑞典的达拉纳洲有一座高山。山上有一个小屋，里面住着一位牧羊女。每天清晨，隔壁的山头会传来一阵悠扬的</div>
<div>长笛声，而牧羊女则会站在屋里用自己的歌声回应。小屋的俯视图是一个有n个顶点的简单多边形，每一面墙可以</div>
<div>反射声音，但是由于不可避免的能量损失，最多只能反射k次（k=0表示不能反射声音）。墙面非常光滑，因此声音</div>
<div>的反射遵循反射角等于入射角，如图1。墙角不能反射声音，而每面墙的其他部分——即使离墙角很近——都可以</div>
<div>反射声音。</div>
<p><img border="0" alt="" src="/source/bzoj/1159/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzExNTlfMS5qcGc=.jpg"/> 图1.</p>
<div>声音的反射 突然有一天，牧羊女问自己：在小屋的哪些地方能听到她的歌声？假设所有听众都在屋里靠墙而坐，</div>
<div>那么歌声能到达的墙一共有多长？图2的四幅示意图分别画出了初始情况和声音经过0、1、2次反射后到达的区域。</div>
<div>灰色部分表示能听到歌声的部分，黑点表示牧羊女的位置。本题所求即灰色部分在多边形边界上的总长度。</div>
<p><img border="0" alt="" src="/source/bzoj/1159/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzExNTlfMi5qcGc=.jpg"/> </p>
<p>(a) 初始情况 (b)声音发出后未经反射</p>
<p><img border="0" alt="" src="/source/bzoj/1159/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzExNTlfMy5qcGc=.jpg"/> (</p>
<p>c) 声音1次反射 (d) 声音2次反射图2. 能听到歌声的区域</p></div>

# Input

<div class="content"><div>第一行包含4个整数n，k，x，y分别表示小屋的墙角数、最多反射的次数以及牧羊女的坐标</div>
<div>（牧羊女所在位置保证在屋内且至少离墙1个单位）。</div>
<div>以下n行每行两个整数x, y，表示第i个墙角的坐标。</div>
<div>墙角按照顺时针或逆时针排列。</div></div>

# Output

<div class="content"><p>输出文件仅包含一个实数L，表示能听到歌声的墙的总长度。保留两位小数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入1】<br/>
5 0 100 135<br/>
20 200<br/>
200 100<br/>
300 125<br/>
40 10<br/>
100 100<br/>
【样例输入2】<br/>
8 1 25 15<br/>
0 0<br/>
0 20<br/>
30 20<br/>
30 0<br/>
20 0<br/>
20 10<br/>
10 10<br/>
10 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">【样例输出1】<br/>
469.86<br/>
【样例输出2】<br/>
106.67</span></div>

# Hint

<div class="content"><p></p><p><span style="font-family: arial, verdana, helvetica, sans-serif; text-align: -webkit-center; white-space: nowrap;">鸣谢刘汝佳先生授权使用</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

