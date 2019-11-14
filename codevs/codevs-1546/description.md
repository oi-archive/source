<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    贝贝所居住的城市有很多个交通路口，其中有26个交通路口在上下班高峰期总是塞车，严重影响市民的出行。于是交通管理部门研制了一批机器人交通警察，用它们来专门指挥这26个交通路口，但需要一个自动化的指挥系统来指挥机器人的运作。这个任务交给了贝贝，贝贝的设计如下。</p>
<p>    分别用大写英文字母A、B、…、Z表示这26个路口，并按如下的规则派出这些机器人到交通路口协助指挥交通：</p>
<p>    1．每次派出两名机器人；</p>
<p>    2．当两名机器人的名字中存在一个相同的字母时，这两名机器人便到对应的交通路口上指挥交通；有多个字母相同时，两名机器人需要按字母的字典顺序到这些路口上巡逻；</p>
<p>    3．当两名机器人的名字中不存在相同的字母时，交警部门的派出指令无效(WuXiao)。</p>
<p>    假设这些机器人的名字全由大写字母组成，请你编一个程序，帮贝贝完成这个交通指挥系统。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第1行输入第一个机器人的名字(长度不超过250);</p>
<p>    第2行输入第二个机器人的名字(长度不超过250)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp;&nbsp;1．当不能派出机器人时，在第一行输出&ldquo;WuXiao&rdquo;；</p>
<p>&nbsp;&nbsp; &nbsp;2．当两名机器人在路口上指挥交通时，在第一行输出&ldquo;ZhiHui&rdquo;，第二行输出路口编号；</p>
<p>&nbsp;&nbsp;&nbsp; 3．当两名机器人在路口上巡逻时，在第一行输出&ldquo;XLuo&rdquo;，第二行输出巡逻的路口数，第三行输出巡逻线路。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1：</p>
<p>OPEN</p>
<p>CLOSE</p>
<p> </p>
<p>样例2：</p>
<p>EPSON</p>
<p>SENPUM</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1：</p>
<p>XLuo</p>
<p>2</p>
<p>E-O</p>
<p> </p>
<p>样例2：</p>
<p>XLuo</p>
<p>4</p>
<p>E-N-P-S</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>