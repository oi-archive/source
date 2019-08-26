
# Description

<div class="content"><div style="margin: 0cm 0cm 10pt"><span style="font-size: medium">现在有一条直线，直线上有n个原子核，每个原子核都有其各自的位置,原子序数和速度。经过一段时间之后，可能存在两个原子核互相碰撞。对于碰撞有两种可能，如果两个原子核的序数分别为a，b 且 M<sub>a</sub>+M<sub>b</sub>&gt;=M<sub>a+b</sub>[M<sub>i</sub>表示i号原子的质量]，则他们两个就会发生核聚变(只满足动量守恒且两原子核先达到共同速度再进行聚变)，聚变时会放出能量，放出的能量就是质量亏损的能量，我们假设所有的能量都转化为了动能，聚变后速度的方向与原来两个原子核的共同速度方向相同。但是如果M<sub>a</sub>+M<sub>b</sub>&lt;M<sub>a+b</sub>则他们就会发生弹性碰撞（动量和动能守恒）。[公式见注意事项]</span></div></div>

# Input

<div class="content"><div style="margin: 0cm 0cm 10pt"><span style="font-size: medium">第一行一个整数m表示（1..m的原子的质量已知）</span></div>
<div style="margin: 0cm 0cm 10pt"><span style="font-size: medium">接下来m个实数 表示M<sub>1..m</sub></span></div>
<div style="margin: 0cm 0cm 10pt"><span style="font-size: medium">接下来一个数c表示光速。</span></div>
<div style="margin: 0cm 0cm 10pt"><span style="font-size: medium">接下来两个数n，T表示该直线上有n个原子核，由T次询问。</span></div>
<div style="margin: 0cm 0cm 10pt"><span style="font-size: medium">接下来n行每行3个数 表示原子核的序数，位置，和初速度。</span></div>
<div style="margin: 0cm 0cm 10pt"><span style="font-size: medium">接下来T行表示T个询问</span></div>
<div style="margin: 0cm 0cm 10pt"><span style="font-size: medium">1 a b v 表示在b位置新建一个原子核序数为a的原子速度为v</span></div>
<div style="margin: 0cm 0cm 10pt"><span style="font-size: medium">2 a k删除位置第k小的原子序数为a的原子核</span></div>
<div style="margin: 0cm 0cm 10pt"><span style="font-size: medium">3 询问并进行下一次碰撞同时输出碰撞后的两个或一个原子核的三个信息</span></div>
<div style="margin: 0cm 0cm 10pt"><span style="font-size: medium">4 a b 删除位置最小的原子序数从a到b的原子核</span></div></div>

# Output

<div class="content"><div style="margin: 0cm 0cm 10pt"><span style="font-size: medium">接下来k行每行六或三个实数表示原子核的序数，位置和速度。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
2 3 4 5 6 7 8 13 15 20<br/>
3<br/>
3 2<br/>
6 1 0<br/>
1 2 0<br/>
1 3 -3<br/>
3<br/>
3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 2.00000000 -3.00000000<br/>
6 1.00000000 -1.80000000 2 1.00000000 1.20000000 <br/>
</span></div>

# Hint

<div class="content"><p></p><p><img height="1047" width="561" alt="" src="source/bzoj/3666/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNy8xMSgzKS5qcGc=.jpg"/></p><br/>
<p class="a" style="margin: 0cm 0cm 10pt; mso-line-height-alt: 11.0pt"><span lang="EN-US" style="font-size: 16pt; font-family: 宋体">T&lt;=2*10^5,N&lt;=100000,</span><span style="font-size: 16pt; font-family: 宋体">所有的数据满足<span lang="EN-US">m&lt;=10<sup>5</sup> </span>其余的数据属于<span lang="EN-US">[-10<sup>9</sup>..10<sup>9</sup>],</span>误差小于<span lang="EN-US">1e-5</span>则答案正确。<span lang="EN-US"><o:p></o:p></span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

