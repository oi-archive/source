<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>形如2</span><sup><span><em>P</em></span></sup><span>-1的素数称为麦森数, 这时P一定也是个素数. 但反过来不一定, 即如果P是个素数, 2</span><sup><span><em>P</em></span></sup><span>-1不一定也是素数. 在1998年底, 人们找到了37个麦森数. 当时</span><span>最大的一个是</span><span>P=3021377, </span><span>它有</span><span>909526</span><span>位. </span><span>但是截止到2013年2月, </span><span>美国中央密苏里大学数学家库珀领导的研究小组通过参加一个名为“互联网梅森素数大搜索”(GIMPS)项目, 日前发现了第48个梅森素数——P=57885161; 该素数也是目前已知的最大素数, 有17425170位. 如果用普通字号将它连续打印下来, 它的长度可超过65公里! 美国数学学会发言人布林说:“超大素数令数学家和计算机科学家感到兴奋.” 他认为这是素数探究的一项重大突破. </span><span>麦森数有许多重要应用, 它与完全数密切相关. 所以, 给出一个P, 请计算出</span><span>2</span><sup><span><em>P</em></span></sup><span>-1.</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>一个整数P.</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>第一行:&nbsp;十进制高精度数2<sup>P</sup>-1的位数.</span><br /><span>第2-21行:&nbsp;十进制高精度数2<sup>P</sup>-1的最后1000位数字.&nbsp;(每行输出50位,&nbsp;共输出10行,&nbsp;不足500位时高位补0)</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>1279</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>386</span><br><span>00000000000000000000000000000000000000000000000000</span><br><span>00000000000000000000000000000000000000000000000000</span><br><span>00000000000000000000000000000000000000000000000000</span><br><span>00000000000000000000000000000000000000000000000000</span><br><span>00000000000000000000000000000000000000000000000000</span><br><span>00000000000000000000000000000000000000000000000000</span><br><span>00000000000000000000000000000000000000000000000000</span><br><span>00000000000000000000000000000000000000000000000000</span><br><span>00000000000000000000000000000000000000000000000000</span><br><span>00000000000000000000000000000000000000000000000000</span><br><span>00000000000000000000000000000000000000000000000000</span><br><span>00000000000000000000000000000000000000000000000000</span><br><span>00000000000000104079321946643990819252403273640855</span><br><span>38615262247266704805319112350403608059673360298012</span><br><span>23944173232418484242161395428100779138356624832346</span><br><span>49081399066056773207629241295093892203457731833496</span><br><span>61583550472959420547689811211693677147548478866962</span><br><span>50138443826029173234888531116082853841658502825560</span><br><span>46662248318909188018470682222031405210266984354887</span><br><span>32958028878050869736186900714720710555703168729087</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>1000≤P&lt;2147483647</span></p>
</div>
</div>