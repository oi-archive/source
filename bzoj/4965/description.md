
# Description

<div class="content"><div>天猫有一个停车场，这个停车场是由一个N行M列的网格构成的，每个网格是一个车位。刚开始，某些车位已经停了</div>
<div>车。停车场经常有车辆进进出出。在天猫观察的这一段时间内，总共有Q次车辆进出。在其中的第i次，在第Xi行第</div>
<div>Yi列的车位的停车情况发生了变化，即要么这个车位之前是空的，一辆新的车停了进来，要么是原本停在这个这个</div>
<div>位置的车离开了（是哪一种取决于这个事件之前这个车位有没有停车）。有时，天猫需要在某个连续子矩形区域内</div>
<div>，找一块最大的K行K列的正方形连续网格，使得这块区域中的车位都没有停车。请你在他的每次询问的时候，帮他</div>
<div>找出最大的K值。</div>
<p></p></div>

# Input

<div class="content"><div>第一行N,M,Q,C.Q为操作（停车情况变化或询问）的次数,C为数据类型。</div>
<div>接下来N行，每行M个0或1，描述所有车位的停车情况。</div>
<div>如果第i行第j列的网格没有停车，则这一个数字将会是1，否则是0。</div>
<div>接下来Q行，每行2种情况：</div>
<div>0 x y：第x行第y列的车位的停车情况发生了变化；</div>
<div>1 x1 y1 x2 y2：询问以(x1,y1)和(x2,y2)为对角线的子矩形中，最大的K是多少。</div>
<div>对于所有数据，保证N*M&lt;=4000000,Q&lt;=2000并且N&gt;M</div>
<div>对于情况0，保证1&lt;=X&lt;=N，1&lt;=Y&lt;=M</div>
<div>对于情况1，保证1&lt;=X1&lt;=X2&lt;=N,1&lt;=Y1&lt;=Y2&lt;=M</div>
<p></p></div>

# Output

<div class="content"><div>输出Q行，表示每次变动后最大的K。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">http://www.lydsy.com/JudgeOnline/upload/s11.in</span></div>

# Sample Output

<div class="content"><span class="sampledata">http://www.lydsy.com/JudgeOnline/upload/s11.out</span></div>

# Hint

<div class="content"><p></p><p> 数据似乎有误，现给出数据，有心人可以查下错<a href="http://www.lydsy.com/JudgeOnline/upload/4965.rar">www.lydsy.com/JudgeOnline/upload/4965.rar</a></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

