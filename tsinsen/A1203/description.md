<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Antonio制作了一串非常大的珠链。这串珠链由N颗珠子构成，并通过N条细线串连起来。每条细线能够串起两颗不同的珠子，而且任意两颗不同的珠子之间最多只会有一条细线相连。与此同时，这串珠链还满足一个性质，那就是从任意一颗珠子出发，通过一条或者多条细线，可以到达其中所有的珠子。<br/>
<br/>
<img width="122" height="96" src="source/tsinsen/A1203/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9NUpZZm4yeWg=.do"/><br/>
　　Antonio意识到在它的珠链中，有的节点通过若干条细线还能够走回本身（同一条细线不能经过两次）。所有满足这个性质的节点的集合被称为环，这些节点本身被称作环上的节点。如在右图中，红色标记的节点的集合就构成这个图的环，在这个图中共有6个环上的节点。<br/>
　　现在，Antonio准备把他的珠链进行一下分割。首先，他给每一颗珠子都赋上了一个1~100（含）的正整数，代表这颗珠子的价值。然后，他通过下面的步骤进行分割：<br/>
　　1、 切断若干条细线，把整个珠链分割成K个部分。每个部分都满足连通性（i.e. 从该部分内任意一个节点出发通过一条或者多条细线可以到达该部分中的所有其他节点）。<br/>
　　2、 选择K个部分中的一个，把这个部分中所有环上的节点的价值分别平方。<br/>
　　然后，Antonio会把这K个部分送给他的K个好友，且每个好友的满意度等于他/她收到的所有珠子的价值的总和。Antonio希望每个好友都能对他的礼物充分满意，所以他希望最大化满意度最低的好友的满意度。请你设计一个程序，向Antonio指出这个值。</div>
# 输入格式

<div class="pdcont">　　由于输入规模可能会很大，故采用两种模式进行输入。<br/>
　　输入模式A：<br/>
　　输入文件第一行有且仅有一个字母A，表示用A模式进行输入。<br/>
　　第二行，两个用空格隔开的正整数，N和K。含义如试题描述中所述。<br/>
　　接下来一行，N个用空格隔开的正整数，均不超过100，表示每个珠子的价值。<br/>
　　接下来N行，每行两个整数，代表细线连接的两颗珠子的编号。珠子按照第三行输入的顺序从1到N进行编号。<br/>
<br/>
　　输入模式B：<br/>
　　输入文件第一行有且仅有一个字母B，表示用B模式进行输入。<br/>
　　第二行，两个用空格隔开的正整数，N和K。含义如试题描述中所述。<br/>
　　在输入模式B中，图的结构是固定的。所有的节点按照1~N依次编号，而细线则为(1,2), (2,3), ..., (N-1,N), ..., (N,1)，即一个首尾相连的大环。<br/>
　　第三行，四个正整数，V,A,B,C，每个数都不超过10<sup>9</sup>. 依照下列规则产生一个长度为N的数列：<br/>
　　P<sub>1</sub>=V<br/>
　　P<sub>j</sub>=(AP<sub>j-1</sub>+B)mod C,(1&lt;j≤N)<br/>
　　然后通过P数列确定每个珠子的价值。编号为j的珠子的价值<br/>
<br/>
　　Value[j]=(p<sub>j</sub> mod 97)+1, (1≤j≤N)<br/>
　　（注意：你必须要使用64位整数来产生P数列。对于Pascal选手来说，你必须使用int64类型，对于C++选手来说，你必须使用long long类型）<br/>
　　另外，建议C++选手使用scanf()进行读入，以减小读入过程的时间消耗。</div>
# 输出格式

<div class="pdcont">　　输出文件有且仅有一行，只包含一个整数，表示最小的满意度所可能取到的最大值。输入数据保证这个数不超过2<sup>31</sup>-1。</div>
# 样例输入

<div class="pddata">A<br/>
6 4<br/>
12 2 2 2 12 12<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 2<br/>
3 5<br/>
4 6</div>
# 样例输出

<div class="pddata">12</div>
# 样例输入

<div class="pddata">A<br/>
5 3<br/>
8 8 2 1 1<br/>
1 2<br/>
2 3<br/>
3 1<br/>
3 4<br/>
3 5</div>
# 样例输出

<div class="pddata">6</div>
# 样例输入

<div class="pddata">B<br/>
5 2<br/>
1 1 1 10000000000</div>
# 样例输出

<div class="pddata">11</div>
# 样例输入

<div class="pddata">B<br/>
100 10<br/>
1039203 4398234 3930493 1000000003</div>
# 样例输出

<div class="pddata">542</div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">数据点<br/>
</td><td valign="top" style="border:solid 1.0pt">N<br/>
</td><td valign="top" style="border:solid 1.0pt">K<br/>
</td><td valign="top" style="border:solid 1.0pt">输入模式<br/>
</td><td valign="top" style="border:solid 1.0pt">数据点<br/>
</td><td valign="top" style="border:solid 1.0pt">N<br/>
</td><td valign="top" style="border:solid 1.0pt">K<br/>
</td><td valign="top" style="border:solid 1.0pt">输入模式<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">0<br/>
</td><td valign="top" style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">1≤K≤N<br/>
</td><td valign="top" style="border:solid 1.0pt">A<br/>
</td><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">50000<br/>
</td><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">B<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">30<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
1≤K≤N<br/>
</td><td valign="top" style="border:solid 1.0pt">A<br/>
</td><td valign="top" style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">50000<br/>
</td><td valign="top" style="border:solid 1.0pt">1000<br/>
</td><td valign="top" style="border:solid 1.0pt">B<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">100<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
1≤K≤N<br/>
</td><td valign="top" style="border:solid 1.0pt">A<br/>
</td><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">50000<br/>
</td><td valign="top" style="border:solid 1.0pt">45000<br/>
</td><td valign="top" style="border:solid 1.0pt">B<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">1000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
1≤K≤N<br/>
</td><td valign="top" style="border:solid 1.0pt">A<br/>
</td><td valign="top" style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">300000<br/>
</td><td valign="top" style="border:solid 1.0pt">100<br/>
</td><td valign="top" style="border:solid 1.0pt">B<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">10000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
1≤K≤N<br/>
</td><td valign="top" style="border:solid 1.0pt">A<br/>
</td><td valign="top" style="border:solid 1.0pt">9<br/>
</td><td valign="top" style="border:solid 1.0pt">300000<br/>
</td><td valign="top" style="border:solid 1.0pt">10000<br/>
</td><td valign="top" style="border:solid 1.0pt">B<br/>
</td></tr></tbody></table></div>
# 样例说明

<div class="pdcont"><img width="456" height="422" src="source/tsinsen/A1203/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9OW1iR0hER0E=.do"/></div>
# 特别提醒

<div class="pdcont">　　只有一个部分中节点的权值可以被平方，请仔细观察样例3。<br/>
　　只有环上的节点的权值才能够被平方，请仔细观察样例2。<br/>
　　节点需要分别被平方，请仔细观察样例1。</div>

</div>