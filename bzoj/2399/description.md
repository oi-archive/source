
# Description

<div class="content"><div style="text-indent: 21pt">在一个二围坐标系中，有许多的线段。每一条线段都有颜色，且为R、G、B三种颜色中的某种，给出线段两端的坐标（线段有可能相交，且保证这些线段都在第一象限）。现在所有的线段都向x轴方向射出与线段颜色相同光线，光线方向与y轴平行。射出的光线只有中途没有碰到其他线段，才能射到x轴上，一条线段允许只有部分光线射到x轴。</div>
<div><span>       </span>请问，在x轴上，各个颜色的光线按R、G、B的顺序输出能看到的长度为多少，精确到0.01位。</div>
<div align="left"><b> </b></div></div>

# Input

<div class="content"><div style="text-indent: 21pt">第一行，一个数N，表示有N条线段。</div>
<div style="text-indent: 21pt" align="left">接下来N行，对每条线段进行描述。每一行有4个数与一个字母，用空格隔开。四个数字X1，Y1，X2，Y2描述此线段端点坐标，字母描述颜色。</div>
<div style="text-indent: 21pt" align="left"> </div></div>

# Output

<div class="content"><div style="text-indent: 21pt">三行，每行第一个为字母表示颜色，第一行R，第二行G，第三行B，每行第二个为实数，表示长度。</div>
<div align="left"> </div>
<div align="left"> </div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1 0 4 3 B<br/>
2 3 5 0 G<br/>
0 1 7 1 R<br/>
                             <br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">R 5.00<br/>
G 1.00<br/>
B 1.00<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>  N&lt;=300，坐标范围小于100000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

