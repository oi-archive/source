<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>chang老师是一个非常仁慈的老师！但如果学生太过分，实在忍无可忍的话，他会罚学生写检讨。sky是深有体会。</p><p>sky回忆了一下，讲起了他被罚写检讨的经历。有一次，sky没来上课，也没有请假，结果被罚写3个字的检讨，当时他写了900字；还有一次，sky在课堂上玩游戏，被罚写100字检讨，当时他写了201个字……</p><p>其实，上课并不是不能请假，但如果每个人都经常请假，那课还怎么上呢？所以还是不要请假的好！</p><p>其实，学生并不是不能玩游戏，但学习时间怎么可以拿来玩游戏呢？玩游戏不仅影响自己，还会影响到周围的同学呀！</p><p>所以，chang老师让sky写检讨，sky没有理由拒绝。</p><p>今天，sky又被罚写检讨了，他被罚写33字检讨。什么叫做33字检讨呢？33字检讨，就是指检讨字数是33的倍数，或者字+标点的数量是33的倍数。当然，这是严格要求的情况。由于陈老师非常不讲理，但是，只要字数误差在5%以内，都可以。</p><p>举个例子，33的倍数，可以是33、66、99、132、165、198、231、264……，严格要求的话，检讨字数必须是这些；但不讲理的chang老师，居然还允许写32、34字的检讨，因为33*0.95=31.35，33*1.05=34.65，32、33、34都在31.35到34.65范围内，当然。66*0.95=62.7，66*1.05=69.3，所以写63、64、65、66、67、68、69个字的检讨也是可以的。</p><p>现在，sky写了一篇检讨，请帮chang老师判断这篇检讨是否符合要求？chang老师智商不够用了！你还是帮sky判断一下是否符合要求吧，因为提交不符合要求的检讨，会受到更严重的惩罚！</p><p>怎么判断呢？我们先来看看sky的检讨。检讨里面仅包含文字、空格、逗号和句号。只要在句号的地方，字数满足要求就符合要求了，因为句号后面的内容都可以删掉。（逗号不行哦，因为这个句子还没完）</p><p>现请你写个程序，帮sky判断一下检讨是否符合要求，如果符合，输出最少字数（含空格、标点），否则输出0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：输入一个整数n，表示这是n字检讨<br><br>第二行：输入一个整数m，表示误差范围是m%<br><br>第三行：检讨内容，由字母、空格、逗号、句号组成</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个数，符合要求的检讨的最少字数或者0</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10<br>10<br>wo zhi dao cuo le, xia ci bu gan. wo bu wan you xi. qing yuan lian wo ba.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>51</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n &lt;= 1000<br>m &lt;= 50<br>检讨字数 &lt;= 10000<br>样例说明：<br>写10字检讨，误差10%，字数可以是9、10、11、18、19、20、21、22、27、28、29、30、31、32、33……<br>“wo zhi dao cuo le, xia ci bu gan. wo bu wan you xi.”共有38个字（不含空格），符合要求，总字数（含空格）51。<br>----------------------------------<br>呵呵哒</p>
</div>
</div>