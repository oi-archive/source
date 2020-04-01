
# Description

<div class="content"><div>无线网络基站在理想状况下有效信号覆盖范围是个圆形。而无线基站的功耗与圆的半径的平方成正比。现给出平面</div>
<div>上若干网络用户的位置,请你选择一个合适的位置建设无线基站....就在你拿起键盘准备开始敲代码的时候,你的好</div>
<div>朋友发明家 SHTSC 突然出现了。SHTSC 刚刚完成了他的新发明——无线信号增幅仪。增幅仪能够在不增加无线基</div>
<div>站功耗的前提下,使得有效信号的覆盖范围在某一特定方向上伸长若干倍。即:使用了增幅仪的无线基站覆盖范围是</div>
<div>个椭圆,其功耗正比于半短轴长的平方。现给出平面上若干网络用户的位置,请你选择一个合适的位置建设无线基站</div>
<div>,并在增幅仪的帮助下使所有的用户都能接收到信号,且无线基站的功耗最小。注意:由于SHTSC 增幅仪的工作原理</div>
<div>依赖地磁场,增幅的方向是恒定的。</div></div>

# Input

<div class="content"><div>第一行一个整数:n。平面内的用户个数。之后的 n 行每行两个整数 x, y,表示一个用户的位置。第 n+2 行一个整</div>
<div>数:a。表示增幅仪的增幅方向,单位是度。表示增幅仪的方向是从 x 正方向逆时针转 a 度。第 n+3 行一个整数:p</div>
<div>。表示增幅仪的放大倍数。</div></div>

# Output

<div class="content"><p>输出一行一个实数,为能够覆盖所有用户的最小椭圆的半短轴长,四舍五入到三位小数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">样例一：<br/>
2<br/>
1 0 <br/>
-1 0 <br/>
0 <br/>
2 </span></div>

# Sample Output

<div class="content"><span class="sampledata">样例一：<br/>
0.500</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">对于 100%的数据,n≤50000,0≤a&lt;180,1≤p≤100,|x|,|y|≤2×10^8。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

