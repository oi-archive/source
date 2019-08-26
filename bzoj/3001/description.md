
# Description

<div class="content"><div style="margin: 0cm 0cm 0pt 18pt"><span style="font-size: medium"> </span></div>
<div style="margin: 0cm 0cm 0pt 17.95pt; text-indent: 21pt"><span style="font-size: medium">在一个神秘的岛上，有许许多多水井，水井只有两种，圆井和方井，两种井各有n个，水井两两相通。</span></div>
<div style="margin: 0cm 0cm 0pt 17.95pt; text-indent: 21pt"><span style="font-size: medium">如果两个水井形状相同，则水井下通道的流向是不确定的。可以任意修改。</span></div>
<div style="margin: 0cm 0cm 0pt 17.95pt; text-indent: 21pt"><span style="font-size: medium">如果两个水井形状不同，则水井下通道的流向是确定的。若两个水井间的距离Dij&gt;D，则圆井流向方井，否则方井流向圆井。</span></div>
<div style="margin: 0cm 0cm 0pt 17.95pt; text-indent: 21pt"><span style="font-size: medium">这里的Dij指的是曼哈顿距离（|xi-xj|+|yi-yj|)，D为给定值</span></div>
<div style="margin: 0cm 0cm 0pt 17.95pt; text-indent: 21pt"><span style="font-size: medium">如果某三个井i,j,k,它们形状不完全相同，且它们之间的连的边是 i→j,j→k,k→i。那么就会出现一次灵异现象。</span></div>
<div style="margin: 0cm 0cm 0pt 17.95pt; text-indent: 21pt"><span style="font-size: medium">现在要问的是，通过改变同形状水井通道的流向，使得灵异现象出现的最多次和最少次。</span></div></div>

# Input

<div class="content"><div style="margin: 0cm 0cm 0pt 17.95pt; text-indent: 21pt"><span style="font-size: medium">第一行两个正整数 N D</span></div>
<div style="margin: 0cm 0cm 0pt 17.95pt; text-indent: 21pt"><span style="font-size: medium">接下来N行Xi Yi描述第i个圆井的坐标</span></div>
<div style="margin: 0cm 0cm 0pt 17.95pt; text-indent: 21pt"><span style="font-size: medium">再接下来N行Xj Yj描述第j个方井的坐标</span></div></div>

# Output

<div class="content"><div style="margin: 0cm 0cm 0pt 17.95pt; text-indent: 26.25pt"><span style="font-size: medium">两个数依次为灵异现象出现最少的次数，最多的次数，中间用一个空格隔开。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 1<br/>
1 2<br/>
1 1<br/>
3 1<br/>
2 2    <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 2<br/>
100%   N&lt;=100000 1&lt;=x,y,d&lt;=100000且为整数<br/>
 <br/>
 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

