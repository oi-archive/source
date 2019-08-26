
# Description

<div class="content"><div>GHQ通过在24区引起基因组共鸣，从而引发了第二次失落的圣诞。</div>
<div>24区的地图可以视为一个二维平面。GHQ在24区布置了 架发射塔，而葬仪社也建立了 个据点。要阻止共鸣，需要顺次连接一些据点，连接的两个据点之间会形成屏障。所有屏障应构成一个多边形，称之为干扰场。干扰场的面积越大，起到的干扰效果就越强。</div>
<div>但是并非所有的连接方式都是有效的。其一，任意两块屏障不能在据点之外的位置相交；其二，干扰场中的任意一个位置都应该可以直接看到构成干扰场的所有据点。所谓直接看到是指视线不会穿过任意一块屏障。</div>
<div>更重要的一点是，干扰场内不能存在有GHQ布置的发射塔，而且屏障也不能穿过发射塔。如果这个条件不满足，干扰场根本无法发挥作用。</div>
<div>葬仪社需要设计一个构成干扰场的方案，使得干扰场的面积最大。请你协助他们。</div>
<p></p></div>

# Input

<div class="content"><div>输入文件的第一行包含两个整数 和 ，分别代表葬仪社的据点个数，以及GHQ设立的发射塔架数。</div>
<div>接下来 行，每行包含一个坐标，表示葬仪社的一个据点的位置。</div>
<div>接下来 行，每行包含一个坐标，表示GHQ布置的一架发射塔的位置。</div>
<div>坐标的每一维皆为绝对值不超过1000的整数。输入的任意两个坐标不相同。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>第一行输出一个非负实数，表示干扰场的最大面积。保留两位小数。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入1】<br/>
3 1<br/>
0 0<br/>
3 0<br/>
0 4<br/>
1 1<br/>
【样例输入2】<br/>
4 1<br/>
0 0<br/>
3 0<br/>
3 3<br/>
0 3<br/>
1 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">【样例输出1】<br/>
0.00<br/>
【样例1解释】<br/>
唯一的正面积干扰场是由据点1、2、3构成的，但是发射塔1在这个干扰场内部，所以不存在合法的正面积干扰场。<br/>
注意第三行的空行。<br/>
【样例输出2】<br/>
4.50<br/>
</span></div>

# Hint

<div class="content"><p></p><p>N&lt;=100,M&lt;=100</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

