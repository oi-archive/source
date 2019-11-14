
# Description

<div class="content"><p><span style="font-size: medium">小Z在玩一个叫做《淘金者》的游戏。游戏的世界是一个二维坐标。X轴、Y轴坐标范围均为1..N。初始的时候，所有的整数坐标点上均有一块金子，共N*N块。<br/>
    一阵风吹过，金子的位置发生了一些变化。细心的小Z发现，初始在(i，j)坐标处的金子会变到(f(i)，fIj))坐标处。其中f(x)表示x各位数字的乘积，例如f(99)=81，f(12)=2，f(10)=0。如果金子变化后的坐标不在1..N的范围内，我们认为这块金子已经被移出游戏。同时可以发现，对于变化之后的游戏局面，某些坐标上的金子数量可能不止一块，而另外一些坐标上可能已经没有金子。这次变化之后，游戏将不会再对金子的位置和数量进行改变，玩家可以开始进行采集工作。<br/>
    小Z很懒，打算只进行K次采集。每次采集可以得到某一个坐标上的所有金子，采集之后，该坐标上的金子数变为0。<br/>
    现在小Z希望知道，对于变化之后的游戏局面，在采集次数为K的前提下，最多可以采集到多少块金子？<br/>
    答案可能很大，小Z希望得到对1000000007(10^9+7)取模之后的答案。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">  共一行，包含两介正整数N，K。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">  一个整数，表示最多可以采集到的金子数量。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">    1 2  5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">    18</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">N &lt; = 10^12 ,K &lt; = 100000<br/><br/>
对于100%的测试数据：K &lt; = N^2</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

