# 题目描述


<p>
【问题描述】<br/>
Louis.PS是一名精明的珠宝商，他出售的项链构造独特，很大程度上是因为他的制作方法与众不同。每次Louis.PS到达某个国家后，他会选择一条路径去遍历该国的城市。在到达一个城市后，他会使用在这个城市流行的材料制作一颗珠子，并按照城市被访问的顺序将珠子串联做成项链，为了使制作出来的项链不会因为城市之间的竞争而影响销量，路径中同一个城市不会重复出现(因为如果项链中A城市的材料比B城市的材料使用的多，则项链在B城市的宣传可能会受到影响)。经过多年对消费者的调查，Louis.PS已经掌握了判断一条项链吸引消费者程度的方法，具体来说，Louis.PS经过调查得出了受消费者欢迎的项链的特征，并基于此制作了一个长项链(Louis.PS称之为特征项链)。对于一条待售的项链，这条项链在特征项链里出现的次数越多，这条项链就越受消费者欢迎。<br/>
考虑到现实情况的复杂性，我们对条件做出适当的简化。对于每个国家：在某城市间存在道路直接相连,对于两个不同的城市,有且仅有一条路径连接这两个城市 (即国家是连通的，且不存在一个环)。对于每个城市，我们用一个小写字母来表示在这个城市流行的材料类型。这样，我们就可以用一个仅包含小写字母的字符串来表示一条项链，我们将特征项链所对应的字符串称作特征字符串，设为EigenString[1..M]，M为特征项链的长度。对于一条项链，假设其对应字符串为P[1..L]，L为这条项链的长度。如果在一个正整数K,使EigenString[K..K+L-1]=P[1..L],称这条项链在特征项链中出现了一次。满足上述条件的正整数K的个数即为这条项链在特征项链中出现次数,记为Popularity(P)。<br/>
Louis.PS使用数学中的期望概念来评价一个国家是否适合珠宝的采集，对于一个包含N个城市的国家，令Str<sub>u,v</sub>表示沿着从u开始，至v结束的路径所得到的项链的对应字符串。
</p>
<p>
(Str<sub>u,v</sub>与Str<sub>v,u</sub>表示的串一般不相同)，则Expectation=∑u,vPopularity(Str<sub>u,v</sub>)／N<sup>2</sup><br/>
对于如下的例子(图中实线表示两端点的国家有直接道路相连)：
</p>
<p>
<svg xmlns="http://www.w3.org/2000/svg" class="st5" color-interpolation-filters="sRGB" viewBox="0 0 125.456 46.8962" width="1.74244in" height="0.651336in" xmlns:xml="http://www.w3.org/XML/1998/namespace" xml:space="preserve">
	<v:documentproperties v:viewmarkup="false" v:metric="true" v:langid="2052"></v:documentproperties>
<style type="text/css">
	 .st1 {fill:#ffffff;stroke:#000000;stroke-linecap:round;stroke-linejoin:round;stroke-width:0.72} .st2 {fill:#000000;font-family:Times New Roman;font-size:1.00001em} .st3 {fill:none;stroke:none;stroke-linecap:round;stroke-linejoin:round;stroke-width:0.72} .st4 {stroke:#000000;stroke-linecap:round;stroke-linejoin:round;stroke-width:0.72} .st5 {fill:none;fill-rule:evenodd;font-size:12;overflow:visible;stroke-linecap:square;stroke-miterlimit:3} 
	</style>
<g xmlns:ns1="" ns1:v:index="1" xmlns:ns2="" ns2:v:groupcontext="foregroundPage" xmlns:ns3="" ns3:v:mid="0">
<title>
Page-1
</title>
<v:pageproperties v:shadowoffsety="-8.50394" v:shadowoffsetx="8.50394" v:drawingunits="24" v:pagescale="0.0393701" v:drawingscale="0.0393701"></v:pageproperties>
		<g id="shape1-1" transform="translate(46.783 -0.72)" xmlns:ns4="" ns4:v:groupcontext="shape" xmlns:ns5="" ns5:v:mid="1">
			<desc>a</desc>
			<v:textblock v:tabspace="42.5197" v:margins="rect(4,4,4,4)"></v:textblock>
			<v:textrect height="28.3465" width="28.35" cy="32.723" cx="14.1732"></v:textrect>
			<ellipse class="st1" cx="14.1732" cy="32.723" rx="14.1732" ry="14.1732"></ellipse>
			<text class="st2" x="11.51" y="36.32" xmlns:ns6="" ns6:v:langid="2052"><v:paragraph v:horizalign="1"></v:paragraph><v:tablist></v:tablist>a</text>		</g>
		<g id="shape2-4" transform="translate(4.26331 -0.72)" xmlns:ns7="" ns7:v:groupcontext="shape" xmlns:ns8="" ns8:v:mid="2">
			<desc>a</desc>
			<v:textblock v:tabspace="42.5197" v:margins="rect(4,4,4,4)"></v:textblock>
			<v:textrect height="28.3465" width="28.35" cy="32.723" cx="14.1732"></v:textrect>
			<ellipse class="st1" cx="14.1732" cy="32.723" rx="14.1732" ry="14.1732"></ellipse>
			<text class="st2" x="11.51" y="36.32" xmlns:ns9="" ns9:v:langid="2052"><v:paragraph v:horizalign="1"></v:paragraph><v:tablist></v:tablist>a</text>		</g>
		<g id="shape3-7" transform="translate(89.3027 -0.72)" xmlns:ns10="" ns10:v:groupcontext="shape" xmlns:ns11="" ns11:v:mid="3">
			<desc>b</desc>
			<v:textblock v:tabspace="42.5197" v:margins="rect(4,4,4,4)"></v:textblock>
			<v:textrect height="28.3465" width="28.35" cy="32.723" cx="14.1732"></v:textrect>
			<ellipse class="st1" cx="14.1732" cy="32.723" rx="14.1732" ry="14.1732"></ellipse>
			<text class="st2" x="11.18" y="36.32" xmlns:ns12="" ns12:v:langid="2052"><v:paragraph v:horizalign="1"></v:paragraph><v:tablist></v:tablist>b</text>		</g>
		<g id="shape4-10" transform="translate(0.72 -36.1531)" xmlns:ns13="" ns13:v:groupcontext="shape" xmlns:ns14="" ns14:v:mid="4">
			<desc>P2</desc>
			<v:textblock v:tabspace="42.5197" v:margins="rect(4,4,4,4)"></v:textblock>
			<v:textrect height="7.08661" width="35.44" cy="43.3529" cx="17.7165"></v:textrect>
			<rect class="st3" x="0" y="39.8096" width="35.4331" height="7.08661"></rect>
			<text class="st2" x="11.39" y="46.95" xmlns:ns15="" ns15:v:langid="2052"><v:paragraph v:horizalign="1"></v:paragraph><v:tablist></v:tablist>P2</text>		</g>
		<g id="shape5-13" transform="translate(43.2397 -36.1531)" xmlns:ns16="" ns16:v:groupcontext="shape" xmlns:ns17="" ns17:v:mid="5">
			<desc>P1</desc>
			<v:textblock v:tabspace="42.5197" v:margins="rect(4,4,4,4)"></v:textblock>
			<v:textrect height="7.08661" width="35.44" cy="43.3529" cx="17.7165"></v:textrect>
			<rect class="st3" x="0" y="39.8096" width="35.4331" height="7.08661"></rect>
			<text class="st2" x="11.39" y="46.95" xmlns:ns18="" ns18:v:langid="2052"><v:paragraph v:horizalign="1"></v:paragraph><v:tablist></v:tablist>P1</text>		</g>
		<g id="shape6-16" transform="translate(89.3027 -36.1531)" xmlns:ns19="" ns19:v:groupcontext="shape" xmlns:ns20="" ns20:v:mid="6">
			<desc>P3</desc>
			<v:textblock v:tabspace="42.5197" v:margins="rect(4,4,4,4)"></v:textblock>
			<v:textrect height="7.08661" width="35.44" cy="43.3529" cx="17.7165"></v:textrect>
			<rect class="st3" x="0" y="39.8096" width="35.4331" height="7.08661"></rect>
			<text class="st2" x="11.39" y="46.95" xmlns:ns21="" ns21:v:langid="2052"><v:paragraph v:horizalign="1"></v:paragraph><v:tablist></v:tablist>P3</text>		</g>
		<g id="shape7-19" transform="translate(46.783 78.8992) rotate(180)" xmlns:ns22="" ns22:v:groupcontext="shape" xmlns:ns23="" ns23:v:mid="7">
			<path class="st4" d="M 0 46.9 L 14.17 46.9"></path>
		</g>
		<g id="shape8-22" transform="translate(75.1294 -14.8932)" xmlns:ns24="" ns24:v:groupcontext="shape" xmlns:ns25="" ns25:v:mid="8">
			<path class="st4" d="M 0 46.9 L 14.17 46.9"></path>
		</g>
	</g>
</svg>
</p>
<p>
N=3，所流行的材料类型分别为a,a,b。
</p>
<p>
<br/>
EigenString=”abaab”<br/>
Str(3，1)=ba Popularity(ba)=1<br/>
Str(1，1)=a Popularity(ba)=3<br/>
Str(1，2)=aa Popularity(ba)=1<br/>
Str(1，3)=ab Popularity(baa)=2<br/>
Str(2，1)=aa Popularity(ba)=1<br/>
Str(2，2)=a Popularity(ba)=3<br/>
Str(2，3)=aab Popularity(ba)=1<br/>
Str(3，1)=ba Popularity(ba)=1<br/>
Str(3，2)=baa Popularity(baa)=1<br/>
Str(3，3)=b Popularity(b)=2
</p>
<p>
Expectation=(3+1+2+1+3+1+1+1+2)/9=5/3<br/>
对于一个国家，Louis.PS想知道其Expectation的值，但苦于计算期望的工作量太大。作为珠宝店的学徒，你当然不愿放过难得在老板面前展示自己的机会。<br/>
【输入文件】<br/>
输入文件jewelry.in，第一行包含两个整数N，M，表示城市个数及特征项链的长度。<br/>
接下来的N-1行,每行两个整数x,y 表示城市x与城市y有直道接路相连。城市由1～N进行编号。<br/>
接下来的一行，包含一个长度为N，仅包含小写字母的字符串，第i位的字符表示在城市i流行的原料类型。<br/>
最后一行，包含一个长度为M，仅包含小写字母的字符串，表示特征字符串。<br/>
【输出文件】<br/>
输出文件jewelry.out，仅包含一个整数，为N2*Expectation。<br/>
【样例输入】<br/>
3 5<br/>
1 2<br/>
1 3<br/>
aab<br/>
abaab<br/>
【样例输出】<br/>
15<br/>
【数据规模】<br/>
有20％的数据，满足M&lt;= 1000；<br/>
有40％的数据，满足N≤8000，M≤50000；<br/>
对于100％的数据，N，M≤50000。
</p>
<p>
<br/>
</p>
