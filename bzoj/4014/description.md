
# Description

<div class="content"><div>众所周知，在国王胖哥的带领下，K国国泰民安，空前繁荣，但今天K国却遇到了空前的危机。</div>
<div>在K国境内同时发现了n个未知的病毒，每个病毒会从它被发现的位置开始感染K国的土地，K国可以看做是一个无限大的二维平面，而病毒的感染形状可以看做是一个不断扩大的圆形区域，即在t时间这个病毒会感染半径为t的圆形土地，这个圆形的圆心为发现这个病毒的位置。</div>
<div>但是万幸的是，K国有独特的病毒防护带可以杀死这些病毒，所以K国国王胖哥在刚发现病毒之时就开始着手进行杀毒工作，所谓的病毒防护带可以看成是一条直线，可以选定建立在K国的任意位置，即可以放置在K国所表示的平面上的任意位置，一旦病毒在扩散的过程中接触到这个防护带，病毒就会死亡，它感染的土地面积就固定为这个病毒死亡时所占的土地面积。注意由于防护带的建立十分昂贵，K国最多只能建立一条病毒防护带。</div>
<div>现在胖哥想知道要如何设立这个病毒防护带，才能使每个病毒感染的平均面积最小，即被感染的总土地面积除以病毒数n，每个病毒可以独立看待，即任意一个病毒的死亡不会影响到其他的病毒。注意如果同一个区域被多个病毒感染，那么在计算被感染的土地面积时需要计算多次，即若有一个病毒在位置(0,0)被发现，一个病毒在位置(1,1)被发现，它们都在t=1时接触到防护带死亡，那么此时K国被感染的面积为pi*2，病毒感染的平均面积为pi。</div>
<div>由于K国有举世无双的安全监测系统和卫生防护系统，可以认为在病毒防护带建立完毕之后病毒才开始进行扩散。若病毒出现在病毒防护带上，他感染的土地面积可以看做0。</div>
<div>请编程输出在最优决策下，这些病毒感染的平均面积。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第1行中给出正整数Q，表示该组数据中有多少组测试样例。</div>
<div>
<div>每组样例首先输入一个整数n (0 &lt; n ≤ 1000000)，表示该组样例中病毒的个数，之后一行输入两个正整数x，y，表示第一个病毒的坐标，之后一行输入三个正整数a，b，c，如果第i个病毒的坐标为(x, y)，那么第i+1个病毒的坐标为(x’, y’)，其中x’=(a*x*x + b*x + c)%107，y’=(a*y*y + b*y + c)%107，其中%是取模运算符号</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>首先输出样例编号，之后输出在最优决策下，这些病毒会感染的K国的土地面积，答案保留8位小数，详见输出示例，请严格按照输出实例中的格式输出</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
2<br/>
0 0<br/>
0 0 1<br/>
3<br/>
1 2<br/>
3 4 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 0.00000000<br/>
Case 2: 58.42574374</span></div>

# Hint

<div class="content"><p></p><div>100%的数据满足Q*n≤10000000，0 ≤x, y, a, b, c≤100, Q≤n。</div><br/>
<div></div><br/>
<div>//某出题人是见到了这题以后才出了[Zjoi2014]星系调查</div><br/>
<div>数据及SPJ见<span style="font-size: 12px;">http://www.lydsy.com/JudgeOnline/upload/4014.rar</span></div><br/>
<div></div><br/>
<div></div><br/>
<div></div><br/>
<div></div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

