
# Description

<div class="content"> <img border="0" src="/source/bzoj/2204/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzIyMDQuanBn.jpg"/> 
</div>

# Input

<div class="content">第一行s,为立方镜子的边长。(1&lt;=s&lt;=2^15)
第二行m,为镜子个数。（1&lt;=m&lt;=200000）
下接m行，每行四个数描述一面镜子
x,y,z,d表示在坐标(x,y,z)的点上有一面方向为d的镜子。（0&lt;=x,y,z&lt;=s，0&lt;=d&lt;=5，保证不会有两个镜子坐标相同）

</div>

# Output

<div class="content">共6组，每组两行，按顺序分别输出从面0到面5的出射光线条数，以及这部分光线的总反射次数。

</div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
4<br/>
4 4 0 0<br/>
1 3 0 1<br/>
1 1 0 0<br/>
4 1 0 1<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
0<br/>
0<br/>
0<br/>
1<br/>
1<br/>
1<br/>
1<br/>
34<br/>
0<br/>
0<br/>
0<br/>
<br/>
注：我们认为每个平板镜子都是无限薄的，即如果有一束光线从一个镜子的侧面射入，它会方向不变的射出。<br/>
<br/>
</span></div>

# Hint

<div class="content"><p>样例解释：<br/>
2号面射出去了一根光线：从(4,0,0)落下击中(4,1,0)处的镜子然后射出去。反射次数为1<br/>
3号面射出去了一根光线：从(1,0,0)落下击中(1,1,0)处的镜子然后射出去。反射次数为1<br/>
剩余的的36-2=34条光线没有经过任何反射直接从4号面射出。<br/>
(1,3,0)处的镜子与(4,4,0)处的镜子没被用到。<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=模拟题系列">模拟题系列</a></p></div>

