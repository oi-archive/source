
# Description

<div class="content"><div>有一个平面，左下角是(0,0)，右上角是(A,B)。</div>
<div>有n个平行于y轴的栅栏a1..an，表示挡在(ai,0)到(ai,B)之间。</div>
<div>有m个平行于x轴的栅栏b1..bn，表示挡在(0,bi)到(A,bi)之间。</div>
<div>这样，平面被划成了(n+1)*(m+1)块。</div>
<div>现在要去掉某些栅栏的一部分，使得每一块都连通。</div>
<div>比如原来是这样：</div>
<p><img width="131" height="163" alt="" src="/source/bzoj/4410/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwMi8xLmpwZw==.jpg"/></p>
<div>可以去掉后变成这样：</div>
<p><img width="135" height="177" alt="" src="/source/bzoj/4410/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwMi8yKDEpLmpwZw==.jpg"/></p>
<div>求最少需要去掉多少长度的栅栏使得每一块都连通。</div></div>

# Input

<div class="content"><div>第一行四个数A,B,n,m。</div>
<div>A&lt;=1000000000 ,B&lt;=1000000000 N&lt;=25000 M&lt;=25000</div>
<div>接下来n行每行一个数表示ai</div>
<div>接下来m行每行一个数表示bi。</div>
<div>0&lt;ai&lt;A  0&lt;bi&lt;B </div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出一个数表示答案。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">15 15 5 2<br/>
2<br/>
5<br/>
10<br/>
6<br/>
4<br/>
11<br/>
3</span></div>

# Sample Output

<div class="content"><span class="sampledata">44</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

