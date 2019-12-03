<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Sue<span style="">和</span><span style="font-family: 'Times New Roman';">Sandy</span><span style="">最近迷上了一个电脑游戏，这个游戏的故事发在美丽神秘并且充满刺激的大海上，</span><span style="font-family: 'Times New Roman';">Sue</span><span style="">有一支轻便小巧的小船。然而，</span><span style="font-family: 'Times New Roman';">Sue</span><span style="">的目标并不是当一个海盗，而是要收集空中漂浮的彩蛋，</span><span style="font-family: 'Times New Roman';">Sue</span><span style="">有一个秘密武器，只要她将小船划到一个彩蛋的正下方，然后使用秘密武器便可以在瞬间收集到这个彩蛋。然而，彩蛋有一个魅力值，这个魅力值会随着彩蛋在空中降落的时间而降低，</span><span style="font-family: 'Times New Roman';">Sue</span><span style="">要想得到更多的分数，必须尽量在魅力值高的时候收集这个彩蛋，而如果一个彩蛋掉入海中，它的魅力值将会变成一个负数，但这并不影响</span><span style="font-family: 'Times New Roman';">Sue</span><span style="">的兴趣，因为每一个彩蛋都是不同的，</span><span style="font-family: 'Times New Roman';">Sue</span><span style="">希望收集到所有的彩蛋。</span></p>
<p>然而<span style="font-family: 'Times New Roman';">Sandy</span><span style="">就没有</span><span style="font-family: 'Times New Roman';">Sue</span><span style="">那么浪漫了，</span><span style="font-family: 'Times New Roman';">Sandy</span><span style="">希望得到尽可能多的分数，为了解决这个问题，他先将这个游戏抽象成了如下模型：</span></p>
<p>以<span style="font-family: 'Times New Roman';">Sue</span><span style="">的初始位置所在水平面作为</span><span style="font-family: 'Times New Roman';">x</span><span style="">轴。</span></p>
<p>一开始空中有<span style="font-family: 'Times New Roman';">N</span><span style="">个彩蛋，对于第</span><span style="font-family: 'Times New Roman';">i</span><span style="">个彩蛋，他的初始位置用整数坐标（</span><span style="font-family: 'Times New Roman';">xi, yi</span><span style="">）表示，游戏开始后，它匀速沿</span><span style="font-family: 'Times New Roman';">y</span><span style="">轴负方向下落</span><span style="font-family: 'Times New Roman';">,</span><span style="">速度为</span><span style="font-family: 'Times New Roman';">vi</span><span style="">单位距离</span><span style="font-family: 'Times New Roman';">/</span><span style="">单位时间。</span><span style="font-family: 'Times New Roman';">Sue</span><span style="">的初始位置为</span><span style="font-family: 'Times New Roman';">(x0, 0)</span><span style="">，</span><span style="font-family: 'Times New Roman';">Sue</span><span style="">可以沿</span><span style="font-family: 'Times New Roman';">x</span><span style="">轴的正方向或负方向移动，</span><span style="font-family: 'Times New Roman';">Sue</span><span style="">的移动速度是</span><span style="font-family: 'Times New Roman';">1</span><span style="">单位距离</span><span style="font-family: 'Times New Roman';">/</span><span style="">单位时间，使用秘密武器得到一个彩蛋是瞬间的，得分为当前彩蛋的</span><span style="font-family: 'Times New Roman';">y</span><span style="">坐标的千分之一。</span></p>
<p>现在，<span style="font-family: 'Times New Roman';">Sue</span><span style="">和</span><span style="font-family: 'Times New Roman';">Sandy</span><span style="">请你来帮忙，为了满足</span><span style="font-family: 'Times New Roman';">Sue</span><span style="">和</span><span style="font-family: 'Times New Roman';">Sandy</span><span style="">各自的目标，你决定在收集到所有彩蛋的基础上，得到的分数最高。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为两个整数<span style="font-family: 'Times New Roman';">N, x0</span><span style="">用一个空格分隔，表示彩蛋个数与</span><span style="font-family: 'Times New Roman';">Sue</span><span style="">的初始位置。</span></p>
<p>第二行为<span style="font-family: 'Times New Roman';">N</span><span style="">个整数</span><span style="font-family: 'Times New Roman';">xi</span><span style="">，每两个数用一个空格分隔，第</span><span style="font-family: 'Times New Roman';">i</span><span style="">个数表示第</span><span style="font-family: 'Times New Roman';">i</span><span style="">个彩蛋的初始横坐标。</span></p>
<p>第三行为<span style="font-family: 'Times New Roman';">N</span><span style="">个整数</span><span style="font-family: 'Times New Roman';">yi</span><span style="">，每两个数用一个空格分隔，第</span><span style="font-family: 'Times New Roman';">i</span><span style="">个数表示第</span><span style="font-family: 'Times New Roman';">i</span><span style="">个彩蛋的初始纵坐标。</span></p>
<p>第四行为<span style="font-family: 'Times New Roman';">N</span><span style="">个整数</span><span style="font-family: 'Times New Roman';">vi</span><span style="">，每两个数用一个空格分隔，第</span><span style="font-family: 'Times New Roman';">i</span><span style="">个数表示第</span><span style="font-family: 'Times New Roman';">i</span><span style="">个彩蛋匀速沿</span><span style="font-family: 'Times New Roman';">y</span><span style="">轴负方向下落的的速度。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一个实数，保留三位小数，为收集所有彩蛋的基础上，可以得到最高的分数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 0</p>
<p>-4 -2 2</p>
<p>22 30 26</p>
<p>1 9 8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0.000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N&lt;=20<span style="">，对于</span><span style="font-family: 'Times New Roman';">30%</span><span style="">的数据。</span></p>
<p>N&lt;=100<span style="">，对于</span><span style="font-family: 'Times New Roman';">100%</span><span style="">的数据。</span></p>
<p>-10^4 &lt;= xi,yi,vi &lt;= 10^4<span style="">，对于</span><span style="font-family: 'Times New Roman';">100%</span><span style="">的数据。</span></p>
</div>
</div>