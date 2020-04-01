
# Description

<div class="content"><div>
<div>众所周知，奶牛贝茜最爱的事情就是在农场恶作剧。为了避免她造成太多的麻烦，农夫约翰决定用一根长绳将贝茜</div>
<div>系在栅栏上。从上面俯瞰，围栏由N个x坐标相等的柱子(1&lt;=N&lt;=10)组成，贝茜的位置(bx,by)位于这些柱子组成的</div>
<div>直线的右侧。约翰用来约束贝茜的绳子由M条首尾相接的线段(3&lt;=M&lt;=10,000)构成，其中第一段从贝茜的位置开始</div>
<div>，最后一段在贝茜的位置结束。保证这些线段上没有栅栏柱；但是线段可能交叉，并且可能有多条线段在端点处重</div>
<div>叠。为了帮助贝茜逃跑，其他的牛从谷仓里偷了一把锯子。请确定为了让贝西能够自由拉动（即她可以在没有绳子</div>
<div>拴住任何栅栏柱的情况下跑到右边），他们必须锯断栅栏杆的最少数量。输入中的所有(x,y)坐标（栅栏柱子、贝</div>
<div>茜和线段端点的位置）位于0至10,000的范围内。所有栅栏柱子都具有相同的x坐标，并且bx大于此值。</div>
<div></div>
</div></div>

# Input

<div class="content"><div>第一行四个整数N,M,bx,by。</div>
<div>接下来N行每行输入一根栅栏柱的坐标。</div>
<div>接下来M+1行按顺序输入绳子的端点坐标，保证第一个点和最后一个点与(bx,by)位置相同。</div>
<div></div></div>

# Output

<div class="content"><div>
<div>输出一行一个整数：让贝茜走到右侧需要锯断的最少柱子数。</div>
<div></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">2 10 6 1<br/>
2 3<br/>
2 1<br/>
6 1<br/>
2 4<br/>
1 1<br/>
2 0<br/>
3 1<br/>
1 3<br/>
5 4<br/>
3 0<br/>
0 1<br/>
3 2<br/>
6 1<br/>
输入解释：有两个柱子(2,3)和(2,1)。贝茜在(6,1)。绳索从(6,1)到(2,4)到(1,1)，依此类推，最后终止于(6,1)。<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
输出解释：锯断柱子1或柱子2可以使贝茜逃脱。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢zP1nG提供翻译">鸣谢zP1nG提供翻译</a></p></div>

