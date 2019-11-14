<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">学校里有一个水房，水房里一共装有m个龙头可供同学们打开水，每个龙头每秒钟的供水量相等，均为1。</span></p><p style=""><span style="">现在有n名同学准备接水，他们的初始接水顺序已经确定。将这些同学按接水顺序从 1到n编号，i号同学的接水量为wi。接水开始时，1到m号同学各占一个水龙头，并同时打开水龙头接水。当其中某名同学j完成其接水量要求wj后，下一名排队等候接水的同学k马上接替j同学的位置开始接水。这个换人的过程是瞬间完成的，且没有任何水的浪费。即j同学第x秒结束时完成接水，则k同学第x+1秒立刻开始接水。若当前接水人数n’不足m，则只有n’个龙头供水，其它m-n’个龙头关闭。  </span></p><p style=""><span style="">现在给出</span><span style="font-family: Arial;">n</span><span style="">名同学的接水量，按照上述接水规则，问所有同学都接完水需要多少秒。</span></p><p style=""><span style="">特别地，同学们在打水前排好了队，接水所用时间更长的先接。</span></p><p style=""><span style=""><br></span></p><p style=""><span style="">（ps：出题人本来想设计一个贪心的题目，然后发现用贪心做有反例，只能强改题目，在此声明道歉。不要在意样例解释。）</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">第<span style="font-family: Arial;"> 1 </span>行<span style="font-family: Arial;">2 </span>个整数<span style="font-family: Arial;"> n </span>和<span style="font-family: Arial;"> m</span>，用一个空格隔开，分别表示接水人数和龙头个数。<span style="font-family: Arial;">  </span></p><p style="">第<span style="font-family: Arial;"> 2 </span>行<span style="font-family: Arial;"> n </span>个整数<span style="font-family: Arial;"> w1</span>、<span style="font-family: Arial;">w2</span>、<span style="font-family: Arial;">„„</span>、<span style="font-family: Arial;">wn</span>，每两个整数之间用一个空格隔开，<span style="font-family: Arial;">wi</span>表示<span style="font-family: Arial;"> i </span>号同学的接水量。<span style="font-family: Arial;"> </span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行，1 个整数，表示接水所需的总时间。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 3</p><p>4 4 1 2 1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="">【输入输出解释】<br></p><p style="">第 1 秒，3 人接水。第 1秒结束时，1、2、3 号同学每人的已接水量为 1，3 号同学接完水，4 号同学接替 3 号同学开始接水。  </p><p style="">第 2 秒，3 人接水。第 2 秒结束时，1、2 号同学每人的已接水量为 2，4 号同学的已接水量为 1。  </p><p style="">第 3 秒，3 人接水。第 3 秒结束时，1、2 号同学每人的已接水量为 3，4 号同学的已接水量为 2。4号同学接完水，5 号同学接替 4 号同学开始接水。  </p><p style="">第 4 秒，3 人接水。第 4 秒结束时，1、2 号同学每人的已接水量为 4，5 号同学的已接水量为 1。1、2、5 号同学接完水，即所有人完成接水。 </p><p> </p><p>【数据范围】<br>对于 30%的数据，n≤10,000，m≤1,000；<br>对于全部的数据，1≤m≤n≤1,000,000，1≤m≤100,000。</p>
</div>
</div>