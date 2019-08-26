
# Description

<div class="content"><div>有n座城市，m个民族。这些城市之间由n-1条道路连接形成了以城市1为根的有根树。每个城市都是某一民族的聚居</div>
<div>地，Master知道第i个城市的民族是A_i，人数是B_i。为了维护稳定，Master需要知道某个区域内人数最多的民族</div>
<div>。他向你提出n个询问，其中第i个询问是：求以i为根的子树内，人数最多的民族有是哪个，这个民族有多少人。</div>
<div>如果子树内人数最多的民族有多个，输出其中编号最小的民族。</div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>共有2*n行。</div>
<div>第一行有两个整数n, m。</div>
<div>接下来n-1行，每行有两个整数u, v，表示一条连接u和v的道路。</div>
<div>接下来n行，第i行有两个整数A_i, B_i。</div>
<div>n&lt;=400000，m&lt;=n，1&lt;=A_i&lt;=m，0&lt;=B_i&lt;=1000。</div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>共有n行。</div>
<div>第i行两个整数x, y，分别表示以i为根的子树中人数最多的民族和它的人数。</div>
<div></div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">8 6<br/>
1 2<br/>
1 3<br/>
2 4<br/>
4 5<br/>
3 6<br/>
5 7<br/>
1 8<br/>
2 8<br/>
2 5<br/>
1 1<br/>
3 1<br/>
6 7<br/>
5 6<br/>
1 10<br/>
4 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 13<br/>
1 10<br/>
5 6<br/>
1 10<br/>
1 10<br/>
5 6<br/>
1 10<br/>
4 6<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

