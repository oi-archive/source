<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">从未来过绍兴的小 D 有幸参加了Winter Camp 2008，他被这座历史名城的秀</span><br><span style="">丽风景所吸引，强烈要求游览绍兴及其周边的所有景点。</span><br><span style="">主办者将绍兴划分为 N 行M 列（N×M）个方块，如下图（8×8）：</span></p>
<p><span style="">图片略;</span></p>
<p><span style="">景点含于方块内，且一个方块至多有一个景点。无景点的方块视为路。</span><br><span style="">为了保证安全与便利，主办方依据路况和治安状况，在非景点的一些方块内</span><br><span style="">安排不同数量的志愿者；在景点内聘请导游（导游不是志愿者）。在选择旅游方</span><br><span style="">案时，保证任意两个景点之间，存在一条路径，在这条路径所经过的每一个方块</span><br><span style="">都有志愿者或者该方块为景点。既能满足选手们游览的需要，又能够让志愿者的</span><br><span style="">总数最少。</span><br><span style="">例如，在上面的例子中，在每个没有景点的方块中填入一个数字，表示控制</span><br><span style="">该方块最少需要的志愿者数目：</span></p>
<p><span style="">图片略；</span></p>
<p><span style="">图中用深色标出的方块区域就是一种可行的志愿者安排方案，一共需要20</span><br><span style="">名志愿者。由图可见，两个相邻的景点是直接（有景点内的路）连通的（如沈园</span><br><span style="">和八字桥）。</span><br><span style="">现在，希望你能够帮助主办方找到一种最好的安排方案。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行有两个整数，N 和M，描述方块的数目。</span><br><span style="">接下来 N 行，每行有M 个非负整数，如果该整数为0，则该方块为一个景点；</span><br><span style="">否则表示控制该方块至少需要的志愿者数目。相邻的整数用（若干个）空格隔开，</span><br><span style="">行首行末也可能有多余的空格。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: medium;">由N + 1 行组成。第一行为一个整数，表示你所给出的方案</span><br /><span style="font-size: medium;">中安排的志愿者总数目。</span><br /><span style="font-size: medium;">接下来 N 行，每行M 个字符，描述方案中相应方块的情况：</span><br /><span style="font-size: medium;">&nbsp;&lsquo;_&rsquo;（下划线）表示该方块没有安排志愿者；</span><br /><span style="font-size: medium;">&nbsp;&lsquo;o&rsquo;（小写英文字母o）表示该方块安排了志愿者；</span><br /><span style="font-size: medium;">&nbsp;&lsquo;x&rsquo;（小写英文字母x）表示该方块是一个景点；</span><br /><span style="font-size: medium;">注：请注意输出格式要求，如果缺少某一行或者某一行的字符数目和要求不</span><br /><span style="font-size: medium;">一致（任何一行中，多余的空格都不允许出现），都可能导致该测试点不得分。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4<br>0 1 1 0<br>2 5 5 1<br>1 5 5 1<br>0 1 1 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6<br>xoox<br>___o<br>___o<br>xoox</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">【数据规模】</span><br><span style="">所有的 10 组数据中N, M ，以及景点数 K 的范围规定如下：</span><br><span style="">测试点编号 N M K</span><br><span style="">1 ≤2 ≤2 ≤2</span><br><span style="">2 ≤4 ≤5 ≤4</span><br><span style="">3 ≤2 ≤10 ≤3</span><br><span style="">4 ≤6 ≤7 ≤5</span><br><span style="">5 ≤8 ≤9 ≤7</span><br><span style="">6 ≤10 ≤9 ≤10</span><br><span style="">7 ≤9 ≤10 ≤10</span><br><span style="">8 ≤10 ≤10 ≤3</span><br><span style="">9 ≤10 ≤10 ≤10</span><br><span style="">10 ≤10 ≤10 ≤10</span><br><span style="">输入文件中的所有整数均不小于 0 且不超过2^16</span></p>
</div>
</div>