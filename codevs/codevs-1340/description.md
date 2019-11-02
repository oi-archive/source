<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>WJMZBMR神犇和白狼在对撸OSU。。。<br><br>丽洁姐因手速太快SS了大黑，白狼被深深地吓到了。。。<br><br>于是白狼希望开挂= =<br><br>白狼听说从前有一个遥远的东方帝国——天朝。。<br><br>那个帝国有各种编挂的神牛。。。<br><br>由于神牛过多，白狼将神牛标号随机选了一个，结果找到了你= =<br><br>白狼答应当你编出挂时给你100000000000 mod 10元以买一块曲奇用的板子0w0。。<br><br>白狼提供了各个Note的出现时间及坐标（没有Spinner、Slider）。你则要用US语言（Unscience）编一个外挂。。。<br><br>US语言超简单（简单爆了）已知它有如下几种语言：<br><br>CMove(x,y)：移动指针至XY。<br><br>Delay(t)：程序延时t毫秒<br><br>MClick：鼠标点击一下<br><br>同各种语言一样，所有语句之后要加分号。<br><br>顺便说一下OSU的游戏规则：<br><br>Easy很简单，只要点Note就行了：在规定时间内将鼠标指针移动至对应坐标，再在最佳时间点击一下。<br><br>具体格式见样例输入输出。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：一个整数n</p>
<p>接下去n行：每行3个整数t,x,y</p>
<p>分别表示点击该Note的最佳时间(ms)，该Note的x坐标及Y坐标</p>
<p>大小写严格按照样例输出。</p>
<p>当相邻两个Note坐标重复时仍然视为移动。</p>
<p>每条语句一行</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出整个程序</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>9</p>
<p>1 1 1</p>
<p>2 2 2</p>
<p>3 3 3</p>
<p>4 4 4</p>
<p>5 5 5</p>
<p>6 6 6</p>
<p>7 7 7</p>
<p>8 8 8</p>
<p>10 10 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Delay(1);</p>
<p>CMove(1,1);</p>
<p>MClick;</p>
<p>Delay(1);</p>
<p>CMove(2,2);</p>
<p>MClick;</p>
<p>Delay(1);</p>
<p>CMove(3,3);</p>
<p>MClick;</p>
<p>Delay(1);</p>
<p>CMove(4,4);</p>
<p>MClick;</p>
<p>Delay(1);</p>
<p>CMove(5,5);</p>
<p>MClick;</p>
<p>Delay(1);</p>
<p>CMove(6,6);</p>
<p>MClick;</p>
<p>Delay(1);</p>
<p>CMove(7,7);</p>
<p>MClick;</p>
<p>Delay(1);</p>
<p>CMove(8,8);</p>
<p>MClick;</p>
<p>Delay(2);</p>
<p>CMove(10,10);</p>
<p>MClick;</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=n&lt;=100000</p>
<p>0&lt;=t,x,y&lt;=2147483647</p>
<p>前面的Delay表示0秒开始到第一个Note的时间</p>
</div>
</div>