
# Description

<div class="content"><div>
<div>For some reason, Farmer John&#39;s cows always seem to be running laser light shows.For their latest sho</div>
<div>w, the cows have procured a large powerful laser -- so large, in fact, that they cannot seem to move</div>
<div> it easily from the location where it was delivered. They would like to somehow send the light from </div>
<div>the laser to the barn on the other side of FJ&#39;s property. Both the laser and the barn can be conside</div>
<div>red to be located at points in the 2D plane on a map of FJ&#39;s farm. The cows plan to point the laser </div>
<div>so that it sends a beam of light out either horizontally or vertically (i.e., aligned with the x or </div>
<div>y axes). They will then bounce this beam off a number of mirrors to direct it to the barn.On the far</div>
<div>m there are N fence posts (1≤N≤100,000) located at distinct 2D points (also distinct from the lase</div>
<div>r and the barn) at which the cows can mount mirrors. The cows can choose not to mount a mirror on a </div>
<div>fence post, in which case the laser would simply pass straight over the top of the post without chan</div>
<div>ging direction. If the cows do mount a mirror on a fence post, they align it diagonally like / or \ </div>
<div>so that it will re-direct a horizontal beam of light in a vertical direction or vice versa.Please co</div>
<div>mpute the minimum possible number of mirrors the cows need to use in order to re-direct the laser to</div>
<div> the barn.</div>
<div>出于某种原因，农夫约翰的奶牛总是喜欢使用激光。奶牛们搞到了一个强大的激光发射器，它很重，所以不能移动</div>
<div>它的位置。奶牛想用它照射到约翰的谷仓的另一端。众所周知，光沿直线传播，所以必须通过镜子的反射来使光线</div>
<div>发生偏折。激光射出的方向只能是平行于x轴或y轴的。农场上有N（1&lt;=N&lt;=100000）个坑位于平面直角坐标系上的</div>
<div>不同点（和激光发射器的位置和目标点的位置也不相同）。奶牛可以把镜子安装在坑里（当然也可以不安）。镜子</div>
<div>可以摆成“/”或者“\”。由物理知识可以知道，一道平行于x轴的光射到镜子上一定会平行于y轴射出，平行于y</div>
<div>轴的光一定会平行于x轴射出。现在给你激光发射器的坐标、目标点的坐标和所有坑的坐标，请你用最少的镜子来</div>
<div>实现奶牛的梦想。</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains 5 space-separated integers: N,xL,yL,xB,yB </div>
<div>where (xL,yL) is the location of the laser and (xB,yB) is the location of the barn. </div>
<div>All coordinates are between 0 and 1,000,000,000</div>
<div>The next N lines each contain the xx and y locations of a fence post,</div>
<div>both integers in the range 0…1,000,000,000</div>
<div><span style="font-family: arial, verdana, helvetica, sans-serif;">第一行包含5个正整数，分别是N,x1,y1,x2,y2，N的意义如题所述，(x1,y1)为激光发射器的坐标，(x2,y2)为目标点的坐标。</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">0&lt;=x1,y1,x2,y2&lt;=1,000,000,000</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">接下来N行，每行两个整数x,y表示坑的坐标。</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">0&lt;=x,y&lt;=1,000,000,000</span></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>output the minimum number of mirrors needed to direct the laser to the barn,</div>
<div>
<div>or -1 if this is impossible to do.</div>
<div><span style="font-family: arial, verdana, helvetica, sans-serif;">最少安装多少个镜子。如果无论怎样都无法完成，输出-1。</span></div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 0 0 7 2<br/>
3 2<br/>
0 2<br/>
1 6<br/>
3 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

