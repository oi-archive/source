
# Description

<div class="content"><div>给定一个n*m的矩形，其中有f个2*2的障碍物，其中任意两个障碍物中心之间的欧几里得距离至少为6，</div>
<div>且每个障碍物的中心到边缘的距离至少为3。请找到一条从左下角(1,1)出发经过所有没有障碍物的点各</div>
<div>一次的且最后回到左下角的回路。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含三个整数n,m,f(1&lt;=n,m&lt;=1000且n,m都为偶数)。</div>
<div>接下来f行，每行两个整数x,y(1&lt;=x&lt;n,1&lt;=y&lt;m)，表示该障碍物左下角的坐标。</div>
<p></p></div>

# Output

<div class="content"><div>如果无解，输出NIE，否则第一行输出TAK，第二行输出方案。</div>
<div>方案包含n*m-4*f个字符，第i个字符表示第i步的移动方向，用G表示上，D表示下，L表示左，P表示右。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">12 6 2<br/>
3 3<br/>
9 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
PPPPPPPPPPPGGGLDDLLLLLGPPGLLLDDLLLGGGPPPPPPPPPPGLLLLLLLLLLLDDDDD<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img src="/source/bzoj/4148/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNi9QaWxsYXJzU2FtcGxlLkpQRw==.JPG" width="334" height="192" alt=""/> </p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris上传">鸣谢Claris上传</a></p></div>

