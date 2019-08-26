
# Description

<div class="content"><div>JOI君有N个装在手机上的挂饰，编号为1...N。 JOI君可以将其中的一些装在手机上。</div>
<div>JOI君的挂饰有一些与众不同——其中的一些挂饰附有可以挂其他挂件的挂钩。每个挂件要么直接挂在手机上，要么挂在其他挂件的挂钩上。直接挂在手机上的挂件最多有1个。</div>
<div>此外，每个挂件有一个安装时会获得的喜悦值，用一个整数来表示。如果JOI君很讨厌某个挂饰，那么这个挂饰的喜悦值就是一个负数。</div>
<div>JOI君想要最大化所有挂饰的喜悦值之和。注意不必要将所有的挂钩都挂上挂饰，而且一个都不挂也是可以的。</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个整数N，代表挂饰的个数。</div>
<div>接下来N行，第i行(1&lt;=i&lt;=N)有两个空格分隔的整数Ai和Bi，表示挂饰i有Ai个挂钩，安装后会获得Bi的喜悦值。 </div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个整数，表示手机上连接的挂饰总和的最大值</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
0 4<br/>
2 -2<br/>
1 -1<br/>
0 1<br/>
0 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p><div>将挂饰2直接挂在手机上，然后将挂饰1和挂饰5分别挂在挂饰2的两个挂钩上，可以获得最大喜悦值4-2+3=5。</div><br/>
<div>1&lt;=N&lt;=2000</div><br/>
<div>0&lt;=Ai&lt;=N(1&lt;=i&lt;=N)</div><br/>
<div>-10^6&lt;=Bi&lt;=10^6(1&lt;=i&lt;=N)</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=JOI 2013~2014 春季training合宿 竞技4 By PoPoQQQ">JOI 2013~2014 春季training合宿 竞技4 By PoPoQQQ</a></p></div>

