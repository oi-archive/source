<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">小奇要开采一些矿物，它驾驶着一台带有钻头（初始能力值w）的飞船，按既定路线依次飞过喵星系的n个星球。</span></p><p><br></p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">星球分为2类：资源型和维修型。</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">1.资源型：含矿物质量a[i]，若选择开采，则得到a[i]*p的金钱，之后钻头损耗k%，即p=p*(1-0.01k)</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">2.维修型：维护费用b[i]，若选择维修，则支付b[i]*p的金钱，之后钻头修复c%，即p=p*(1+0.01c)</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">（p为钻头当前能力值）</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">注：维修后钻头的能力值可以超过初始值</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">请你帮它决策最大化这个收入</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">第一行4个整数n，k，c，w。</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">以下n行，每行2个整数type，x。</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">type为1则代表其为资源型星球，x为其矿物质含量a[i]；</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">type为2则代表其为维修型星球，x为其维护费用b[i]；</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &#39;Helvetica Neue&#39;, &#39;Trebuchet MS&#39;, Helvetica, &#39;Microsoft YaHei&#39;, Georgia, &#39;sans Microsoft YaHei&#39;, sans-serif; line-height: 25.6px; background-color: rgb(255, 255, 255);">输出一行一个实数（保留两位小数），表示要求的结果。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">5 50 50 10</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">1 10</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">1 20</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">2 10</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">2 20</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">1 30</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">375.00</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;"> </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">对于30%的数据 n&lt;=100</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">对于50%的数据 n&lt;=1000，k=100</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">对于100%的数据 n&lt;=100000，0&lt;=k，c，w，a[i]，b[i]&lt;=100</p><p style="font-family: 'Helvetica Neue', 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, 'sans Microsoft YaHei', sans-serif;">保证答案不超过10^9</p><p><br></p>
</div>
</div>