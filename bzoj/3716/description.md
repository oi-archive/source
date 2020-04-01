
# Description

<div class="content"><p>吉丽的漫展有n件手办和m名警卫。建立平面直角坐标系，每个手办和警卫都可以看做一个点。警卫们的目光都朝着y轴负方向，且都有相同大小的视角。警卫可以看见自己视角内（包括边界上的点）的所有手办，不用考虑视线的遮挡。<br/>
你打算抢劫吉丽的漫展，但不可被警卫发现。为了实施这次抢劫计划，你可以事先贿赂某些警卫，让他们闭上眼睛。只要某件手办不在任何睁着眼睛的警卫的视野内，你就可以偷走它。你知道每件手办的价格，以及每位警卫需要接受多少钱的贿赂。你想知道自己的最大收益是多少。</p></div>

# Input

<div class="content"><p>第一行两个整数n,m(1&lt;=n,m&lt;=200000)，分别表示手办的数量和警卫的数量。<br/>
第二行两个整数w,h(1&lt;=w,h&lt;=10^9)，表示每个警卫的视角的一半的正切值是w/h。（见配图）<br/>
接下来n行，每行三个整数x[i],y[i],v[i](-10^9&lt;=x[i],y[i]&lt;=10^9,1&lt;=v[i]&lt;=10^9)，表示手办的坐标为(x[i],y[i])，价格为v[i]。<br/>
接下来m行，格式同上，表示警卫的坐标为(x[i],y[i])，需接受贿赂的金额为v[i]。<br/>
保证每个点最多只有一个手办或一个警卫。</p>
<p><img height="224" alt="" width="210" src="/source/bzoj/3716/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwOS9tdXpyeXMtY3JvcC5naWY=.gif"/></p></div>

# Output

<div class="content"><p>输出仅一行表示最大收益。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
2 3<br/>
2 6 2<br/>
5 1 3<br/>
5 5 8<br/>
7 3 4<br/>
8 6 1<br/>
3 8 3<br/>
4 3 5<br/>
5 7 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
样例解释：<br/>
贿赂3+6元，偷走2+8+4+1元，收益6元。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Jcvb">鸣谢Jcvb</a></p></div>

