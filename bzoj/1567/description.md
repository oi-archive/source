
# Description

<div class="content">Blue Mary最近迷上了玩Starcraft(星际争霸) 的RPG游戏。她正在设法寻找更多的战役地图以进一步提高自己的水平。
由于Blue Mary的技术已经达到了一定的高度,因此，对于用同一种打法能够通过的战役地图，她只需要玩一张，她就能了解这一类战役的打法，然后她就没有兴趣再玩儿这一类地图了。而网上流传的地图有很多都是属于同一种打法，因此Blue Mary需要你写一个程序，来帮助她判断哪些地图是属于同一类的。
具体来说，Blue Mary已经将战役地图编码为n*n的矩阵，矩阵的每个格子里面是一个32位（有符号）正整数。对于两个矩阵，他们的相似程度定义为他们的最大公共正方形矩阵的边长。两个矩阵的相似程度越大，这两张战役地图就越有可能是属于同一类的。

</div>

# Input

<div class="content">第一行包含一个正整数n。
以下n行，每行包含n个正整数，表示第一张战役地图的代表矩阵。
再以下n行，每行包含n个正整数，表示第二张战役地图的代表矩阵。

</div>

# Output

<div class="content">仅包含一行。这一行仅有一个正整数，表示这两个矩阵的相似程度。
</div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1 2 3<br/>
4 5 6<br/>
7 8 9<br/>
5 6 7<br/>
8 9 1<br/>
2 3 4<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
<br/>
</span></div>

# Hint

<div class="content"><p>样例解释：<br/>
<br/>
子矩阵：<br/>
5 6<br/>
8 9<br/>
为两个地图的最大公共矩阵<br/>
<br/>
约定：<br/>
n&lt;=50<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

