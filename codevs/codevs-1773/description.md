<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>回到家中的猫猫把三桶鱼全部转移到了她那长方形大池子中，然后开始思考：到底要以何种方法吃鱼呢（猫猫就是这么可爱，吃鱼也要想好吃法 ^_*）。她发现，把大池子视为01矩阵（0表示对应位置无鱼，1表示对应位置有鱼）有助于决定吃鱼策略。</p>
<p>在代表池子的01矩阵中，有很多的正方形子矩阵，如果某个正方形子矩阵的某条对角线上都有鱼，且此正方形子矩阵的其他地方无鱼，猫猫就可以从这个正方形子矩阵“对角线的一端”下口，只一吸，就能把对角线上的那一队鲜鱼吸入口中。</p>
<p>　　猫猫是个贪婪的家伙，所以她想一口吃掉尽量多的鱼。请你帮猫猫计算一下，她一口下去，最多可以吃掉多少条鱼？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入数据：</p>
<p>　　有多组输入数据，每组数据：</p>
<p>　　第一行有两个整数n和m（n,m≥1），描述池塘规模。接下来的n行，每行有m个数字（非“0”即“1”）。每两个数字之间用空格隔开。</p>
<p>　　对于30%的数据，有n,m≤100</p>
<p>　　对于60%的数据，有n,m≤1000</p>
<p>　　对于100%的数据，有n,m≤2500</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出数据：</p>
<p>　　只有一个整数&mdash;&mdash;猫猫一口下去可以吃掉的鱼的数量，占一行，行末有回车。</p>
<p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>输入样例：</p>
<p>4 6</p>
<p>0 1 0 1 0 0</p>
<p>0 0 1 0 1 0</p>
<p>1 1 0 0 0 1</p>
<p>0 1 1 0 1 0</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>输出样例：</p>
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>DP可满点，搜索..</p>
</div>
</div>