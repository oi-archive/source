<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>code-11 是一种条形码编码系统，用来将一个字符串编码为条形码。在这种编码系统中</p><p>可以使用的字符仅有数字0 到9 以及"-"号，以及特殊的start/stop 字符放在条形码的开头</p><p>和结尾。对于每个字符，都对应了一个长度为5 的01 串如下所示，对应到条形码中，每个</p><p>条形码都是由黑白相隔的条带组成的，且第一个条带为黑色。条带分为宽和窄两种，宽带的</p><p>宽度为窄带的两倍，0 表示窄的，1 表示宽的条带。</p><p><span style="">           character               Encoding</span><br style=""><span style="">                0                           00001</span><br style=""><span style="">                1                           10001</span><br style=""><span style="">                2                           01001</span><br style=""><span style="">                3                           11000</span><br style=""><span style="">                4                           00101</span><br style=""><span style="">                5                           10100</span><br style=""><span style="">                6                           01100</span><br style=""><span style="">                7                           00011</span><br style=""><span style="">                8                           10010</span><br style=""><span style="">                9                           10000</span><br style=""><span style="">                -                            00100</span><br style=""><span style="">            Start/Stop                00110</span></p><p>而每两个相邻的字符之间一定是一个白色窄带作为分隔。</p><p>为了能够检测条形码的正确性，我们加入两个检测数字C 和K，加在条形码的末尾(在stop 之前)。设需编码的字符串为c1...cn,则C 为：</p><p>    n</p><p>（  ∑ (（n-i）mod 10 +1）*w(ci)) mod 11</p><p>   i=1</p><p>K 为：</p><p>   n+1</p><p>（ ∑ (（n-i）mod 10 +1）*w(ci)) mod 11</p><p>   i=1</p><p>而cn+1 即为C。其中w(ci)为每个字符的权重。0 到9 即为0 到9。"-"为10。</p><p>举个例子，对于字符串123-45，C 和K 分别等于5 和2，则条形码为123-4552，并在前</p><p>后加上start 和stop 符号。</p><p>在实际应用中，通过探测器探测出每个条带的宽度后，通过解析软件将条形码还原为原本的字符串。由于条形码方向并未固定，所以软件必须自己判断这个条形码是从左至右的还是从右至左的。</p><p> 现在，你的任务是扫描并解析一个条形码。你所拥有的信息为每个条带的宽度，但由于设备总是会有误差的，所以，宽带宽度不一定严格的是窄带的宽度的两倍，你的程序需要能够容忍5%的误差。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>由于输出的特殊情况较多，所以采用多组测试数据。</p><p> 输入第一行包括一个整数T表示测试数据的组数，对于每组数据首先是一个整数n表示该条形码有多少条带。接着n个整数d1..dn以空格隔开表示了每个条带的宽度。再次强调你并不知道这个条形码是从左至右的还是从右至左的，你需要正着和反着都判断一遍。</p><p> T &lt;= 20, n &lt;= 150, di&lt;=200。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每组数据输出一行。</p><p>&nbsp;输出时分如下几种情况。若该条形码合法，则输出解析所得的原字符串，不包括检测字符C和K。若可以成功解析但是检测字符C错了，则输出&quot;bad C&quot;。若C也是对的，但K是错的，则输出&quot;bad K&quot;。对于剩下所有情况输出bad code。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p>59 </p><p>10 20 20 10 10 10 20 10 10 20 10 10 10 10 20 10 20 10 10 10 20 10 20 10 20 10 20 10 10 10 10 10 20 10 10 10 10 10 10 20 20 10 20 10 10 20 10 10 20 10 10 10 20 10 10 20 20 10 10 </p><p>35 </p><p>10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 10 </p><p>35 </p><p>10 10 20 20 10 10 20 10 10 10 20 10 10 20 10 10 20 10 10 10 20 10 20 10 20 10 10 10 10 10 10 10 20 20 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>123-45 </p><p>bad code </p><p>bad K</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>T &lt;= 20, n &lt;= 150, di&lt;=200。</p>
</div>
</div>