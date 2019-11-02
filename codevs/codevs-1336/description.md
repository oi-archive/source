<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>       刚进我们的新学校~首先感受到了校园的样子与小学完全不同~来到了我们的机房，我也看到了几个同学~有的认识，有的不认识！(MHZ：废话！ LCZ：现在流行说废话凑字数。 JHT：汗~)</p>
<p>       现在，为了让大家更熟悉，更容易交流，于是老师决定排座位！现在，老师通过同学们的自我介绍明白了同学们互相的熟悉度，老师安排好座位后，告诉了同学们一个惊天的好消息(MHZ：哇，快说！)：我们可以去参观广播操的排练现场！</p>
<p>       来到了现场，我们通过仔细的观察，又发现了一个秘密，我们几个过去参观的同学被老师盯上了！老师发现他们的同学做广播的动作极不整齐，让我们告诉他们应该做那个动作会用的时间最少而最整齐。</p>
<p>       MHZ由于是第一个到现场的，所以，这个任务就给他了~作为他的好朋友，你要帮帮他哦！</p>
<p>       有n个班的老师求助~我们都要帮他们(JHT：要不要给他们每人发一瓶水 MHZ：我也要，其他没意见 JHT：那还是算了~)。</p>
<p>       每个班里都有相对应的m个学生，由于老师初期教的不好，于是动作五花八门的！居然最多有50种动作！！！现在知道越是接近的两个动作，他们序号就越接近。而要改掉这个动作的时间就是你要改的动作的序号减去现在动作序号的绝对值~老师问你一共需要多少时间才能纠正全班的错误(LJX：提醒一下，老师只有一个，要一个一个同学地纠正~)。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：一个整数n</p>
<p>第2~n+1行：首先是一个整数m，然后是m个人的动作，都用0~49的整数组成。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; &nbsp; &nbsp;n行，每行两个整数：第一个整数表示选的动作的序号，第二个整数表示纠正动作要花的时间(LCZ：时间一样的话按序号小的输出~老师认为序号的动作越小越美观~)。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>4 0 1 2 3</p>
<p>5 0 0 0 0 0</p>
<p>4 0 0 1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 4</p>
<p>0 0</p>
<p>0 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>时间限制</strong><strong> Time Limitation</strong></p>
<p>1s，不解释</p>
<p><strong>注释</strong><strong> Hint</strong><strong></strong></p>
<p>       100%的数据：n≤40,m≤50000</p>
</div>
</div>