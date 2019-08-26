
# Description

<div class="content">Sue和Sandy最近迷上了一个电脑游戏，这个游戏的故事发在美丽神秘并且充满刺激的大海上，Sue有一支轻便小巧的小船。然而，Sue的目标并不是当一个海盗，而是要收集空中漂浮的彩蛋，Sue有一个秘密武器，只要她将小船划到一个彩蛋的正下方，然后使用秘密武器便可以在瞬间收集到这个彩蛋。然而，彩蛋有一个魅力值，这个魅力值会随着彩蛋在空中降落的时间而降低，Sue要想得到更多的分数，必须尽量在魅力值高的时候收集这个彩蛋，而如果一个彩蛋掉入海中，它的魅力值将会变成一个负数，但这并不影响Sue的兴趣，因为每一个彩蛋都是不同的，Sue希望收集到所有的彩蛋。
然而Sandy就没有Sue那么浪漫了，Sandy希望得到尽可能多的分数，为了解决这个问题，他先将这个游戏抽象成了如下模型：
以Sue的初始位置所在水平面作为x轴。
一开始空中有N个彩蛋，对于第i个彩蛋，他的初始位置用整数坐标（xi, yi）表示，游戏开始后，它匀速沿y轴负方向下落,速度为vi单位距离/单位时间。Sue的初始位置为(x0, 0)，Sue可以沿x轴的正方向或负方向移动，Sue的移动速度是1单位距离/单位时间，使用秘密武器得到一个彩蛋是瞬间的，得分为当前彩蛋的y坐标的千分之一。
现在，Sue和Sandy请你来帮忙，为了满足Sue和Sandy各自的目标，你决定在收集到所有彩蛋的基础上，得到的分数最高。
</div>

# Input

<div class="content">第一行为两个整数N, x0用一个空格分隔，表示彩蛋个数与Sue的初始位置。
第二行为N个整数xi，每两个数用一个空格分隔，第i个数表示第i个彩蛋的初始横坐标。
第三行为N个整数yi，每两个数用一个空格分隔，第i个数表示第i个彩蛋的初始纵坐标。
第四行为N个整数vi，每两个数用一个空格分隔，第i个数表示第i个彩蛋匀速沿y轴负方向下落的的速度。
</div>

# Output

<div class="content">一个实数，保留三位小数，为收集所有彩蛋的基础上，可以得到最高的分数。
</div>

# Sample Input

<div class="content"><span class="sampledata">3 0<br/>
-4 -2 2<br/>
22 30 26<br/>
1 9 8<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.000<br/>
<br/>
<br/>
数据范围：<br/>
N &lt; = 1000，对于100%的数据。 -10^4  &lt; =  xi,yi,vi  &lt; =  10^4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

