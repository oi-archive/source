<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　PianoEater喜欢听钢琴曲，并且一直梦想着给他的GF Little Pink弹奏一曲。于是PianoEater去钢琴王国大学（Piano Kingdom University，简称PKU）找钢琴十级的rainbow学习弹琴。</span><br><span>　　PianoEater弹琴时，他的一只手上的5根手指不能交叉，并且两根手指不能放在同一个琴键上。同时，一只手的跨度不能超过9个白键（大拇指和小指之间最多间隔7个白键）。弹琴时，左右臂可以交叉，但是用（其中一只手的手指）去按（处于另一只手的两个手指之间）的按键是不允许的。</span></p>
<p><span><span>　　现在PianoEater有一架有52个白键和36个黑键的钢琴，并且他要弹奏的曲子只需要按白键。在同一时刻，他只用弹奏一个音符。如果这个音符不移动大拇指就可以按到，那么他不需要耗费体力；否则他需要花费sqrt(x)（下取整）的体力来移动手的位置（也就是移动大拇指的位置）。其中x代表移动前后大拇指的位置之差的绝对值。</span><br><span>　　现在有一首由N个音符组成的乐曲，每个音符用0~51之间的一个整数表示，分别对应了52个白键。0是最左边的键，51是最右边的键。PianoEater想知道他弹完这首曲子最少需要耗费多少体力。</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　输入的第一行是三个整数，L,R,N，分别表示初始时刻左手大拇指的位置、右手大拇指的位置和乐曲的音符数。</span><br><span>　　接下来N行每行一个在0~51之间的整数，代表需要弹奏的音符。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　<span>输出一个整数，表示最少需要耗费的体力。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 20 10<br>0<br>1<br>2<br>3<br>4<br>5<br>6<br>7<br>8<br>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>　　对于30%的数据，1&lt;=N&lt;=100</span><br><span>　　对于50%的数据，1&lt;=N&lt;=500</span><br><span>　　对于100%的数据，1&lt;=N&lt;=1000，4&lt;=L&lt;=51,0&lt;=R&lt;=47</span><br><br><span>样例解释：</span><br><span>　　最初左手大拇指在10，第一次花费sqrt(2)=1的体力移动到8，此时0~8这9个键都能被左手够到。最后再花费sqrt(1)=1的体力移动到9即可。</span></p>
<p><span><br></span></p>
<p><span>来源：Nescafe 21</span></p>
</div>
</div>