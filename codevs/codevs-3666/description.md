<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">在</span><span style="font-family: Verdana;">3</span><span style="">月</span><span style="font-family: Verdana;">29</span><span style="">日</span><span style="">举行的女子冰壶世锦赛决赛中，王冰玉、柳荫、岳清爽和周妍组成的中国女子冰壶队以</span><span style="font-family: Verdana;">8</span><span style="">比</span><span style="font-family: Verdana;">6</span><span style="">击败了冬奥会和世</span><span style="">锦赛双冠王瑞典队，夺得了中国冰壶历史上第一枚世锦赛金牌，创造了历史。美丽、实力兼具的中国冰壶姑娘们也赢得了超高的赞誉。</span></p><p style=""><span style="">在冰壶比赛中，给出一个<strong><em>目标点</em></strong></span><strong><em><span style="font-family: Verdana;">P</span></em></strong><span style="">，以及一个规定的正整数</span><span style="font-family: Verdana;">r</span><span style="">。每一局由甲乙两队轮流投冰壶各</span><span style="font-family: Verdana;">8</span><span style="">次后，该局比赛结束。此时，哪一方的冰壶最终离<strong><em>目标点</em></strong></span><strong><em><span style="font-family: Verdana;">P</span></em></strong><span style="">更近，该方得分，另一方不得分。得分方</span><span style="">每颗离<strong><em>目标点</em></strong></span><strong><em><span style="">P</span></em></strong><span style="">距离小于或等于</span><span style="">r</span><span style="">、位置较另一队所有</span><span style="">冰</span><span style="">壶都更接近<strong><em>目标点</em></strong></span><strong><em><span style="">P</span></em></strong><span style="">的冰壶都可以得</span><span style="">1</span><span style="">分。</span></p><p style=""><span style="">比赛最多进行</span><span style="">10</span><span style="">局。双方之间的某局比赛结束后，落后一方可以弃权。此时，比赛不再进行下去。</span></p><p style=""><span style="">已知每一局结束时，双方的每个冰壶离</span><strong><em><span style="">目标点</span></em></strong><strong><em><span style="">P</span></em></strong><span style="">的距离，以及正整数</span><span style="font-family: Verdana;">r</span><span style="">，请你写一个程序判断两队之间每一局比赛的得分，以及总得分。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入文件</span><span style="font-family: Verdana;">Curling</span><span style="">.in</span><span style="">的第一行只有一个正整数</span><span style="">r</span><span style="">。</span></p><p style=""><span style="">以下有若干行</span><span style="">(</span><span style="">不超过</span><span style="">20</span><span style="">行</span><span style="">)</span><span style="">，除了最后一行外，每一行有</span><span style="">8</span><span style="">个正整数</span><span style="">(</span><span style="">互相之间以一个空格分隔</span><span style="">)</span><span style="">。</span></p><p style=""><span style="">第</span><span style="">2</span><span style="">行的第</span><span style="">j</span><span style="">个数表示第</span><span style="">1</span><span style="">局比赛结束时，甲方的第</span><span style="">j</span><span style="">个冰壶距离</span><strong><em><span style="">目标点</span></em></strong><strong><em><span style="">P</span></em></strong><span style="">的距离</span><span style="">;</span></p><p style=""><span style="">第</span><span style="">3</span><span style="">行的第</span><span style="">j</span><span style="">个数表示第</span><span style="">1</span><span style="">局比赛结束时，乙方的第</span><span style="">j</span><span style="">个冰壶距离</span><strong><em><span style="">目标点</span></em></strong><strong><em><span style="">P</span></em></strong><span style="">的距离</span><span style="">;</span></p><p style=""><span style="">第</span><span style="">4</span><span style="">行的第</span><span style="">j</span><span style="">个数表示第</span><span style="">2</span><span style="">局比赛结束时，甲方的第</span><span style="">j</span><span style="">个冰壶距离</span><strong><em><span style="">目标点</span></em></strong><strong><em><span style="">P</span></em></strong><span style="">的距离</span><span style="">;</span></p><p style=""><span style="">第</span><span style="">5</span><span style="">行的第</span><span style="">j</span><span style="">个数表示第</span><span style="">2</span><span style="">局比赛结束时，乙方的第</span><span style="">j</span><span style="">个冰壶距离</span><strong><em><span style="">目标点</span></em></strong><strong><em><span style="">P</span></em></strong><span style="">的距离</span><span style="">;</span></p><p style=""><span style="">    … …</span></p><p style=""><span style="">第</span><span style="">2k</span><span style="">行的第</span><span style="">j</span><span style="">个数表示第</span><span style="">k</span><span style="">局比赛结束时，甲方的第</span><span style="">j</span><span style="">个冰壶距离</span><strong><em><span style="">目标点</span></em></strong><strong><em><span style="">P</span></em></strong><span style="">的距离</span><span style="">;</span></p><p style=""><span style="">第</span><span style="">2k+1</span><span style="">行的第</span><span style="">j</span><span style="">个数表示第</span><span style="">k</span><span style="">局比赛结束时，乙方的第</span><span style="">j</span><span style="">个冰壶距离</span><strong><em><span style="">目标点</span></em></strong><strong><em><span style="">P</span></em></strong><span style="">的距离</span><span style="">;</span></p><p> </p><p style=""><span style="">如果有一方中途弃权，则最后一行</span><span style="">(</span><span style="">偶数行</span><span style="">)</span><span style="">只有一个整数</span><span style="">-1</span><span style="">，表示此时发生弃权情况。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="line-height:24px"><span style=";font-family:宋体">输出文件</span><span style="font-family: Verdana">Curling</span><span style=";font-family:Verdana">.out</span><span style=";font-family:宋体">有若干行，每行有二个整数，中间以一个冒号分隔，表示每一局比赛甲乙双方的比分</span><span style=";font-family:Verdana">(</span><span style=";font-family:宋体">甲得分在前</span><span style=";font-family:Verdana">)</span><span style=";font-family:宋体">。</span></p><p style="text-indent: 28px; line-height: 24px;"><span style=";font-family:宋体">最后一行有二个整数，中间以一个冒号分隔，表示甲乙双方比赛的最终得分</span><span style=";font-family:Verdana">(</span><span style=";font-family:宋体">甲得分在前</span><span style=";font-family:Verdana">)</span><span style=";font-family:宋体">。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: Verdana;">8</span></p><p><strong><span style="font-family: Verdana;">5  20  18  19  3  15  13  3</span></strong></p><p><strong><span style="font-family: Verdana;">20  2  17  12  5  18  10  11</span></strong></p><p><span style="font-family: Verdana;">20  3  4  1  2  11  9  2</span></p><p><span style="font-family: Verdana;">4  15  19  9  8  14  11  10</span></p><p><strong><span style="font-family: Verdana;">15  2  10  1  19  14  3  18</span></strong></p><p><strong><span style="font-family: Verdana;">15  17  21  19  24  32  19  26</span></strong></p><p><span style="font-family: Verdana;">-1</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: Verdana;">0:1</span></p><p><span style="font-family: Verdana;">4:0</span></p><p><span style="font-family: Verdana;">3:0</span></p><p><span style="font-family: Verdana;">7:1</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: Verdana;">70%</span><span style="">的数据，双方均不弃权，比赛进行</span><span style="font-family: Verdana;">10</span><span style="">局</span></p><p style=""><span style="font-family: Verdana;">100%</span><span style="">的数据，每只冰壶距离目标点</span><span style="font-family: Verdana;">P</span><span style="">的距离不超过</span><span style="font-family: Verdana;">100</span><span style="">。</span></p><p style=""><span style="font-family: Verdana;"> </span></p><p><br></p>
</div>
</div>