
# Description

<div class="content"><p><span style="font-size: medium">邪恶的巨型宇宙怪物 CCM(Crazy Code Monster)即将对美丽的地球发动攻击!<br/>
在这千钧一发的时刻,地球联合军决定使用地球最先进的能量武器——由发明家 SHTSC 设计的超能粒子炮彻底摧毁 CCM。<br/>
超能粒子炮由垂直方向从上到下共 n 个超能粒子发射管构成,编号 1~n。所有的发射管都会在开火的一瞬间同时发射出强大的超能粒子流。<br/>
为了彻底摧毁再生能力极强的邪恶宇宙怪物 CCM,地球联合军将 CCM 从上到下分为 m 个区域, 编号 1~m,分别进行打击。其中超能粒子炮的第 i 号发射管将会对准 f(i)号区域发射。f(i) 的公式如下:<br/>
f(i) = (a * i + b) mod m + 1<br/>
其中 a, b 都是给定的常数。<br/>
然而,出于某种不可告人的目的,N 财团不希望 CCM 被超能粒子炮彻底消灭。于是 N 财团以远程精神控制了超能粒子炮的操作员——你来阻止地球军消灭 CCM。<br/>
你发现,超能粒子炮的开火模式会使得不同的粒子流的运动轨迹发生交叉, 而在所有这些交叉点处部署一种名为折跃棱镜的能量反射装置就能使得超能粒子炮因过载而自爆。这样,你就可以阻止地球联合军使用超能粒子炮摧毁 CCM 而成为下一代 N 财团金牌的获得者。<br/>
为了实现这个计划,你需要知道有多少对粒子流 i, j,满足 i&lt;j 且 f(i) &gt; f(j)。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第一行四个整数:n, m, a, b。分别为超能粒子炮的发射管数目、CCM 被分成的区域数、以及题目描述中的 f 公式中的常数。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">输出一行一个整数,为运动轨迹交叉的粒子流的对数。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">样例一：<br/>
2 3 2 2<br/>
样例二：<br/>
5 5 2 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例一：<br/>
1<br/>
样例二：<br/>
7<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">对于 100%的数据,n≤m≤10^9,存在 a’满足 a*a’=1 (mod m), 且 min{a,a’} ≤1000, a,b&lt;m, m 是质数。<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

