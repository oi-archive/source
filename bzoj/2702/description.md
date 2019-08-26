
# Description

<div class="content"><div style="text-indent: 27pt; line-height: 150%"><span style="font-size: medium"><span style="line-height: 150%">在这次金融危机爆发之前，小</span><span style="line-height: 150%">L</span><span style="line-height: 150%">就有预感。她准确地预测到了爆发地点以及扩散的形式和速度。因此，金融危机爆发时，小</span><span style="line-height: 150%">L</span><span style="line-height: 150%">的很多好友都马上来找她帮忙，希望尽可能晚的遭到金融风暴的影响。</span></span></div>
<div style="text-indent: 27pt; line-height: 150%"><span style="font-size: medium"><span style="line-height: 150%">为了简化问题，我们将地球变成二维平面（坐标值非负。最左与最右，最上与最下不可直接互达）。每个整点都为一个城市。在第</span><span style="line-height: 150%">0</span><span style="line-height: 150%">时刻只有</span><span style="line-height: 150%">N</span><span style="line-height: 150%">个金融中心爆发了金融风暴，第</span><span style="line-height: 150%">i</span><span style="line-height: 150%">个金融中心是坐标</span><span style="line-height: 150%">(xi,yi)</span><span style="line-height: 150%">。金融风暴扩散的方式是以金融中心为圆心做均匀的圆扩散。即世界上每个城市受到第</span><span style="line-height: 150%">i</span><span style="line-height: 150%">个金融风暴影响的时间为这个城市与这场风暴中心（</span><span style="line-height: 150%">xi,yi</span><span style="line-height: 150%">）的欧几里德距离。注意，地球外没有城市，金融危机也不会爆发到地球外面</span><span style="line-height: 150%">XD</span><span style="line-height: 150%">。</span></span></div>
<div style="text-indent: 27pt; line-height: 150%"><span style="font-size: medium"><span style="line-height: 150%">小</span><span style="line-height: 150%">L</span><span style="line-height: 150%">希望你写个程序来帮帮她。</span></span></div>
<div style="text-indent: 27pt; line-height: 150%"><span style="font-size: medium"><span style="line-height: 150%">现有</span><span style="line-height: 150%">t</span><span style="line-height: 150%">个好友希望小</span><span style="line-height: 150%">L</span><span style="line-height: 150%">帮忙，因为各个人所在的不同地方以及国家大小原因。你需要告诉她与第</span><span style="line-height: 150%">i</span><span style="line-height: 150%">个好友所在的</span><span style="line-height: 150%">(pi,qi)</span><span style="line-height: 150%">横纵坐标距离不超过</span><span style="line-height: 150%">si</span><span style="line-height: 150%">的所有城市（即</span><span style="line-height: 150%">{(a,b)|max{|a-pi|</span><span style="line-height: 150%">，</span><span style="line-height: 150%">|b-qi|}&lt;=si}</span><span style="line-height: 150%">）中，最晚遭受金融风暴影响的城市开始爆发金融危机的时间（为严格定义，如果需要覆盖到地球外的区域，则输出</span><span style="line-height: 150%">-1</span><span style="line-height: 150%">）。</span></span></div>
<div style="line-height: 150%"><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div style="text-indent: 6pt; line-height: 150%"><span style="font-size: medium"><span style="line-height: 150%">   </span><span style="line-height: 150%">第一行两个数，地图大小</span><span style="line-height: 150%">w,h</span></span></div>
<div style="text-indent: 6pt; line-height: 150%"><span style="font-size: medium"><span style="line-height: 150%">   </span><span style="line-height: 150%">第二行一个数</span><span style="line-height: 150%">N</span><span style="line-height: 150%">，金融中心坐标</span></span></div>
<div style="text-indent: 6pt; line-height: 150%"><span style="font-size: medium"><span style="line-height: 150%">   </span><span style="line-height: 150%">接下来</span><span style="line-height: 150%">N</span><span style="line-height: 150%">行，</span><span style="line-height: 150%">(xi,yi)   0&lt;=xi&lt;=w, 0&lt;=yi&lt;=h</span></span></div>
<div style="text-indent: 6pt; line-height: 150%"><span style="font-size: medium"><span style="line-height: 150%">   </span><span style="line-height: 150%">第</span><span style="line-height: 150%">N+3</span><span style="line-height: 150%">行一个数</span><span style="line-height: 150%">t</span><span style="line-height: 150%">，为询问数</span></span></div>
<div style="text-indent: 6pt; line-height: 150%"><span style="font-size: medium"><span style="line-height: 150%">   </span><span style="line-height: 150%">接下来</span><span style="line-height: 150%">t</span><span style="line-height: 150%">行，每行三个数，</span><span style="line-height: 150%">(pi,qi)</span><span style="line-height: 150%">表示好友的坐标，</span><span style="line-height: 150%">si</span><span style="line-height: 150%">如题中描述意义。</span></span></div>
<div style="text-indent: 6pt; line-height: 150%"><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div style="text-indent: 6pt; line-height: 150%"><span style="font-size: medium"><span style="line-height: 150%">   t</span><span style="line-height: 150%">行，每行一个数</span><span style="line-height: 150%">time</span><span style="line-height: 150%">如题中描述。（保留</span><span style="line-height: 150%">3</span><span style="line-height: 150%">位小数）</span></span></div>
<div style="text-indent: 6pt; line-height: 150%"><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">    4 4<br/>
    1<br/>
    2 2<br/>
    3<br/>
    2 2 0<br/>
    2 2 1<br/>
    2 2 3<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">    0.000<br/>
    1.414<br/>
    -1<br/>
 <br/>
【数据说明】<br/>
 20% 0&lt;=w,h&lt;=100<br/>
1&lt;=N,t&lt;=1000<br/>
60% 1&lt;=t&lt;=200000<br/>
100% 0&lt;=w,h&lt;=1000<br/>
1&lt;=N,t&lt;=1000000</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

