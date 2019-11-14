<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>某一天WJMZBMR在打osu~~~但是他太弱逼了，有些地方完全靠运气:(<br>我们来简化一下这个游戏的规则<br>有n次点击要做，成功了就是o，失败了就是x，分数是按comb计算的，连续a个comb就有a*a分，comb就是极大的连续o。<br>比如ooxxxxooooxxx，分数就是2*2+4*4=4+16=20。<br>Sevenkplus闲的慌就看他打了一盘，有些地方跟运气无关要么是o要么是x，有些地方o或者x各有50%的可能性，用?号来表示。<br>比如oo?xx就是一个可能的输入。<br>那么WJMZBMR这场osu的期望得分是多少呢？<br>比如oo?xx的话，?是o的话就是oooxx =&gt; 9，是x的话就是ooxxx =&gt; 4<br>期望自然就是(4+9)/2 =6.5了</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数n，表示点击的个数<br>接下来一个字符串，每个字符都是ox？中的一个</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行一个浮点数表示答案<br />四舍五入到小数点后4位<br />如果害怕精度跪建议用long double或者extended</p>
<p>(由于没有SpecialJudge功能，请强制输出4位小数)</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4<br>????</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4.1250</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据范围】</p>
<p>k表示?号的个数</p>
<p>40%的数据 : n&lt;=200且k&lt;=20</p>
<p>70%的数据 : k&lt;=20</p>
<p>100%的数据 : n&lt;=300000</p>
<p> </p>
<p>【卖萌向】</p>
<p>osu很好玩的哦</p>
<p>WJMZBMR技术还行(雾),x基本上很少呢</p>
<p> </p>
<p>【来源】</p>
<p>我们都爱GYZ摸你赛 Problem A Easy</p>
</div>
</div>