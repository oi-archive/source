
# Description

<div class="content"><p><span style="font-size: medium">听说公主被关押在城堡里，彭大侠下定决心：不管一路上有多少坎坷，不管城堡中的看守有多少厉害，不管救了公主之后公主会不会再被抓走，不管公主是否漂亮、是否会钟情于自己，他将义无反顾地朝着城堡前进。</span></p>
<p><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> 可是，通往城堡的路上出现了一些情况。抽象地说，假象地图在二维平面的第一象限。在每个横轴的x位置上有一个高为h<sub>x</sub>的支撑点，如果彭大侠没有跳到支撑点上，那么他就会掉下去，牺牲在路途。开始时彭大侠在起点（1，h<sub>1</sub>）处，而城堡的入口在（n，h<sub>n</sub>）处。彭大侠每次可以从支撑点（x，h<sub>x</sub>）跳到支撑点（x+1，h<sub>x+1</sub>）。但是彭大侠每次的跳跃能量只有d，也就是说，每次跳跃必须满足条件|h<sub>x+1</sub>-h<sub>n</sub>|≤d。换句话说，如果两个相邻支撑点的纵向落差大于d，那么彭大侠就无法跳跃了！幸运的是，彭大侠还有一个杀手锏。在起点处，他可以花一个金币，把某个支撑点升高1个单位，或者降低1个单位。但是，起点处和城堡入口处的支撑点高度不能改变，并且一旦离开起点彭大侠就无法使用该杀手锏。</span></p>
<p><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> 彭大侠被告知100个金币可兑换一单位生命。于是他希望通过少花金币来保存更多单位的生命。他终于找到了你这位热心的高手，请你帮他规划一下以便耗费尽量少的金币来到达城堡。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">文件第一行包含一个整数m(m≤5)，表示问题求解次数。接下来的2m行依次表示每次求解的输入数据块。每个输入数据块占2行，其中第一行包含两个整数n和d，分别表示从起点到城堡入口处必须经过的支撑点数和每次跳跃允许的最大纵向落差，n和d之间用空格隔开，输入数据保证2≤n≤5000，0≤d≤10<sup>9</sup>；第二行包含用空格隔开的n个非负整数h<sub>1</sub>、h<sub>2</sub>、…、h<sub>n</sub>，其中h<sub>i</sub>(1≤i≤n)表示第i个支撑点的高度，特别地，h<sub>1</sub>表示彭大侠出发时所在支撑点的高度，h<sub>n</sub>表示城堡入口所在支撑点的高度，输入数据保证对所有1≤i≤n有0≤h<sub>i</sub>≤10<sup>9</sup>。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">有m行，第I(1≤I≤m)行表示第I次求解时彭大侠到达城堡必须耗费的最少金币数量。若无论怎样使用杀手锏他都无法到达城堡，则输出impossible。输入数据保证答案在int64范围之内。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3                        <br/>
10 2                      <br/>
4 5 10 6 6 9 4 7 9 8          <br/>
3 1<br/>
6 4 0<br/>
4 2<br/>
3 0 6 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
impossible<br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"> 对样例中的第一个输入数据块，d=2，把第三个支撑点降低3个单位，把第六个支撑点降低1个单位，把第七个支撑点升高2个单位，原序列变成：4 5 7 6 6 8 6 7 9 8，这时任意相邻支撑点的纵向落差没有超过2，彭大侠可以到达城堡！</span></p><br/>
<p><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> 对样例中的第二个输入数据块，d=1，这时不管怎样调节第二个支撑点的高度，都无法使任意相邻支撑点的纵向落差不超过1。</span></p><br/>
<p><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> 对样例中的第三个输入数据块，d=2，这时，把第二个支撑点升高1个单位，把第三个支撑点降低3个单位就满足条件了。</span></p><br/>
<p><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> 【数据规模】</span></p><br/>
<p><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> 20% </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> n≤100</span></p><br/>
<p><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> 40% </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> n≤1000</span></p><br/>
<p><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> 100% </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> n≤5000</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

