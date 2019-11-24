<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<h2>背景</h2>
<p>“在那山的那边海的那边有一群小肥猪。他们活泼又聪明，他们调皮又灵敏。他们自由自在生活在那绿色的大草坪，他们善良勇敢相互都关心……”</p>
<p>——选自猪王国民歌</p>
<p> </p>
<p>很久很久以前，在山的那边海的那边的某片风水宝地曾经存在过一个猪王国。猪王国地理位置偏僻，实施的是适应当时社会的自给自足的庄园经济，很少与外界联系，商贸活动就更少了。因此也很少有其他动物知道这样一个王国。</p>
<p>猪王国虽然不大，但是土地肥沃，屋舍俨然。如果一定要拿什么与之相比的话，那就只能是东晋陶渊明笔下的大家想象中的桃花源了。猪王勤政爱民，猪民安居乐业，邻里和睦相处，国家秩序井然，经济欣欣向荣，社会和谐稳定。和谐的社会带给猪民们对工作火红的热情和对未来的粉色的憧憬。</p>
<p>小猪iPig是猪王国的一个很普通的公民。小猪今年10岁了，在大肥猪学校上小学三年级。和大多数猪一样，他不是很聪明，因此经常遇到很多或者稀奇古怪或者旁人看来轻而易举的事情令他大伤脑筋。小猪后来参加了全猪信息学奥林匹克竞赛(Pig Olympiad in Informatics, POI)，取得了不错的名次，最终保送进入了猪王国大学(Pig Kingdom University, PKU)深造。</p>
<p>现在的小猪已经能用计算机解决简单的问题了，比如能用P++语言编写程序计算出A + B的值。这个“成就”已经成为了他津津乐道的话题。当然，不明真相的同学们也开始对他刮目相看啦<span style="font-family: 'Times New Roman';">~</span></p>
<h2>题目描述</h2>
<p>猪王国的文明源远流长，博大精深。</p>
<p>iPig<span style="">在大肥猪学校图书馆中查阅资料，得知远古时期猪文文字总个数为</span>N。当然，一种语言如果字数很多，字典也相应会很大。当时的猪王国国王考虑到如果修一本字典，规模有可能远远超过康熙字典，花费的猪力、物力将难以估量。故考虑再三没有进行这一项劳猪伤财之举。当然，猪王国的文字后来随着历史变迁逐渐进行了简化，去掉了一些不常用的字。</p>
<p>iPig<span style="">打算研究古时某个朝代的猪文文字。根据相关文献记载，那个朝代流传的猪文文字恰好为远古时期的</span>k分之一，其中k是N的一个正约数（可以是<span style="font-family: 'Times New Roman';">1</span><span style="">和</span>N）。不过具体是哪k分之一，以及k是多少，由于历史过于久远，已经无从考证了。</p>
<p>iPig<span style="">觉得只要符合文献，每一种能整除</span>N的k都是有可能的。他打算考虑到所有可能的k。显然当k等于某个定值时，该朝的猪文文字个数为N / k。然而从N个文字中保留下N / k个的情况也是相当多的。<span style="font-family: 'Times New Roman';">iPig</span><span style="">预计，如果所有可能的</span>k的所有情况数加起来为P的话，那么他研究古代文字的代价将会是G的P次方。</p>
<p>现在他想知道猪王国研究古代文字的代价是多少。由于<span style="font-family: 'Times New Roman';">iPig</span><span style="">觉得这个数字可能是天文数字，所以你只需要告诉他答案除以</span>999911659<span style="">的余数就可以了。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入有且仅有一行：两个数N、G，用一个空格分开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出有且仅有一行：一个数，表示答案除以999911659<span style="font-family: 宋体;">的余数</span>。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2048</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>10%<span style="">的数据中，</span><span style="font-family: 'Times New Roman';">1 &lt;= </span>N &lt;= 50<span style="">；</span></p>
<p>20%<span style="">的数据中，</span><span style="font-family: 'Times New Roman';">1 &lt;= </span>N &lt;= 1000<span style="">；</span></p>
<p>40%<span style="">的数据中，</span><span style="font-family: 'Times New Roman';">1 &lt;= </span>N &lt;= 100000<span style="">；</span></p>
<p>100%<span style="">的数据中，</span><span style="font-family: 'Times New Roman';">1 &lt;= </span>G &lt;= 1000000000<span style="">，</span><span style="font-family: 'Times New Roman';">1 &lt;= </span>N &lt;= 1000000000<span style="">。</span></p>
</div>
</div>
</div>