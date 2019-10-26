
# Description

<div class="content"><div>
<div>使用过Android手机的同学一定对手势解锁屏幕不陌生。Android的解锁屏幕由3x3个点组成，手指在屏幕上画一条</div>
<div>线将其中一些点连接起来，即可构成一个解锁图案。如下面三个例子所示：</div>
<div><img src="/source/bzoj/5299/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwNC92MS5qcGc=.jpg" width="469" height="161" alt=""/></div>
<div>画线时还需要遵循一些规则</div>
<div>1．连接的点数不能少于4个。也就是说只连接两个点或者三个点会提示错误。</div>
<div>2．两个点之间的连线不能弯曲。</div>
<div>3．每个点只能&#34;使用&#34;一次，不可重复。这里的&#34;使用&#34;是指手指划过一个点，该点变绿。</div>
<div>4．两个点之间的连线不能&#34;跨过&#34;另一个点，除非那个点之前已经被&#34;使用&#34;过了。</div>
<div>对于最后一条规则，参见下图的解释。左边两幅图违反了该规则：而右边两幅图(分别为2→4→1→3→6和→5→4→1→9→2)</div>
<div>则没有违反规则，因为在&#34;跨过&#34;点时，点已经被&#34;使用&#34;过了。</div>
<div><img src="/source/bzoj/5299/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwNC92Mi5qcGc=.jpg" width="316" height="110" alt=""/></div>
<div>现在工程师希望改进解锁屏幕，增减点的数目，并移动点的位置，不再是一个九宫格形状，但保持上述画线的规则不变。</div>
<div>请计算新的解锁屏幕上，一共有多少满足规则的画线方案。</div>
</div>
<div></div></div>

# Input

<div class="content"><div>输入文件第一行，为一个整数n，表示点的数目。</div>
<div>接下来n行，每行两个空格分开的整数xi和yi，表示每个点的坐标。</div>
<div>-1000≤xi,Yi≤l000，1≤n&lt;20。各点坐标不相同</div>
<div></div></div>

# Output

<div class="content"><div>输出文件共一行，为题目所求方案数除以100000007的余数。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
0 0<br/>
1 1<br/>
2 2<br/>
3 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
解释：设4个点编号为1到4，方案有1→2→3→4，2→1→3→4，3→2→1→4，2→3→1→4，<br/>
及其镜像4→3→2→1,3→4→2→1,2→3→4→1,3→2→4→1.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Amphetamine整理题面">鸣谢Amphetamine整理题面</a></p></div>

