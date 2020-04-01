<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　小A喜欢收集宝物。一天他得到了一个圆环，圆环上有N颗彩色宝石，闪闪发光。小A很爱惜这个圆环，天天把它带在身边。<br/>
　　一天，小A突然发现圆环上宝石的颜色是会变化的。他十分惊讶，仔细观察这个圆环后发现，圆环上宝石的颜色每天变化一次，而且每颗宝石的颜色都等概率地为特定的M种颜色之一。小A发现了这个秘密后，对圆环更是爱不释手，时时刻刻都在研究。<br/>
　　又经过了一段时间，小A发现因为圆环上宝石的颜色不断变化，圆环有时会显得比其他时候更美丽。为了方便比较，小A这样定义圆环的“美观程度”：<br/>
　　设圆环上相同颜色的宝石构成的连续段长度分别为a<sub>1</sub>, <i>a</i><sub>2</sub>, ..., <i>a<sub>n</sub></i>；<br/>
　　定义圆环的“美观程度”<img width="232" height="33" src="source/tsinsen/A1202/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9UXJUODVqUlI=.do"/>  。以图一给出的圆环为例，有a<sub>1 </sub>= 3, <i>a</i><sub>2 </sub>= 2, <i>a</i><sub>3 </sub>= 1，故<i>R</i> = 6。<br/>
<img width="139" height="119" src="source/tsinsen/A1202/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9RW1nVGdlRk0=.do"/><br/>
　　图一<br/>
　　现在小A想知道，在上述前提下，圆环的“美观程度”的期望值E(R)是多少。因为如果知道了E(R)，他就可以判断每天变化出的新圆环是否比一般情况更美丽。<br/>
　　说明：“美观程度”的期望值即为对每种可能的圆环状态的“美观程度”与其出现概率的乘积进行求和所得的值。</div>
# 输入格式

<div class="pdcont">　　输入仅有一行，该行给出依次两个正整数N, M，分别表示宝石的个数和宝石在变化时可能变成的颜色种类数。</div>
# 输出格式

<div class="pdcont">　　输出应仅有一行，该行给出一个实数E(R)，表示圆环的“美观程度”的期望值。</div>
# 样例输入

<div class="pddata">3 2</div>
# 样例输出

<div class="pddata">2.25</div>
# 样例输入

<div class="pddata">200 1</div>
# 样例输出

<div class="pddata">200</div>
# 数据规模和约定

<div class="pdcont">　　20%的数据满足1 ≤ N, M ≤ 8；<br/>
　　50%的数据满足1 ≤ N, M ≤ 25；<br/>
　　100%的数据满足1 ≤ N ≤ 200, 1 ≤ M ≤10<sup>9</sup>。</div>
# 评分标准

<div class="pdcont">　　对每个测试点，若你给出的E(R)与标准程序给出的E(R)’的相对误差不超过10-7，则该测试点得满分；否则该测试点得零分。<br/>
　　说明：相对误差  <img width="122" height="54" src="source/tsinsen/A1202/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9aGo3ZTc4cmg=.do"/></div>

</div>