<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给定一个树型电网，树中的每条边上有一个电阻<i>R<sub>i</sub></i>，电阻值均为10000Ω。下图为一个包含4个节点的树型电路情况：<br/>
<img src="source/tsinsen/A1345/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9NFRNODZqMkE=.do" width="310" height="211"/><br/>
<br/>
　　树中的所有叶子节点（度为1的节点称为叶子节点）都接地，每条接地线上都附有10000Ω的电阻，最终形成的电网如下图所示：<br/>
<img src="source/tsinsen/A1345/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9TERmRGI2NlQ=.do" width="330" height="344"/><br/>
<br/>
　　现有如下两种操作：<br/>
　　C <i>u v w </i>：表示在边&lt;<i>u</i>,<i>v</i>&gt;上串联一个电源，电源的大小为<i>w</i>伏，电源位于靠近节点<i>u</i>一侧（如下图所示），电源负极指向<i>u</i>。注意同一条边上可以串联多个电源。<br/>
<img src="source/tsinsen/A1345/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9NHJ5M2RiYTc=.do" width="421" height="72"/><br/>
<br/>
　　Q<i> u</i> ：表示询问点<i>u</i>当前的电压，此电压是指对地电压。<br/>
<br/>
　　如对上图进行C 2 4 5操作后，网络变为：<br/>
<br/>
<img src="source/tsinsen/A1345/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9dEVFcVFZcXQ=.do" width="366" height="397"/><br/>
　　此时每个节点上的电压见上图的标注。</div>
# 输入格式

<div class="pdcont">　　输入第一行包含两个整数<i>N</i>,<i>M</i>，分别表示树的节点数和操作个数。接下来<i>N</i>-1行，每行两个数<i>u</i>,<i>v</i>，表示有一条连接节点<i>u</i>,<i>v</i>的边，这条边上恰好包含一个电阻。<br/>
　　接下来<i>M</i>行，每行一个命令，格式见题目描述。</div>
# 输出格式

<div class="pdcont">　　对于每个Q命令，输出一个数表示此刻该点的电压值。你可以输出任意多位的小数，只要你的答案和标准答案相差不超过10<sup>-3</sup>就算合法。<br/>
<br/>
<br/>
<b> </b></div>
# 样例输入

<div class="pddata">4 3<br/>
1 2<br/>
2 3<br/>
2 4<br/>
Q 2<br/>
C 2 4 5<br/>
Q 2</div>
# 样例输出

<div class="pddata">0.0000000000<br/>
-1.6666666666</div>
# 样例说明

<div class="pdcont">　　对于第一个询问，由于原图中没有电源，所以没有电流，所有点的电压都相等（否则如果有<i>U<sub>i</sub></i>&gt;<i>U<sub>j</sub></i>，则就有<i>i</i>流向<i>j</i>的电流，与没有电源矛盾）,都等于地电压0V。<br/>
　　之后在&lt;2,4&gt;中加一个5V的电源，得到的新图见题目描述。<br/>
　　整理后可以发现，新图的形式是串联(电源,<i>R<sub>2</sub></i>+10000,并联(<i>R<sub>1</sub></i>+10000, <i>R<sub>3</sub></i>+10000))，由此可以得到新图的总电阻为:<br/>
　　<i>R<sub>2</sub></i>+10000+1/(1/(<i>R<sub>3</sub></i>+10000)+1/(<i>R<sub>1</sub></i>+10000))=30000 Ω.<br/>
　　所以流过节点4的电流就是5/30000A，所以<i>U<sub>4</sub></i>=5/3V。<i>U<sub>2</sub></i>=<i>U<sub>4</sub></i>+<i>R<sub>2</sub></i>*<i>I</i>-5=-5/3V，由于<i>U<sub>1</sub></i>和<i>U<sub>3</sub></i>形式对称，由分压关系可知<i>U<sub>1</sub></i>=<i>U<sub>3</sub></i>=<i>U<sub>2</sub></i>*10000/(10000+10000)=-5/6V。</div>
# 数据规模和约定

<div class="pdcont">　　30%的数据保证<i>N</i>,<i>M</i> ≤ 30<br/>
　　60%的数据保证<i>N</i>,<i>M</i> ≤ 3000<br/>
　　100%的数据保证3 ≤ <i>N</i>,<i>M</i> ≤ 50000，1 ≤ <i>u</i>,<i>v</i> ≤ <i>n</i>，1 ≤ <i>w</i> ≤ 10，树中最长链的长度不超过50。</div>

</div>