# 题目描述


<p style="text-indent:32.0000pt;">
	<span style="font-weight:bold;font-size:16.0000pt;font-family:&#39;宋体&#39;;">通讯线路<span>(line)</span></span><span style="font-weight:bold;font-size:16.0000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<h1>
	<span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">题目描述：</span><span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span>
</h1>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">某地区共有</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">n</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">座村庄，每座村庄的坐标用一对整数</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">(x, y)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">表示，现在要在村庄之间建立通讯网络。通讯工具有两种，分别是需要铺设的普通线路和卫星设备。卫星设备数量有限，只能给</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">k</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">个村庄配备卫星设备。拥有卫星设备的村庄互相间直接通讯；铺设了线路的村庄之间也可以通讯。卫星分配是不受限制的。</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p style="text-indent:20.5800pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">问怎样合理的分配卫星和铺设线路，使得在保证每两座村庄之间都可以直接或间接地通讯的前提下，铺设线路的总长度最短。</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p style="text-indent:20.6000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">范围：</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">≤</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">k</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">≤</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">n</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">≤<span>2</span></span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">000</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">输入数据：</span><span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第一行两个数</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">,n,k</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">接下来</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">n</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">行，每行两个数描述一个村庄。</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">输出数据：</span><span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">仅一行，代表总长度，精确到</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">0.0001</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">输入样例：</span><span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">20 8</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">137 824</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">761 14</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">68 151</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">194 758</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">149 138</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">314 90</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">809 404</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">964 877</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">471 66</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">177 546</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">73 977</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">397 560</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">928 653</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">199 486</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">736 44</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">985 801</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">621 509</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">444 140</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">88 508</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">556 327</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">输出样例：</span><span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1355.4195</span>
</p>
<p>
	<br/>
</p>
<p>
	中小学电脑报<span> NOI导刊 NOIP2012河南省实验中学培训 Day4 Exercise Problem 13</span><br/>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
