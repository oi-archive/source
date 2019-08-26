
# Description

<div class="content"><div>喜欢几何的小付遇到了这样一个问题：一天他在一张白纸上画了n条直线，然后剪了一张m边</div>
<div>形（简单多边形）的小纸片。他想把这张小纸片放在白纸上，使它盖住的线段的总长度最长</div>
<div>。并且这张多边形纸片不能翻转或旋转，只能平移，如果直线的某一段刚好与多边形纸片的</div>
<div>边重合，那么，这条线段算作是被覆盖。你能帮他解决这个问题吗？</div></div>

# Input

<div class="content"><div>第一行为两个数n和m，其中1&lt;=n，m&lt;=10，分别表示直线的数目和多边形的边数。</div>
<div>接下来的n行分别表示各条直线，每行有4个实数x1，y1，x2，y2，</div>
<div>表示一条经过(x1，y1)和(x2，y2)的直线。</div>
<div>接下来的m行按顺时针或逆时针的顺序输入多边形的各个顶点，</div>
<div>每行有2个实数x，y，表示一个顶点的坐标。</div>
<div>这里假设所有输入的实数都在-10000到10000之间，且不会超过2位小数，</div>
<div>输入的多边形保证不自交，且连续的3点不共线。</div></div>

# Output

<div class="content"><p>仅包含一个数L，表示输入的多边形能盖住的最大的线段总长度，精确到小数点后3位。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 5                                     <br/>
6 1 2 5<br/>
1 2 8 4<br/>
4 -1 5 6<br/>
1 0<br/>
5 -1<br/>
4 2<br/>
7 3<br/>
4 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">11.933</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

