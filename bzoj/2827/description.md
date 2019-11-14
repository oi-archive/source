
# Description

<div class="content"><div><span style="font-size: medium; "><br/>
</span></div>
<div><span style="font-size: medium; "><span class="Apple-tab-span" style="white-space: pre; ">	</span>话说有一天doyouloveme和vfleaking到山里玩。谁知doyouloveme刚刚进山，所有的鸟儿竟被他的神犇气场给惊得全部飞走了。vfleaking顿时膜拜不已。</span></div>
<div><span style="font-size: medium; "><span class="Apple-tab-span" style="white-space: pre; ">	</span>这时鸟王用鸟语说道：“!@#$%……?”安抚了一下众鸟的情绪。鸟王生性好斗，作出了一个决定——要排鸟布阵把刚才吓到它们的人类赶出山去。</span></div>
<div><span style="font-size: medium; "><span class="Apple-tab-span" style="white-space: pre; ">	</span>每只鸟都有一个编号，都有一个威武值。每秒钟鸟王都会发一个命令，编号为v的鸟飞到(x,y)去（坐标系原点是山顶，坐标单位为鸟爪）。鸟飞得很快，一秒之内就飞到了，可以看作是瞬间移动。如果编号为v的鸟和编号为u的鸟某一时刻处在同一位置，它们就会互相鼓励，增加各自的士气值和团结值。一只鸟的士气值等于此刻与它处在同一位置的鸟中的威武值的最大值，团结值等于此刻与它处在同一位置的鸟的只数。如果每一时刻都没有鸟与它处在同一位置，则士气值和团结值都为0。要注意自己不能鼓励自己，计算士气值和团结值时不能算上自己。</span></div>
<div><span style="font-size: medium; "><span class="Apple-tab-span" style="white-space: pre; ">	</span>t秒钟后，doyouloveme目测出了现在每只鸟的战斗力，于是感叹了一句：“不妙，我们得走了。”</span></div>
<div><span style="font-size: medium; "><span class="Apple-tab-span" style="white-space: pre; ">	</span>正所谓团结的鸟儿一个顶俩，所以doyouloveme这样描述战斗力：一只鸟战斗力值等于它在0到t秒中士气值的最大值与团结值的最大值的乘积。注意不是乘积的最大值，而是最大值的乘积。</span></div>
<div><span style="font-size: medium; "><span class="Apple-tab-span" style="white-space: pre; ">	</span>vfleaking很想知道现在每只鸟的战斗力，但是他当然不会啦，于是他把这个任务交给了你来完成。</span></div>
<div><span style="font-size: medium; "><br/>
</span></div>
<div><font size="3"><br/>
</font></div>
<p></p></div>

# Input

<div class="content"><p></p>
<div></div>
<div>
<div><span style="font-size: medium; "><span class="Apple-tab-span" style="white-space: pre; ">	</span>第一行一个数n，代表鸟的只数。（鸟王那家伙你可以完全忽视掉）</span></div>
<div><span style="font-size: medium; "><span class="Apple-tab-span" style="white-space: pre; ">	</span>接下来n行，每行三个整数w,x,y描述每只鸟的威武值和初始坐标。第i+1行描述编号为i的鸟。</span></div>
<div><span style="font-size: medium; "><span class="Apple-tab-span" style="white-space: pre; ">	</span>接下来一行有一个数t，代表经过时间ts。</span></div>
<div><span style="font-size: medium; "><span class="Apple-tab-span" style="white-space: pre; ">	</span>接下来t行，每行三个整数v,x,y描述鸟王每秒的命令。</span></div>
<div></div>
</div></div>

# Output

<div class="content"><div>
<div><span class="Apple-tab-span" style="font-size: medium; white-space: pre; ">	</span><span style="font-size: medium; ">一共n行，每行一个数，代表每只鸟的战斗力。</span></div>
<div><span style="font-size: medium; "><br/>
</span></div>
<div><font size="3"><br/>
</font></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 1 1<br/>
3 1 2<br/>
4 4 4<br/>
2 0 1<br/>
2 2 3<br/>
5<br/>
1 1 2<br/>
2 4 4<br/>
2 4 3<br/>
3 0 1<br/>
5 0 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
4<br/>
6<br/>
8<br/>
8<br/>
</span></div>

# Hint

<div class="content"><p></p><div>对于样例的解释：</div><br/>
<div>首先5只鸟的位置为(1,1),(1,2),(4,4),(0,1),(2,3)，士气和团结值都是0。</div><br/>
<div>鸟1飞到了(1,2)，于是鸟1和鸟2互相鼓励，鸟1士气变为3，鸟2士气变为1。鸟1鸟2的团结值变为1。</div><br/>
<div>然后鸟2飞到(4,4)，与鸟3互相鼓励，鸟2士气变为4，鸟3士气变为3。鸟2与鸟3的团结值变为1。</div><br/>
<div>鸟2然后飞到了(4,3)，一个没有鸟的地方。于是士气和团结值都变为了0。</div><br/>
<div>接下来鸟3和鸟5都飞到了鸟4的位置，于是三只鸟互相鼓励，鸟4、鸟5士气变为4，鸟3士气仍为3。鸟3、鸟4、鸟5的团结值都变为2。</div><br/>
<div>于是大家的战斗力：</div><br/>
<div>鸟1：3 * 1 = 3</div><br/>
<div>鸟2：4 * 1 = 4</div><br/>
<div>鸟3：3 * 2 = 6</div><br/>
<div>鸟4：4 * 2 = 8</div><br/>
<div>鸟5：4 * 2 = 8</div><br/>
<div></div><br/>
<div>1≤n≤30000   0≤t≤300000   坐标范围为整数，且不超过INT_MIN~INT_MAX</div><br/>
<div>威武值为不超过INT_MAX的非负整数。</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=湖北省队互测
">湖北省队互测<br/>
</a></p></div>

