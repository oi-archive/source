<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>距2008年北京奥运会开幕还有90天时，CTSC准备为志愿者们举行一次抽奖活动。作为志愿者的一员，你对这次抽奖活动自然是万分期待。</p>
<p>       CTSC委员会介绍了抽奖活动的规则。设总共有<em>p</em>个参加抽奖的志愿者，开始时每一个志愿者领取一个0到<em>p</em>-1的 号码。任意两个志愿者领取的号码不同。屏幕的正中央是五福娃的头像，他们不停的眨眼欢迎大家。开始抽奖时，工作人员按下屏幕旁边的按钮，等待屏幕上的画面静止下来。这时，福娃们都停止眨眼了。当然，画面静止时，有的福娃的眼睛可能是睁开的，有的是闭上的。如果所有福娃的眼睛都闭上了，工作人员需要重新按一 下按钮。这样，直到至少有一个福娃的眼睛是睁开的。接着，工作人员开始观察有哪些福娃的眼睛是睁开的。</p>
<p>       工作人员对五个福娃都标了号。贝贝、晶晶、欢欢、迎迎、妮妮的标号分别是2、3、4、5、6（工作人员认为0和1都不是好数字）。定义幸运数字如下：</p>
<p>       1、如果一个福娃的眼睛是睁开的，那么他（她）对应的标号就是幸运数字；</p>
<p>       2、如果数字<em>l</em>1和<em>l</em>2(可能相等)都是幸运数字，那么他们的乘积 也是幸运数字；</p>
<p>       3、其他的数字都不是幸运数字。</p>
<p>       用<em>L</em>表示所有数字的集合，例如，如果贝贝、晶晶的眼睛是睁开的，欢欢、迎迎、妮妮的眼睛是闭上的，则<em>L</em>={2,3,4,6,8,9,12,…}。令<em>l</em>(<em>x</em>)表示第<em>x</em>大的幸运数字。例如，上面的例子中，<em>l</em>(1)=2，<em>l</em>(4)=6等等。</p>
<p>       接着，工作人员开始随机产生两个数，小的数是<em>a</em>，大的数字是<em>b</em>。定义集合<em>Ta</em>,<em>b</em>为：</p>
<p>             （其中 表示<em>x</em>整除<em>y</em>）</p>
<p>       定义一个自然数的有限子集的特征值<em>f</em> 如下：</p>
<p>1、空集的特征值为0，即 ；</p>
<p>2、对于非空集合<em>S</em>，令<em>d</em>为<em>S</em>中的最小元素，则</p>
<p><span style="">  f(s)=d+f(s\d)+q*d*f(s\d)。</span></p>
<p>其中， 表示把<em>S</em>删除元素<em>d</em>后的集合，<em>q</em>是一个给定的非负整数。</p>
<p>在<em>a</em>和<em>b</em>产生以后，中奖的志愿者就确定了，他的号码是除以<em>p</em>的余数。工作人员会产生多次<em>a</em>，<em>b</em>，这样就能形成多个中奖者。但是，抽奖现场的程序需要很长的时间才能算出中奖的志愿者。出于对中奖结果的热切期待，你便想要重新写一下计算程序，于是，你的目光移向了前面的键盘……。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行给出用空格隔开的5个数，每个数不是0就是1，分别表示贝贝、晶晶、欢欢、迎迎、妮妮的眼睛是否睁开。0对应眼睛闭上，1对应眼睛睁开。5个数不可能都是0。</p>
<p>第二行给出了用空格隔开的两个数，<em>p</em>和<em>q</em>。 其中<em>p</em>表示参加抽奖的志愿者的人数，<em>q</em>如前所述，用来计算集合的特征值。</p>
<p>第三行给出了数<em>n</em>，表示抽取的<em>a</em>和<em>b</em>的次数。</p>
<p>接下来的<em>n</em>行，每一行有两个数<em>a</em>、<em>b</em>，中间用空格隔开，表示一次抽奖产生的两个数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出共<em>n</em>行，每一行一个整数，表示一次抽奖中中奖者的号码。顺序与输入的<em>n</em>对<em>a</em>、<em>b</em>一一对应。当然，一个人可能中奖多次。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 0 0 1 0</p>
<p>10001 2</p>
<p>3</p>
<p>1 10</p>
<p>2 12</p>
<p>4 15</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3265</p>
<p>5816</p>
<p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>贝贝和迎迎的眼睛是睁开的，因此，前面15个幸运数字是2、4、5、8、10、16、20、25、32、40、50、64、80、100、125。<em>l</em>(1) = 2，l(10) = 40。既是2的倍数，又是40的约数的幸运数字有2、4、8、10、20、40。所以<em>T</em>1,10 = {2,4,8,10,20,40}。<em>T</em>1,10的特征值的计算过程为：</p>
<p> </p>
<p>所以中奖者的号码就是26675932除以10001的余数——3265。</p>
<p>类似的，<em>T</em>2,12 = {4,8,16,32,64}，它的特征值是21167932，除以10001的余数是5816。而<em>T</em>4,15 = <em>Φ</em>。</p>
<p>有20%的数据点满足：</p>
<p>              1 ≤ <em>a </em>≤ <em>b </em>≤1000，<em>n </em>≤ 2000；</p>
<p>       所有的数据点均满足：</p>
<p>              1 ≤ <em>a </em>≤ <em>b </em>≤ 100000，<em>n </em>≤ 100000，<em>p</em>, <em>q </em>≤ 2 × 109。</p>
<p>60%的数据点满足：<em>p</em>是素数。</p>
</div>
</div>