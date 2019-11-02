<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>（本故事纯属虚构，如有雷同纯属巧合）<br> 今天体育老师在操场上打球，把所有的篮筐全部霸占上了，他们很霸道，不让我们打球，没办法我们只能看他们打球了。这时我们班的傻大个来了，想为我们打抱不平，要和体育老师一决高下，他向体育老师发起了挑战！我们都为傻大个捏了把汗，他究竟能不能胜利呢？让我们为他算算吧！</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数n表示体育老师的人数<br>第二行至第n+1行 每行两个整数 p，h表示体育老师的体力数值值和攻击力数值<br>第n+2行 两个整数 x,y 表示我们班傻大个的攻击力数值和体力数值<br>注意：体育老师也很文明他们也是一个一个和傻大个打，不是好多人一起打傻大个</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行如果傻大个可以打败体育老师输出"yes!!very good"否则输出"oh shit!"</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1<br>4 5<br>6 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>yes!!very good</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1.体育老师一个一个和傻大个打<br>2.任何一个体育老师和傻大个打完之后傻大个只保持打完后的体力值，并不回复！<br>3.傻大个和体育老师打架采用回合制（就是傻大个先打，然后是体育老师，这样轮流下去，直到有一方败北）<br>4.任何时候都是傻大个先攻击<br>5.每回合的掉血量就是对方的攻击力<br>6..体力值&lt;=0的时候算败北<br>例：傻大个的攻击力是6，体力6，只有一个体育老师和他对战，体育老师的攻击力是5，体力是4，傻大个先手，他攻击力直接把体育老师体力打成-2，傻大个胜，所以输出yes!!very good<br>n&lt;=65 其他数均在int范围内</p>
</div>
</div>