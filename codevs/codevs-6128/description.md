<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">Lence<span style="">正在玩一个美妙的游戏。</span></span></p><p><span style=""><span style="">首先这里有一个空白的桌面，上面有线性排列的</span>n<span style="">个方块槽，初始状态下上面什么都没有。</span></span></p><p><span style="">Lence<span style="">现在可以选定一个区间</span><span style="font-family: Calibri;">[l,r](l&lt;=r)</span><span style="">在这段区间内生成一个特殊的方块团。方块团会根据万有引力定律自然的竖直落到方块槽内，</span></span><span style="">特殊方块团的特殊之处在于：</span><span style="">它有一个属性</span><span style="">p</span><span style="">，满足：</span></p><p><span style="">   (1)最左边的一竖列有<span style="font-family: Calibri;">a</span><span style="">个方块。</span></span></p><p style=""><span style="">   (2)</span><span style="font-family: Calibri;">l+1</span><span style="">到</span><span style="font-family: Calibri;">p</span><span style="">这段区间内，每一竖列的方块数都是上一个的个数加上一个正整数</span><span style="font-family: Calibri;">b</span><span style="">。</span></p><p style=""><span style=""> (3)在</span><span style="font-family: Calibri;">p+1</span><span style="">到</span><span style="font-family: Calibri;">r</span><span style="">这段区间内，每一竖列的方块数都是上一个的个数减去一个正整数</span><span style="font-family: Calibri;">b</span><span style="">。</span></p><p><span style=""><span style="">这样的方块团看起来就像两个阶梯。</span></span><span style="">该游戏的说明书上说：</span><span style="">“</span><span style="font-family: Calibri;">......</span><span style="">所谓阶梯，就是每前后两个竖列的方块数的差是一个定值，这样就像一个阶梯。阶梯是连续的。强调一下，如果差值不同那么就不能算成同一阶梯</span><span style="font-family: Calibri;">......</span><span style="">”。</span><span style="">游戏的每个局面是这样的计分的：</span></p><p><span style="">   <span style="">当前桌面上（可能堆了许多次生成而来的方块）的最长阶梯所跨越的方块槽数。</span></span></p><p><span style="">Lence<span style="">喜欢一边玩，一边质问当前桌面上的得分是多少（得分不累加）。</span></span></p><p><span style=""><span style="">他不是在玩这个游戏，他是在玩你，因为他现在要进行许多放置方块操作和询问操作，然后逼迫你快速回答。作为友情提示，她把游戏说明书上的一幅插图给你了，这样可以帮你理解。</span></span><span style="">现在</span><span style="">Lence</span><span style="">正一边嚼着大米饼一边斜着眼看着你。大米饼上面写着：“阶梯可以上升，也可以是下降的，也可以是平的。”</span></p><p><span style=""><span style="">说明书</span></span><span style="">P164<span style="">上的插图：<img height="218" src="/source/codevs/codevs-6128/img/aHR0cDovL3d3dy5qb3lvaS5jbi9tZWRpYS9nb18yMDE3MDUyMDExNTAzMV8xNTQuanBn.jpg" style="" title="" width="505"></span></span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="">第一行读入</span>n,m. n<span style="">表示方块槽的个数</span><span style="font-family: Calibri;">.</span></span></p><p><span style=""><span style="">接下来的</span>m<span style="">行，对于每一行：</span></span></p><p><span style="">  <span style="">首先输入布尔变量</span>f:</span></p><p><span style="">  <span style="">若</span>f<span style="">为</span><span style="font-family: Calibri;">0</span><span style="">，那么接下来进行放置方块操作：即输入</span><span style="font-family: Calibri;">5</span><span style="">个非负整数：</span><span style="font-family: Calibri;">l,r,a,b,p.</span></span></p><p><span style="">  <span style="">这五个元素的意义是：</span></span></p><p><span style="">  <span style="">在方块槽</span>l<span style="">到</span><span style="font-family: Calibri;">r</span><span style="">上方生成一个方块团，这个方块团最左边的一竖列有</span><span style="font-family: Calibri;">a</span><span style="">个方块，然后     从</span><span style="font-family: Calibri;">l+1</span><span style="">到</span><span style="font-family: Calibri;">p</span><span style="">的位置每一竖列的方块数比上一个多</span><span style="font-family: Calibri;">b</span><span style="">个</span><span style="font-family: Calibri;">.</span><span style="">从</span><span style="font-family: Calibri;">p+1</span><span style="">到</span><span style="font-family: Calibri;">r</span><span style="">的位置每一竖列的的方块数比上一个少</span><span style="font-family: Calibri;">b</span><span style="">个。</span></span><span style="">若</span><span style="">f</span><span style="">为</span><span style="font-family: Calibri;">1</span><span style="">，表示一个询问。接下来输入</span><span style="font-family: Calibri;">l,r.</span><span style="">表示询问方块槽</span><span style="font-family: Calibri;">l</span><span style="">到</span><span style="font-family: Calibri;">r(</span><span style="">含</span><span style="font-family: Calibri;">l,r)</span><span style="">中最长的方块阶梯的长度（长度指的是所占据的方块槽数）。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:28px"><span style=";font-family:宋体;font-size:14px"><span style="font-family:宋体">对于每一个询问，输出当前桌面的分数，记得回车哦！</span></span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">5</span><span style=""> </span><span style="">3</span></p><p><span style="">0</span><span style=""> </span><span style="">1</span><span style=""> </span><span style="">5</span><span style=""> </span><span style="">2</span><span style=""> </span><span style="">2</span><span style=""> </span><span style="">3</span></p><p><span style="">0</span><span style=""> </span><span style="">4</span><span style=""> </span><span style="">5</span><span style=""> </span><span style="">4</span><span style=""> </span><span style="">4</span><span style=""> </span><span style="">5</span></p><p><span style="">1</span><span style=""> </span><span style="">1</span><span style=""> </span><span style="">5</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">n&lt;=100000 m&lt;=100000</span></p><p>大米饼可以救你。</p>
</div>
</div>