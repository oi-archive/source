<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>你跳过华尔兹吗？当音乐响起，当你随着旋律滑动舞步，是不是有一种漫步 仙境的惬意？ 众所周知，跳华尔兹时，最重要的是有好的音乐。但是很少有几个人知道， 世界上最伟大的钢琴家一生都漂泊在大海上，他的名字叫丹尼·布德曼·T.D.·柠 檬·1900，朋友们都叫他 1900。 <br>1900 在 20 世纪的第一年出生在往返于欧美的邮轮弗吉尼亚号上。很不幸， 他刚出生就被抛弃，成了孤儿。1900 孤独的成长在弗吉尼亚号上，从未离开过 这个摇晃的世界。也许是对他命运的补偿，上帝派可爱的小天使艾米丽照顾他。 可能是天使的点化，1900 拥有不可思议的钢琴天赋：从未有人教，从没看过 乐谱，但他却能凭着自己的感觉弹出最沁人心脾的旋律。当 1900 的音乐获得邮 轮上所有人的欢迎时，他才 8 岁，而此时，他已经乘着海轮往返欧美大陆 50 余 次了。 <br>虽说是钢琴奇才，但 1900 还是个孩子，他有着和一般男孩一样的好奇和调皮，<span style="">只不过更多一层浪漫的色彩罢了： 这是一个风雨交加的夜晚，海风卷起层层巨浪拍打着弗吉尼亚号，邮轮随着 巨浪剧烈的摇摆。船上的新萨克斯手迈克斯·托尼晕船了，1900 招呼托尼和他 一起坐到舞厅里的钢琴上，然后松开了固定钢琴的闸，于是，钢琴随着海轮的倾 斜滑动起来。准确的说，我们的主角 1900、钢琴、邮轮随着 1900 的旋律一起跳 起了华尔兹，随着“嘣嚓嚓”的节奏，托尼的晕船症也奇迹般的消失了。后来托 尼在回忆录上这样写道： 大海摇晃着我们 使我们转来转去 快速的掠过灯和家具 我意识到我们正在和大海一起跳舞 真是完美而疯狂的舞者 晚上在金色的地板上快乐的跳着华尔兹是不是很惬意呢？也许，我们忘记了 一个人，那就是艾米丽，她可没闲着：她必须在适当的时候施展魔法帮助 1900， 不让钢琴碰上舞厅里的家具。 </span></p>
<p>不妨认为舞厅是一个N行M列的矩阵，矩阵中的某些方格上堆放了一些家具， 其他的则是空地。钢琴可以在空地上滑动，但不能撞上家具或滑出舞厅，否则会 损坏钢琴和家具，引来难缠的船长。 每个时刻，钢琴都会随着船体倾斜的方向向相邻的方格滑动一格，相邻的方 格可以是向东、向西、向南或向北的。而艾米丽可以选择施魔法或不施魔法：如 果不施魔法，则钢琴会滑动；如果施魔法，则钢琴会原地不动。 艾米丽是个天使，她知道每段时间的船体的倾斜情况。她想使钢琴在舞厅里 滑行的路程尽量长，这样 1900 会非常高兴，同时也有利于治疗托尼的晕船。但 艾米丽还太小，不会算，所以希望你能帮助她。</p>

<img src="/source/codevs/codevs-1748/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNzQ4L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTc0OC5wbmc=.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行包含 5 个数 N, M, x, y 和 K。N 和 M 描述舞厅的大小，x 和 y 为钢琴的初始位置；我们对船体倾斜情况是按时间的区间来描述的，且从 1 开始计算时间，比如“在[1, 3]时间里向东倾斜，[4, 5]时间里向北倾斜”，因此这 里的 K 表示区间的数目。 以下 N 行，每行 M 个字符，描述舞厅里的家具。第 i 行 第 j 列 的字符若为‘ . ’， 则表示该位置是空地；若为‘ x ’，则表示有家具。 以下 K 行，顺序描述 K 个时间区间，格式为：si ti di(1 ≤ i ≤ K)。表示在时间 区间[si, ti]内，船体都是向 di方向倾斜的。di 为 1, 2, 3, 4 中的一个，依次表示北、 南、西、东（分别对应矩阵中的上、下、左、右）。输入保证区间是连续的，即</p>
<p>s1 = 1</p>
<p>ti = si-1 + 1 <span style=""> (1 &lt; i ≤ K)</span></p>
<p><span style=""> tK = T </span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件仅有 1 行，包含一个整数，表示钢琴滑行的最长距离(即格子数)。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 5 4 1 3</p>
<p>..xx.</p>
<p>.....</p>
<p>...x.</p>
<p>.....</p>
<p>1 3 4</p>
<p>4 5 1</p>
<p>6 7 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>50%的数据中，1≤N, M≤200，T≤200； <br>100%的数据中，1≤N, M≤200，K≤200，T≤40000。</p>
</div>
</div>