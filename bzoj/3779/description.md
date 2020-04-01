
# Description

<div class="content"><div><span style="font-family: arial, verdana, helvetica, sans-serif;">黑客们通过对已有的病毒反编译，将许多不同的病毒重组，并重新编译出了新型的重组病毒。这种病毒的繁殖和变异能力极强。为了阻止这种病毒传播，某安全机构策划了一次实验，来研究这种病毒。</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">实验在一个封闭的局域网内进行。局域网内有n台计算机，编号为1~n。一些计算机之间通过网线直接相连，形成树形的结构。局域网中有一台特殊的计算机，称之为核心计算机。根据一些初步的研究，研究员们拟定了一个一共m步的实验。实验开始之前，核心计算机的编号为1，每台计算机中都有病毒的一个变种，而且每台计算机中的变种都不相同。实验中的每一步会是下面中的一种操作：</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">1、	RELEASE x</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">在编号为x的计算机中植入病毒的一个新变种。这个变种在植入之前不存在于局域网中。</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">2、	RECENTER x</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">将核心计算机改为编号为x的计算机。但是这个操作会导致原来核心计算机中的病毒产生新变种，并感染过来。换言之，假设操作前的核心计算机编号为y，相当于在操作后附加了一次RELEASE y的操作。</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">根据研究的结论，在植入一个新变种时，病毒会在局域网中搜索核心计算机的位置，并沿着网络中最短的路径感染过去。</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">而第一轮实验揭露了一个惊人的真相：病毒的不同变种是互斥的。新变种在感染一台已经被旧变种感染的电脑时，会把旧变种完全销毁之后再感染。但研究员发现了实现过程中的漏洞。如果新变种在感染过程中尚未销毁过这类旧变种，需要先花费1单位时间分析旧变种，才能销毁。如果之前销毁过这类旧变种，就可以认为销毁不花费时间。病毒在两台计算机之间的传播亦可认为不花费时间。</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">研究员对整个感染过程的耗时特别感兴趣，因为这是消灭病毒的最好时机。于是在m步实验之中，研究员有时还会做出如下的询问：</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">3、	REQUEST x</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">询问如果在编号为x的计算机的关键集合中的计算机中植入一个新变种，平均感染时间为多长。编号为y的计算机在编号为x的计算机的关键集合中，当且仅当从y沿网络中的最短路径感染到核心计算机必须经过x。由于有RECENTER操作的存在，这个集合并不一定是始终不变的。</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">至此，安全机构认为已经不需要实际的实验了，于是他们拜托你编写一个程序，模拟实验的结果，并回答所有的询问。</span></div>
<p></p></div>

# Input

<div class="content"><div><span style="font-size: 11.8181819915771px; font-family: arial, verdana, helvetica, sans-serif;">输入的第一行包含两个整数n和m，分别代表局域网中计算机的数量，以及操作和询问的总数。</span><br style="font-size: 11.8181819915771px; font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-size: 11.8181819915771px; font-family: arial, verdana, helvetica, sans-serif;">接下来n-1行，每行包含两个整数x和y，表示局域网中编号为x和y的计算机之间有网线直接相连。</span><br style="font-size: 11.8181819915771px; font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-size: 11.8181819915771px; font-family: arial, verdana, helvetica, sans-serif;">接下来m行，每行包含一个操作或者询问，格式如问题描述中所述。</span></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每个询问，输出一个实数，代表平均感染时间。输出与答案的绝对误差不超过 10^(-6)时才会被视为正确。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">8 6<br/>
1 2<br/>
1 3<br/>
2 8<br/>
3 4<br/>
3 5<br/>
3 6<br/>
4 7<br/>
REQUEST 7<br/>
RELEASE 3<br/>
REQUEST 3<br/>
RECENTER 5<br/>
RELEASE 2<br/>
REQUEST 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">4.0000000000<br/>
2.0000000000<br/>
1.3333333333<br/>
</span></div>

# Hint

<div class="content"><p></p><p>N &lt; = 1 00 000 M &lt; = 1 00 000</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

