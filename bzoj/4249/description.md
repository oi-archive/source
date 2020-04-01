
# Description

<div class="content"><div>
<div>你入手了一款JOI社发售的游戏。你对这款游戏十分上手，每天玩得不亦乐乎。</div>
<div>某一天，玩家之中出现了一个叫做“镭射”的关卡。这个关卡十分的难，连老司机玩家也只有很低的概率才能通过。正在三番五次挑战这个关卡的你，很快判断出通过的可能性是存在的，并考虑写一个程序来计算出对策。</div>
<div>镭射关卡在一个配置有N个防壁的地形上进行。地形为长方形，分成了一些1*1的正方形区域。每个区域可以用两个非负整数(x,y)表示，左下角的区域为(0,0),(x,y)表示(0,0)往右数x个区域，再往上数y个区域的位置。</div>
<div>关卡开始后，敌人会出现并顺次进行M轮攻击。第i次攻击时，敌人将会从区域(Pi,N+1)向区域(Pi,0)进行直线镭射射击。</div>
<div>每个防壁放在y坐标相同的一些连续的区域中。防壁i(1&lt;=i&lt;=N)是左右长度为Bi-Ai+1，上下宽度为1的长方形，初始位置为(Ai,i)到(Bi,i)的所有区域。在敌人开始攻击之前以及两次攻击的间隙，你可以任意次地左右移动防壁。一次移动可以让防壁向右移动一个区域，或者向左移动一个区域。</div>
<div>镭射在穿过一个防壁后威力会减少。现在为了将镭射的威力最小化，需要移动防壁使得镭射能穿过所有的防壁。你想让移动防壁的次数尽量少。</div>
<div>现在给出关卡开始时每个防壁的位置，以及每个敌人的攻击位置，为了让每一发镭射都穿过所有的防壁，请你输出每个防壁移动次数的最小值。</div>
</div>
<p></p></div>

# Input

<div class="content"><p> 第一行两个空格分隔的整数N,M，表示这个关卡有N个防壁，敌人将会进行M轮攻击。</p>
<div>接下来N行，第i行(1&lt;=i&lt;=N)有两个空格分隔的整数Ai,Bi，表示关卡开始时防壁i被放置在(Ai,i)到(Bi,i)的所有区域的位置上。</div>
<div>接下来M行，第i行有一个整数Pi，表示第i次攻击时，敌人从(Pi,N+1)向(Pi,0)进行直线镭射射击。</div></div>

# Output

<div class="content"><p> 输出N行，第i行表示防壁i的移动次数的最小值。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
0 3<br/>
4 4<br/>
2 7<br/>
8 11<br/>
6<br/>
4<br/>
3<br/>
8<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
10<br/>
1<br/>
7</span></div>

# Hint

<div class="content"><p></p><div>1&lt;=N&lt;=2*10^5</div><br/>
<div>1&lt;=M&lt;=2*10^5</div><br/>
<div>0&lt;=Ai&lt;=Bi&lt;=10^9 (1&lt;=i&lt;=N)</div><br/>
<div>0&lt;=Pi&lt;=10^9 (1&lt;=i&lt;=M)</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=JOI 2014~2015 春季training合宿 竞技4 By POPOQQQ
">JOI 2014~2015 春季training合宿 竞技4 By POPOQQQ<br/>
</a></p></div>

