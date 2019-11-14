
# Description

<div class="content"><div>小T这学期有物理实验课，为了顺利完成下一节课的实验，他打算在课前对实验内容进行预习。这次实验在一个二</div>
<div>维平面上进行，平面上放置了一条无限长的直线导轨，导轨上放置了一个长为L的激光发射器，激光发射器会向导</div>
<div>轨两侧沿导轨垂直方向同时发射宽度为L的平行激光束。平面上还放置了n个挡板，每个挡板可以看作是一条线段，</div>
<div>现在每个挡板都不和直线导轨接触，且和直线导轨的夹角不超过85度，任意两个挡板也不会相互接触，激光束不能</div>
<div>穿透这些挡板，并且会被挡板吸收掉，不会被挡板反射出去。</div>
<div>小T想确定一个激光发射器的位置使得被激光束照射到的挡板长度之和最大，你需要帮小T算出这个最大值</div>
<p class="MsoNormal"></p>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数T，表示测试数据的组数，对于每组测试数据，</div>
<div>第一行是一个整数n，表示挡板个数，</div>
<div>接下来n行，每行包含四个整数x1,y1,x2,y2，表示挡板的两端点分别是(x1,y1)和(x2,y2)，保证(x1,y1)!=(x2,y2)，</div>
<div>第n+2行是五个整数x1,y1,x2,y2,L，表示直线导轨经过了点(x1,y1)和(x2,y2)，且激光发射器的长度为L，同样保证(x1,y1)!=(x2,y2)。</div>
<div>T &lt;= 100，</div>
<div>1 &lt;= n &lt;= 10^4，</div>
<div>1 &lt;= L &lt;= 2*10^9，</div>
<div>所有坐标的绝对值不超过 10^9</div></div>

# Output

<div class="content"><div>
<div>对于每组测试数据，输出一行，包含一个实数，表示激光束能照射到的挡板长度之和的最大值，要求相对误差不超过10^-6，</div>
<div>也就是说，令输出结果为a，标准答案为b，若满足|a-b|/max(1,b)&lt;=10^-6，则输出结果会被认为是正确答案。</div>
</div>
<div></div>
<p class="MsoNormal"></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
4<br/>
-3 2 -1 2<br/>
-1 -1 1 -1<br/>
0 1 2 1<br/>
2 -2 4 -2<br/>
0 0 1 0 2<br/>
4<br/>
1 1 3 3<br/>
2 1 4 2<br/>
3 1 5 1<br/>
3 -1 4 -1<br/>
0 0 -1 0 2<br/>
4<br/>
-2 0 1 2<br/>
1 3 -3 2<br/>
1 -3 5 -1<br/>
2 -1 4 3<br/>
0 0 1 1 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3.000000000000000<br/>
3.118033988749895<br/>
4.251303782246768</span></div>

# Hint

<div class="content"><p></p><p>请不要提交，尚无SPJ！</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

