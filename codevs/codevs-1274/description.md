<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Many communities now have “radar” signs that tell drivers what their speed is, in the hope that they will slow down.</p>
<p>许多社区现在有了雷达标志来告诉司机们他们的速度，以期待他们会减速。</p>
<p> </p>
<p>You will output a message for a “radar” sign. The message will display information to a driver based on his/her speed according to the following table:</p>
<p>你要输出一个雷达标志的消息，这条消息会显示一个司机的速度和他要交的罚金的关系的信息，看下面的表格：</p>
<p><br>km/h over the limit Fine</p>
<p>1 to 20 $100</p>
<p>21 to 30 $270</p>
<p>31 or above $500</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The user will be prompted to enter two integers. First, the user will be prompted to enter the speed limit. Second, the user will be prompted to enter the recorded speed of the car.</p>
<p>用户会输入2个整数。首先，用户会提供限速。然后，会输入车速的纪录。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>If the driver is not speeding, the output should be:<br />Congratulations, you are within the speed limit<br />If the driver is speeding, the output should be:<br />You are speeding and your fine is $ F<br />where F is the amount of the ﬁne as described in the table above</p>
<p>如果他没有超速，要输出Congratulations, you are within the speed limit</p>
<p>如果他超速，要输出You are speeding and your fine is $ F</p>
<p>F就是根据表格的描述计算出的罚金</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>Sample Session 1 (<span style="">with output shown in text, user input in italics 只输入斜体</span>)</p>
<p>Enter the speed limit: <em>40</em></p>
<p>Enter the recorded speed of the car: <em>39</em></p>
<p><br>Sample Session 2</p>
<p>Enter the speed limit:<em>100</em></p>
<p>Enter the recorded speed of the car: <em>131</em></p>
<p> </p>
<p>Sample Session 3</p>
<p>Enter the speed limit:<em>100</em></p>
<p>Enter the recorded speed of the car: <em>120</em></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Congratulations, you are within the speed limit</p>
<p>You are speeding and your fine is $ 500</p>
<p>You are speeding and your fine is $ 100</p>
<p> </p>
<p>注意：“Enter the speed limit:”和“Enter the recorded speed of the car:”也是要输出的。所以完整的输出是：</p>
<p>（以第一个样例为参考）Enter the speed limit:Enter the recorded speed of the car:Congratulations, you are within the speed limit</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>输入描述一定会按照输入描述里的输入</p>
</div>
</div>