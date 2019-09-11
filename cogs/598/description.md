# 题目描述


<div style="line-height: 15pt" align="left"><b><span style="font-size: 10pt">【问题描述】</span></b><span style="font-size: 10pt"><br/>
    </span><span style="font-size: 10pt">话说 Z4 阴差阳错地来到了神秘岛。不久，他们发现，这是一个由 n 个小岛和一个中心岛组成的群岛，群岛之间有 m 座桥。令他们感到惊讶的是，这些桥并不是固定不变的，经较长时间的观察，发现它们会随时间作周期性的变化（即桥的两端会不断更换）。 </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">    </span><span style="font-size: 10pt">立方很早就留意到远远的那个中心岛了。他发现岛的上空好像有一个很巨大的东西，但实在太远了，看不清楚。此时 jakrinchose 得意地从身上拿出一个超高倍数望远镜，好像很自豪的样子，因为他平时专门用来看美女的工具此时终于派得上用场了。 </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">    </span><span style="font-size: 10pt">“那是一间小屋！架在一棵好大好大的树上！” </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">    </span><span style="font-size: 10pt">“ Terrific ！我们也许可以暂时在那安顿，好用来遮风避雨！” </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">    </span><span style="font-size: 10pt">于是他们便决定前往中心岛上的那间空中楼阁。 Z4 的懒惰是出了名的，他们当然希望越早到越好，那么，你能帮帮他们吗？ </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">    </span><span style="font-size: 10pt">为方便计算，Z4 把小岛按 1..n 编号， 0 表示中心岛。 Z4 一开始在编号为 1 的小岛上。在岛上行走的时间忽略不计，过桥的时间为 1 个单位。岛上的桥变化的周期为 T ，在 nT+i(n=0,1,2,…;i=1,2,…,T) 时刻岛上的桥为第 i 种状态，一开始的时刻为 1 。两个小岛间可能有多条桥相连。在任一时刻， Z4 可以选择过桥，也可以原地不动。当然，如果无桥可过， Z4 只能在原地等待。 </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">【输入格式】 <br/>
    输入文件 house.in 的第一行包括三个整数 n （ 1 &lt;=n&lt;=80 ） ， m(1&lt;=m&lt;=10000) 和 T(1&lt;=T&lt;=10) ，分别表示小岛的个数，岛上桥的数量和桥改变的周期 T 。 </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">    </span><span style="font-size: 10pt">接下来分别描述第 1..T 种状态，每种状态有 m 行，每行有两个整数 a, b （ 0&lt;=a,b&lt;=n ），表示这种状态时小岛 a 和 b 有一条桥相连。两状态之间用一空行隔开。 </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">【输出格式】 <br/>
    输出文件 house .out 仅有一个整数，表示 Z4 最少得花多少时间到达中心岛。如果 Z4 无法到达中心岛，则输出“ Poor Z4! ”。 </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">【输入输出样例1】<br/>
 <b><br/>
</b>输入： <br/>
house.in<br/>
4 5 2<br/>
1 2<br/>
1 3<br/>
1 4<br/>
2 0<br/>
4 0</span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">1 3<br/>
1 3<br/>
2 3<br/>
4 3<br/>
3 0</span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">输出：<br/>
house.out<br/>
2</span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">【输入输出样例2】<br/>
 <b><br/>
</b>输入： <br/>
house.in<br/>
7 3 2<br/>
1 2<br/>
1 4<br/>
6 0</span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">2 5<br/>
3 6<br/>
4 7</span></div>
<p><span style="font-size: 10pt">输出：<br/>
house.out<br/>
Poor Z4!</span></p>
