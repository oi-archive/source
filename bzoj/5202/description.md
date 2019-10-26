
# Description

<div class="content"><div>在三维空间中指定一些(x,y,z)，将[x,x+1]*[y,y+1]*[z,z+1]的方块填充，得到一些方块。</div>
<div>这些方块不需要连通，也不需要符合重力。</div>
<div>给定它们在Oxy，Oxz，Oyz三个平面上的投影面积，请构造一种合法方案。</div>
<div><img src="/source/bzoj/5202/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMy8xLnBuZw==.png" width="200" height="201" alt=""/></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含三个正整数a,b,c(1&lt;=a,b,c&lt;=100)</div>
<div>分别表示在Oxy，Oxz，Oyz三个平面上的投影面积。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>若无解，输出-1。</div>
<div>否则第一行输出一个正整数n(n&lt;=1000000)，表示方块个数。</div>
<div>接下来n行，每行三个整数x,y,z(-100&lt;=x,y,z&lt;=100)，描述一个方块。</div>
<div>注意同一个方块不能被描述两次，有多解输出任意一组。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
0 0 0<br/>
0 1 0<br/>
0 2 0<br/>
0 2 2<br/>
1 2 2<br/>
0 0 2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris提供翻译及SPJ">鸣谢Claris提供翻译及SPJ</a></p></div>

