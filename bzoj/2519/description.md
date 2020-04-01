
# Description

<div class="content"><div style="margin: 6pt 0cm 12pt; text-indent: 21pt; line-height: 150%"><span style="font-size: medium">SHOI的领队为了方便大家交流，决定在大家集训的机房里建立起一个局域网络。现在的机房里一共有n台电脑终端，SHOI的领队使用了m条网线去建立这个局域网，每条网线都把某两台电脑连接起来使得它们可以双向通信。现在这个网络是连通的，也就是说，任意两台电脑之间都可以直接的或间接的通信。</span></div>
<div style="margin: 6pt 0cm 12pt; text-indent: 21pt; line-height: 150%"><span style="font-size: medium">为了在整个备战过程中，确保所有学生之间通过这个电脑网络的交流，SHOI的领队想要知道：“如果某台电脑A因故障关机的同时某一条网线l（并非连接在A上的）被切断，那么，除了A以外的其他电脑能否保持相互通信？”</span></div>
<div style="margin: 6pt 0cm 12pt; text-indent: 21pt; line-height: 150%"><span style="font-size: medium">于是，SHOI的领队需要你计算这个局域网络的“不稳定程度”。不稳定程度是指：通过从网络中移除一台电脑且切断一条网线（这条网线不连接在这台电脑上）使得整个网络中的其他电脑之间通讯不完全连通的不同方案的总数。</span></div></div>

# Input

<div class="content"><div style="margin: 6pt 0cm 12pt; text-indent: 21pt; line-height: 150%"><span style="font-size: medium">输入文件的第一行有两个正整数n、m，分别表示网络中的电脑终端的数量以及用来连接电脑的网线数量。</span></div>
<div style="margin: 6pt 0cm 12pt; text-indent: 21pt; line-height: 150%"><span style="font-size: medium">接下来m行每行有两个整数x、y来描述一条网线，表示这条网线连接了编号为x、y的电脑，且。</span></div>
<div style="margin: 6pt 0cm 12pt; text-indent: 21pt; line-height: 150%"><span style="font-size: medium">输入文件保证，这个电脑网络初始时是连通的。</span></div></div>

# Output

<div class="content"><div> </div>
<div style="margin: 6pt 0cm 12pt; text-indent: 21pt; line-height: 150%"><span style="font-size: medium">输出文件只有一行，这行只有一个整数，即为通过从网络中移除一台电脑且切断一条网线使得整个网络不连通的不同方案总数。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 4<br/>
1 2<br/>
1 3<br/>
1 4<br/>
1 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">12</span></div>

# Hint

<div class="content"><p></p><p class="MsoPlainText" style="margin: 0cm 0cm 0pt; line-height: 150%"><span lang="EN-US"><font face="宋体" size="3">1&lt;=N&lt;=2000,1&lt;=M&lt;=200000</font></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=day1">day1</a></p></div>

