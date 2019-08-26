
# Description

<div class="content"><p>　　桌上有一张边界平行于坐标轴的正方形纸片，左下角的坐标为(0,0)，右上角的坐标为(100,100)。接下来执行<br/>
n条折纸命令。每条命令用两个不同点P1(x1,y1)和P2(x2,y2)来表示，执行时把当前的折纸作品沿着P1P2所在直线<br/>
折叠，并把有向线段P1P2的右边折向左边（左边的部分保持不变）。折叠结束后，需要在作品上打一个孔，然后用<br/>
绳子穿起来挂在墙上。孔的位置是相当重要的：若需要穿过太多层的纸，打孔本身比较困难；若穿过的层数太少，<br/>
悬挂起来以后作品可能会被撕破。为了选择一个比较合适的打孔位置，你需要计算在每个候选位置打孔时穿过的层<br/>
数。如果恰好穿过某一层的边界（误差0.000001内），则该层不统计在结果中。本题考虑一个简化的模型：纸的厚<br/>
度不计，因此折纸操作总能完美执行。</p></div>

# Input

<div class="content"><p>　　输入第一行为一个整数n，即折纸的次数。以下n行每行四个实数x1,y1,x2,y2，表示每次折纸时对应的有向线<br/>
段。下一行包含一个正整数m，即候选位置的个数，以下每行包含两个实数x,y，表示一个候选位置。0&lt;=n&lt;=8, 1&lt;=<br/>
m&lt;=50</p></div>

# Output

<div class="content"><p>　　每个候选位置输出一行，包含一个整数，即该位置打孔时穿过的层数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
-0.5 -0.5 1 1<br/>
1 75 0 75<br/>
6<br/>
10 60<br/>
80 60<br/>
30 40<br/>
10 10<br/>
50 50<br/>
20 50</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
2<br/>
2<br/>
0<br/>
0<br/>
2</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"><br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

