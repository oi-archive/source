
# Description

<div class="content"><p>远古时代，在吉丽王国的版图上分布着n个部落。建立平面直角坐标系后，每个部落都是一个边平行于坐标轴的矩形。有些地盘可能同时属于多个部落。随着时间推移，部落之间会发生融合。具体来说，若两个部落的公共面积严格大于零，它们会合并成一个新的部落，新部落的形状是包含原来两个部落的最小矩形（边平行于坐标轴）。<br/>
数百万年后，部落之间终于达到了稳定状态（任两个部落都不能再合并了），然而吉丽也已经老了。他想知道最终还剩下几个部落，以及各个部落的位置。你能替他完成遗业吗？</p></div>

# Input

<div class="content"><p>第一行一个整数n(1&lt;=n&lt;=100000)，表示远古时代的部落数量。<br/>
接下来n行，每行四个整数x1,x2,y1,y2(0&lt;=x1&lt;x2&lt;=1000000,0&lt;=y1&lt;y2&lt;=1000000)，表示部落的坐标。</p></div>

# Output

<div class="content"><p>第一行输出一个整数m，表示稳定后还剩下的部落数量。<br/>
接下来m行，每行四个整数x1,x2,y1,y2，表示部落的坐标。请按照字典序（先比较x1，若x1相等则比较x2，以此类推）从小到大输出。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
7 8 1 4<br/>
1 5 2 3<br/>
4 5 2 7<br/>
2 3 5 9<br/>
4 6 8 9</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1 6 2 9<br/>
7 8 1 4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Jcvb">鸣谢Jcvb</a></p></div>

