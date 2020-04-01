
# Description

<div class="content"><p>在世界末日的前一天，所有神牛全部来到了一个矩形大广场上。这让你——一个相对还很弱小的同学感到透不过气来，因为神牛会产生看不到的气场，让人身心俱疲。具体的，每个神牛的控制区域都是一条线段(x1,y1)----(x2,y2)，两端点有可能相同，那样就变成了一个点。设你所在的位置为点P，如果可以过P做两条互相垂直的直线，使得这两条直线都与某一个或某两个神牛的控制区域有公共点，那么这个P点就是被气场覆盖的部分，这是你不想呆在的地方，你只想一个人静一静，于是，你想知道这个广场的安静系数的值。其中，安静系数=未被气场覆盖的面积/广场总面积。</p></div>

# Input

<div class="content"><p>输入的第一行包含三个整数N,X,Y，分别表示神牛的个数，以及广场的长和宽。广场的区域范围为(0,0)~(X,Y). 接下来N行，每行有四个用空格隔开的非负整数x1,y1,x2,y2,表示该神牛的控制线段为(x1,y1)----(x2,y2)，其中，x1,x2在0到X之间，y1,y2在0到Y之间.</p></div>

# Output

<div class="content"><p>输出一个0到1之间的数，表示这个广场的安静系数，只要输出的答案和参考答案相差不超过0.005就算正确。</p></div>

# Sample Input

<div class="content"><span class="sampledata">1 2 2<br/>
0 1 2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.214602<br/>
实际上，样例对应的气场覆盖的区域为以(1,1)为圆心的一个圆，面积为pi，而安静系数自然就等于(4-pi)/4=0.2146018…<br/>
<br/>
100%的数据满足，N≤50，X≤10000，Y≤100. <br/>
</span></div>

# Hint

<div class="content"><p></p><p>鸣谢Benz提供sj程序！</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

