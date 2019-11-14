
# Description

<div class="content"><div>
<div>JYY有N个平面坐标系中的矩形。每一个矩形的底边都平行于X轴，侧边平行于Y轴。第i个矩形的左下角坐标为(Xi,Y</div>
<div>i)，底边长为Ai，侧边长为Bi。现在JYY打算从这N个矩形中，随机选出两个不同的矩形，并计算它们的并的大小。</div>
<div>JYY想知道，交的大小的期望是多少。</div>
<div>换句话说即求在所有可能的选择中，两个矩形交的面积的平均大小是多大。</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>输入一行包含一个正整数N。</div>
<div>接下来N行，每行4个整数，分别为Xi，Yi，Ai，Bi</div>
<div>2 &lt; =  N &lt; =  2*10^5, 0 &lt; =  Xi, Yi, Ai, Bi &lt; =  10^6。</div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>
<div>输出一行包含一个实数，表示矩形并的大小的期望。</div>
<div>【评分标准】</div>
<div>输出文件可以包含任意精度实数。</div>
<div>对于选手输出的解，如果和标准答案的差的绝对值不超过10?2，则将被判为正确解</div>
</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
0 0 3 5<br/>
2 1 3 5<br/>
3 3 3 5<br/>
0 5 3 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">1.833333333<br/>
输入的4个矩形的位置如下图。<br/>
精确解为：(4+0+0+1+6+0)/(4×3/2)=11/6</span></div>

# Hint

<div class="content"><p></p><p> <a href="/JudgeOnline/upload/201802/11(2).jpg">JudgeOnline/upload/201802/11(2).jpg</a></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

