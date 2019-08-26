
# Description

<div class="content"><div id="psrc" style="margin-top: 20px; display: none">
<div class="pdcont"></div>
<div id="pcont1" style="margin-top: 20px; display: block"></div>
</div>
<p><span style="font-size: medium">　　zz有一副神奇的三角板，三角板有两种形状：宽的(Wide)和窄的(Narrow)。三角板都是等腰三角形，宽的三角板底边为高的两倍，窄的三角板底边和高相等。<br/>
zz要把n个三角板依次放在桌面上。桌面可以抽象为一根数轴，zz把第i个三角板的底边置于数轴上(y坐标为0)，它的顶点坐标为(xi,yi)，那么，根据三角板的形状，就可以得到另外两个点的坐标了。<br/>
每放完一个三角板，zz就会数一遍，目前看得到几个三角板的顶点，如果顶点在其他三角板内(包括边界)，zz是看不见的。并且，当摆放第i个三角板时，如果(xi,yi)已经位于某三角板内，zz认为，这个三角板是放不下的，他便不会放入该三角板。<br/>
然而zz的三角板实在太多了，你能帮帮他吗？<br/>
</span></p></div>

# Input

<div class="content"><div id="pcont1" style="margin-top: 20px; display: block">
<div class="pdcont"><span style="font-size: medium">　　输入的第一行包含一个整数n。接下来n行表述每个三角板，第i行包含两个整数xi,yi和一个字符’W’(代表宽的三角板)或’N’(代表窄的三角板)(不包含引号)。<br/>
</span></div>
</div></div>

# Output

<div class="content"><div class="pdcont"><span style="font-size: medium">　　输出n行。若是第i个三角板能放得下，则输出一个整数，代表放入第i个三角板后看得见几个顶点；否则输出字符串”FAIL”(都为大写字母，不包含引号)<br/>
</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
0 1 W<br/>
0 2 N<br/>
0 1 W<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
1<br/>
FAIL<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据规模和约定<br/><br/>
30%的数据满足：n≤1000<br/><br/>
70%的数据满足：n≤40000<br/><br/>
100%的数据满足：1≤n≤100000、-10^9≤xi≤10^9、1≤yi≤10^9</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

