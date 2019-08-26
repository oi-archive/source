
# Description

<div class="content"><div><span style="font-size: medium">背景</span></div>
<div><span style="font-size: medium">众所周知，DZY是个大学霸，精通数理化。有天，吉丽拿着一道物理题目去问DZY，DZY很快就秒了这题，但是懒得算了，就让你来解决它。</span></div>
<div><span style="font-size: medium"><br/>
</span></div>
<div><span style="font-size: medium">题目描述</span></div>
<div><span style="font-size: medium">现在水平面上有一条无限长的光滑轨道，上面有n个小球(体积忽略)，每个小球的质量都相同。现在这些小球在某些神奇的力量下开始了运动。 给定一个常数C, 每个小球在任意时刻的速度v和加速度a均满足a*v=C. </span></div>
<div><span style="font-size: medium">吉丽还规定，在任意时刻，每个小球的加速度a和速度v方向相同。</span></div>
<div><span style="font-size: medium"><br/>
</span></div>
<div><span style="font-size: medium">因为有多个小球的存在，在运动中，小球之间可能发生碰撞，这里假设小球间发生的碰撞均为完全弹性碰撞。 </span></div>
<div><span style="font-size: medium">吉丽还会给你常数C，每个小球最开始的位置，运动方向，以及初速度Vi.</span></div>
<div><span style="font-size: medium">吉丽的询问是这样的： 给你整数T,K, 让你求当前系统中，让小球开始运动T时刻后，速率第K小的小球的速率为多少。</span></div>
<div><span style="font-size: medium">注意，每次询问之后，小球回到原位。</span></div>
<div><span style="font-size: medium"><br/>
</span></div>
<div><span style="font-size: medium">当然，为了考察你的随机应变能力，吉丽会在问问题的时候不时地增加新的小球。</span></div>
<div><span style="font-size: medium"><br/>
</span></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div></div>
<div>
<div><span style="font-size: medium">第一行包含两个正整数n,C. </span></div>
<div><span style="font-size: medium">接下来n行，每行包含三个整数Vi,Xi,Di</span></div>
<div><span style="font-size: medium">Vi代表第i个小球的速率</span></div>
<div><span style="font-size: medium">Xi代表第i个小球的初始位置(你可以想象轨道是一个数轴)</span></div>
<div><span style="font-size: medium">Di代表第i个小球的初始运动方向 其中1表示正方向，-1表示反方向。</span></div>
<div><span style="font-size: medium">接下来一行Q 代表操作的个数</span></div>
<div><span style="font-size: medium">接下来Q行，第一个数为操作的种类tp</span></div>
<div><span style="font-size: medium">0 Vj Xj Dj 代表吉丽增加了一个初速度Vj, 位置Xj， 运动方向Dj的小球</span></div>
<div><span style="font-size: medium">1 T K 代表吉丽的一次询问</span></div>
<div><span style="font-size: medium"><br/>
</span></div>
<div></div>
</div>
<div>
<p></p>
</div></div>

# Output

<div class="content"><div></div>
<div>
<div><span style="font-size: medium">对于每一个询问，输出一行包含一个实数，代表答案。 保留3位小数。</span></div>
<div><span style="font-size: medium"><br/>
</span></div>
<div><span style="font-size: medium">数据范围</span></div>
<div><span style="font-size: medium">n,m&lt;=10^5 Vi&lt;=10^5 |Xi|&lt;=10^9 0&lt;C&lt;=10^9 0&lt;=T&lt;=10^5 </span></div>
<div><span style="font-size: medium">保证数据合法</span></div>
<div><span style="font-size: medium"><br/>
</span></div>
<div></div>
</div>
<div>
<p></p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 10<br/>
1 2 1<br/>
3 4 1<br/>
6 5 1<br/>
3<br/>
1 5 1<br/>
0 8 -5 -1<br/>
1 8 2<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">10.050<br/>
13.000<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">n,Q&lt;=10^5 Vi&lt;=10^5 |Xi|&lt;=10^9 0&lt;C&lt;=10^9 0&lt;=T&lt;=10^5 </span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By AcrossTheSky
">By AcrossTheSky<br/>
</a></p></div>

