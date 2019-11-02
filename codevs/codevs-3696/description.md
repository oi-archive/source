<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">话说小 </span><span style="font-family: 'Calibri','sans-serif';">x </span><span style="">有一次去参加<span style="">比</span>赛<span style="">，</span>虽然学校离比赛地点不太远<span style="">，</span>但小 </span><span style="font-family: 'Calibri','sans-serif';">x </span><span style="">还是想坐 出租车去<span style="">。</span>大学城的出租车总是比较另类<span style="">，</span><span style="">有</span></span><span style="font-family: 'Calibri','sans-serif';">“</span><span style="">拼车</span><span style="font-family: 'Calibri','sans-serif';">”</span><span style="">一说<span style="">，</span>也就是说<span style="">，</span>你一个人 坐车去<span style="">，</span>还是一堆人一起<span style="">，</span>总共需要支付的钱是一样<span style="">的</span>（每辆出租上除司机外最 多坐下 </span><span style="font-family: 'Calibri','sans-serif';">4 </span><span style="">个人<span style="">）</span><span style="">。</span>刚好那天同校的一群 </span><span style="font-family: 'Calibri','sans-serif';">Oier </span><span style="">在校门口扎堆了<span style="">，</span>大家果断决定拼车 去赛场。</span></p><p style=""><span style="">问题来了<span style="">，</span>一辆又一辆的出租车经过<span style="">，</span>但里面要么坐满了乘客<span style="">，</span>要么只剩下 一两个座位，众 </span><span style="font-family: 'Calibri','sans-serif';">O<span style="">i</span>er </span><span style="">都觉得坐上去太亏了，小 </span><span style="font-family: 'Calibri','sans-serif';">x </span><span style="">也是这么想的。</span></p><p style=""><span style="">假设 </span><span style="font-family: 'Calibri','sans-serif';">N </span><span style="">位 </span><span style="font-family: 'Calibri','sans-serif';">Oier </span><span style="">准备<span style="">拼</span>车，此时为 </span><span style="font-family: 'Calibri','sans-serif';">0 </span><span style="">时刻，从校门到目的地需要支付给出租</span></p><p style=""><span style="">车师傅 </span><span style="font-family: 'Calibri','sans-serif';">D </span><span style="">元</span><span style="">（按车次<span style="">算</span><span style="">，</span>不管里面坐了多少 </span><span style="font-family: 'Calibri','sans-serif';">Oier</span><span style="">）</span><span style="">，</span><span style="">假如 </span><span style="font-family: 'Calibri','sans-serif';">S </span><span style="">分钟后恰能赶上比赛，</span></p><p style=""><span style="">那么 </span><span style="font-family: 'Calibri','sans-serif';">S </span><span style="">分钟后经过校门口的出租车自然可以忽略不计了<span style="">。</span>现在给出在这 </span><span style="font-family: 'Calibri','sans-serif';">S </span><span style="">分钟当</span></p><p style=""><span style="">中经过校门的所有的 </span><span style="font-family: 'Calibri','sans-serif';">K </span><span style="">辆出租车先后到达校门口的时间 </span><span style="font-family: 'Calibri','sans-serif';">T i <span style=""> </span></span><span style="">及里面剩余的座位 </span><span style="font-family: 'Calibri','sans-serif';">Z</span><span style="font-family: 'Calibri','sans-serif';">i</span></p><p style=""><span style="font-family: 'Calibri','sans-serif';">(</span><span style="font-family: 'Calibri','sans-serif';">1 &lt;= <span style="">Z</span>i &lt;= 4<span style="">)</span></span><span style="">，</span><span style="font-family: 'Calibri','sans-serif';">Oier </span><span style="">可以选择上车几个<span style="">人</span>（不能超过<span style="">）</span><span style="">，</span>当然<span style="">，</span>也可以选择上 </span><span style="font-family: 'Calibri','sans-serif';">0 </span><span style="">个</span></p><p style=""><span style="">人，那就是不坐这辆车。</span></p><p style=""><span style="">俗话说，时间就是金钱，这里小 </span><span style="font-family: 'Calibri','sans-serif';">x </span><span style="">把每个 </span><span style="font-family: 'Calibri','sans-serif';">Oier </span><span style="">在校门等待出租车的分钟数 等同于花了相同多的<span style="">钱</span>（例如小 </span><span style="font-family: 'Calibri','sans-serif';">x </span><span style="">等待了 </span><span style="font-family: 'Calibri','sans-serif';">2</span><span style="font-family: 'Calibri','sans-serif';">0 </span><span style="">分钟<span style="">，</span>那相当于他额外花了 </span><span style="font-family: 'Calibri','sans-serif';">2</span><span style="font-family: 'Calibri','sans-serif';">0 </span><span style="">元钱<span style="">）</span>。</span></p><p style=""><span style="">在保证所有 </span><span style="font-family: 'Calibri','sans-serif';">O<span style="">i</span>er </span><span style="">都能在比赛开始前到达比赛地点的情况下，聪明的你能计 算出他们最少需要花多少元钱么？</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">每组数据以四个整数 </span><span style="font-family: 'Calibri','sans-serif';">N , K , D , S </span><span style="">开始，具体<span style="">含</span>义参见题目描<span style="">述</span>。</span></p><p style=""><span style="">接着 </span><span style="font-family: 'Calibri','sans-serif';">K </span><span style="">行，表示第 </span><span style="font-family: 'Calibri','sans-serif';">i </span><span style="">辆出租车在第 </span><span style="font-family: 'Calibri','sans-serif';">T</span><span style="font-family: 'Calibri','sans-serif';">i </span><span style="">分钟到达校门，其空余的座位数为 </span><span style="font-family: 'Calibri','sans-serif';">Zi</span></p><p style=""><span style="">（时间按照先后顺序<span style="">）</span>。</span></p><p style=""><br></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin: 0 5px 0 40px;line-height: 21px"><span style="font-size:16px;font-family:宋体">对于每组测试数据<span style="letter-spacing:-7px">，</span>输出占一行<span style="letter-spacing:-7px">，</span>如果他们所有人能在比赛前到达比赛地点，</span></p><p style="margin-left: 8px;line-height: 21px"><span style="font-size:16px;font-family:宋体">则输出一个整数<span style="letter-spacing:-8px">，</span>代表他们最少需要花的<span style="letter-spacing: -8px">钱</span>（单位<span style="letter-spacing:-8px">：</span>元<span style="letter-spacing:-8px">）</span><span style="letter-spacing:-8px">，</span>否则请输<span style="letter-spacing:0">出</span></span><span style="font-size: 16px;font-family:&#39;Calibri&#39;,&#39;sans-serif&#39;;letter-spacing:1px">“</span><span style="font-size:16px;font-family:&#39;Calibri&#39;,&#39;sans-serif&#39;">im<span style="letter-spacing:0">p</span>oss<span style="letter-spacing:0">i</span><span style="letter-spacing:0">bl</span>e<span style="letter-spacing:-0">”</span></span><span style="font-size:16px;font-family:宋体">。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 2 10 5<br></p><p>1 1<br></p><p>2 2</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>14<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: Calibri, sans-serif;">N &lt;= 1<span style="">0</span><span style="">0</span></span><span style="">，</span><span style="font-family: Calibri, sans-serif;">K &lt;= 1<span style="">0</span><span style="">0</span></span><span style="">，</span><span style="font-family: Calibri, sans-serif;">D &lt;= 1<span style="">0</span><span style="">0</span></span><span style="">，</span><span style="font-family: Calibri, sans-serif;">S <span style="">&lt;</span>= <span style="">1</span>0<span style="">0</span></span><span style="">，</span><span style="font-family: Calibri, sans-serif;">1 &lt;= <span style="">Z</span>i &lt;= <span style="">4</span></span><span style="">，</span><span style="font-family: Calibri, sans-serif;">1<span style="">&lt;</span>= T<span style="">(</span>i) &lt;= T<span style="">(</span>i+<span style="">1</span>) &lt;= S</span></p>
</div>
</div>