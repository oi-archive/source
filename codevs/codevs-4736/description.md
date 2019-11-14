<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">小Z整理完房间时间已经不早了，简单洗漱一下就上床睡觉了，自从进入初三后小Z已经有很久没有做梦了，不做梦的主要原因是学习强度太大加上睡得较晚，一旦睡着就睡得特别沉，沉到没有梦的地步。今晚小Z的大脑皮层特别兴奋，大约是由于白天在CZ中学上的课实在太精彩了，这不小Z刚睡着就进入了梦乡。在梦里小Z梦见自己代表祖国赴B国参加了国际信息学奥林匹克竞赛（International Olympiad in Informatics，简称IOI）并获得了金牌，颁奖会结束后小Z想到附近的超市去买些礼物带回国送给班里的小伙伴们，小Z心想B国的巧克力代表了爱的愿望、大众的迷恋，是食物中的王者，早在19世纪就已经闻名于世了，给小伙伴们每人买一盒巧克力肯定会大受欢迎。于是小Z一进超市就直奔装有巧克力的货架，一口气拿了40盒</span><span style="">Godiva</span><span style="">巧克力，然后到收银台去排队结帐，轮到小Z结账时，他发现自己身上只有一张大面额的B国钞票了，于是他把这张钞票递了过去，收银员迅速在收银机上算出了要找给小Z的金额，然后打开钱柜准备找钱，小Z看到钱柜里的硬币按面额从大到小整整齐齐地摆放着，一种面额的硬币垒成一列，见此情景小Z一下就来了灵感，心想少年宫正在为本次活动征集试题呢，就拿这个找零问题考考小朋友们不是挺好吗？小Z回到宾馆立刻打开笔记本开始命题：已知收银员要找给小Z的金额N、钱柜里的硬币种类K以及K种硬币的面额，计算有多少种不同的找零方法？ 这里的“不同”是指所找零钱至少有一种硬币的数量不相同。假设现在只有2种硬币，一种面额是5分，另一种面额是1分，要找给小Z的金额是8分钱，可以给小Z找 1个五分硬币加 3个一分硬币，或者找8个一分硬币。用3个一分硬币加1个五分硬币本质上与1个五分硬币加3个一分硬币没有任何区别，因此只可以用两种不同的方式找出八分钱。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入数据第一行有两个用空格隔开的整数 N和K，其中</span><span style="">1≤N≤300</span><span style="">，</span><span style="">表示超市收银员要找给小Z的金额，</span><span style="">1≤</span><span style="">K</span><span style="">≤8</span><span style="">，</span><span style="">表示收银员的钱柜里共有K种不同面额的硬币。第2 到 K+1行每行包含一个正整数Ci，其中</span><span style="">1≤Ci≤</span><span style="">1</span><span style="">00</span><span style="">，表示一种硬币的面额，</span><span style="">在输入数据中硬币面额按降序排列（从最大到最小）。 不同种类的硬币面额各不相同，每种硬币都</span><span style="">取之不尽用之不竭</span><span style="">。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style=";font-family:宋体;font-size:14px">输出数据仅有一行包含一个整数，表示超市收银员可能的找零方案数。答案保证不会超出长整型范围。</span><span style=";font-family:宋体;font-size:14px">需要注意的是如果没有面额为1分的硬币，有些金额将无法找零，此时结果就输出0。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">83 5</span></p><p><span style="">50</span></p><p><span style="">25</span></p><p><span style="">10</span></p><p><span style="">5</span></p><p><span style="">1</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>159</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">样例解释：</span></p><p><span style="">输入详解：收银员要找给小Z金额 83分，共有5种硬币，面额分别为：</span><span style="">50,25</span><span style="">,</span><span style="">10</span><span style="">,</span><span style=""> 5</span><span style="">,</span><span style=""> 1</span></p><p><span style="">输出详解：以下是全部159种找零方案中的</span><span style=""> </span><span style="">前</span><span style="">15</span><span style="">种和最后一种</span><span style="">:</span></p><p><span style="">0×50</span><span style="">  </span><span style="">0×25  0×10  0×5 </span><span style=""> </span><span style="">83×1</span></p><p><span style="">0×50  0×25  0×10  1×5 </span><span style=""> </span><span style="">78×1</span></p><p><span style="">0×50  0×25  0×10  2×5 </span><span style=""> </span><span style="">73×1</span></p><p><span style="">0×50  0×25  0×10  3×5  68×1</span></p><p><span style="">0×50  0×25  0×10  4×5 </span><span style=""> </span><span style="">63×1</span></p><p><span style="">0×50  0×25  0×10  5×5  58×1</span></p><p><span style="">0×50  0×25  0×10  6×5  53×1</span></p><p><span style="">0×50  0×25  0×10  7×5  48×1</span></p><p><span style="">0×50  0×25  0×10  8×5  43×1</span></p><p><span style="">0×50  0×25  0×10  9×5  38×1</span></p><p><span style="">0×50  0×25  0×10  10×5</span><span style=""> </span><span style=""> 33×1</span></p><p><span style="">0×50  0×25  0×10  11×5 </span><span style=""> </span><span style="">28×1</span></p><p><span style="">0×50  0×25  0×10  12×5 </span><span style=""> </span><span style="">23×1</span></p><p><span style="">0×50  0×25  0×10  13×5 </span><span style=""> </span><span style="">18×1</span></p><p><span style="">0×50  0×25  0×10  14×5 </span><span style=""> </span><span style="">13×1</span></p><p><span style="">……………………………………………</span></p><p><span style="">1</span><span style="">×50  </span><span style="">1</span><span style="">×25  0×10  </span><span style="">1</span><span style="">×5 </span><span style=""> </span><span style="">3×1</span></p><p><span style=""> </span></p><p style=""><span style="">数据范围：</span></p><p><span style="">10%的数据满足：N</span><span style="">≤50，K≤3，Ci≤10</span></p><p><span style="">30%的数据满足：N</span><span style="">≤100，K≤5，Ci≤20</span></p><p><span style="">60%的数据满足：N</span><span style="">≤100，K≤7，Ci≤50</span></p><p><span style="">100%的数据满足：N</span><span style="">≤300，K≤8，Ci≤100</span></p>
</div>
</div>