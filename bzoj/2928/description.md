
# Description

<div class="content"><div style="text-indent: 24pt"><span style="font-size: medium">一场战争在U国与A国之间爆发了。U国的负责情报的长官得知，A国在边界上已经事先布置了N个坚实的地堡，这些地堡组成的防御体系将对U国的士兵构成极大的威胁！U国国防部不得不在进攻之前先摧毁这些地堡！</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">为了出奇制胜，U国国防部决定：布置在边界的每一个飞弹发射点负责消灭一个地堡。为了给敌人一个措手不及，N个飞弹发射点将同时发射飞弹，每个飞弹均以直线全速前进，争取在短时间内给地堡群造成毁灭性的打击。</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">但是，由于这些飞弹是地对地电子制导型的，两颗飞弹的飞行路线如果相交，电子信号将会互相干扰，从而偏离预定目标。</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">作为军事顾问，国防部需要你来设计一个作战方案，事先确定每个飞弹点负责哪一个地堡，并且在所设计的方案中，飞弹的飞行线路不相交。</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">情报部门已经将飞弹发射点和地堡的位置明确标在地图上，并保证这2N个坐标点不存在三点共线</span></div></div>

# Input

<div class="content"><div style="text-indent: 24pt"><span style="font-size: medium">第一行是一个数N（1&lt;=N&lt;=10000），表示飞弹发射点的个数，也是敌方地堡的个数。</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">以下N行，每行两个整数x和y（在[-10000,10000]内），第i+1行表示第i个飞弹发射点的坐标，。</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">再下面N行，每行两个整数x和y（在[-10000,10000]内），第N+i+1行表示第i个地堡的坐标</span></div></div>

# Output

<div class="content"><div style="text-indent: 24pt"><span style="font-size: medium">输出文件有N行，每行为一个整数。第i行的整数P<sub>i</sub>表示，第i个飞弹发射点负责消灭第P<sub>i</sub>个地堡</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
0 0<br/>
1 5<br/>
4 2<br/>
2 6<br/>
1 2<br/>
5 4<br/>
4 5<br/>
3 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1<br/>
4<br/>
3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

