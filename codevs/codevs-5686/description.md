<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">WLY</span><span style="">最近喜欢刨土。今天，他竟然在花园里挖出了一个月光宝盒！WLY最近对这个宝盒进行了研究，发现这个宝盒只有在晚上才可启动。另外，每次使用时都会出现2道很简单的数学题（加减乘除），只有都回答正确，才能开启。</span></p><p><span style="">不过有个问题：春夏秋冬晚上的时间不一样，所以开启时间也不一样，具体如下：</span></p><p><span style="">春季 20：00黑天 6：30白天   秋季 20：30黑天 6：00白天</span></p><p><span style="">夏季 21：00黑天 5：00白天   冬季 19：30黑天 5：30白天</span></p><p><span style="">已知月份表如下：（2016年）</span></p><table cellpadding="0" cellspacing="0"><tbody><tr><td style="" valign="top" width="114"><br></td><td style="" valign="top" width="114"><p><span style="">开始月份</span></p></td><td style="" valign="top" width="114"><p><span style="">开始日期</span></p></td><td style="" valign="top" width="114"><p><span style="">结束月份</span></p></td><td style="" valign="top" width="114"><p><span style="">结束日期</span></p></td></tr><tr><td style="" valign="top" width="114"><p><span style="">冬季</span></p></td><td style="" valign="top" width="114"><p><span style="">1</span></p></td><td style="" valign="top" width="114"><p><span style="">1</span></p></td><td style="" valign="top" width="114"><p><span style="">2</span></p></td><td style="" valign="top" width="114"><p><span style="">3</span></p></td></tr><tr><td style="" valign="top" width="114"><p><span style="">春季</span></p></td><td style="" valign="top" width="114"><p><span style="">2</span></p></td><td style="" valign="top" width="114"><p><span style="">4</span></p></td><td style="" valign="top" width="114"><p><span style="">6</span></p></td><td style="" valign="top" width="114"><p><span style="">20</span></p></td></tr><tr><td style="" valign="top" width="114"><p><span style="">夏季</span></p></td><td style="" valign="top" width="114"><p><span style="">6</span></p></td><td style="" valign="top" width="114"><p><span style="">21</span></p></td><td style="" valign="top" width="114"><p><span style="">8</span></p></td><td style="" valign="top" width="114"><p><span style="">6</span></p></td></tr><tr><td style="" valign="top" width="114"><p><span style="">秋季</span></p></td><td style="" valign="top" width="114"><p><span style="">8</span></p></td><td style="" valign="top" width="114"><p><span style="">7</span></p></td><td style="" valign="top" width="114"><p><span style="">11</span></p></td><td style="" valign="top" width="114"><p><span style="">6</span></p></td></tr><tr><td style="" valign="top" width="114"><p><span style="">冬季</span></p></td><td style="" valign="top" width="114"><p><span style="">11</span></p></td><td style="" valign="top" width="114"><p><span style="">7</span></p></td><td style="" valign="top" width="114"><p><span style="">12</span></p></td><td style="" valign="top" width="114"><p><span style="">31</span></p></td></tr></tbody></table><p><span style="">别忘了，月光宝盒上还会出现2道算术题，2道均回答正确，方可打开！</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行：日期（格式：M/MM D/DD，例1：1 2；例2：10 24）</span></p><p><span style="">第二行：当时时间（格式：时 分 秒（没有前导0））</span></p><p><span style="">第三行、第四行：两道算数题，一个字符和两个数，（格式：参数1 运算符号 参数2），运算符号：+加、-减、*乘、/除。（注意：参数1、运算符号、参数2之间空格隔开）</span></p><p><span style="">第五行、第六行：第三、四行WLY输入的运算结果。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size:19px;font-family:&#39;微软雅黑 Light&#39;">若WLY能打开，输出3行：</span></p><p><span style="font-size:19px;font-family:&#39;微软雅黑 Light&#39;">第一行输出”YES”；</span></p><p><span style="font-size:19px;font-family:&#39;微软雅黑 Light&#39;">第二行输出当天年份、月份、日期、时、分、秒（中间空格隔开）；</span></p><p><span style="font-size:19px;font-family:&#39;微软雅黑 Light&#39;">第三行输出两个数：两道算术题的正确答案（空格隔开）</span></p><p><span style="font-size:19px;font-family:&#39;微软雅黑 Light&#39;">若WLY不能打开，输出两行：</span></p><p><span style="font-size:19px;font-family:&#39;微软雅黑 Light&#39;">如果WLY仅是因为没有到晚上而无法打开，则输出“time error”,如果WLY仅是因为运算错误而无法打开，输出错误的题目数。</span></p><p><span style="font-size:19px;font-family:&#39;微软雅黑 Light&#39;">若WLY两项均不满足，则先输出”time error“，再隔空格输出错误的题目数。</span></p><p><span style="font-size:19px;font-family:&#39;微软雅黑 Light&#39;">第二行输出两个数：错误的题目的正确答案（空格隔开）（若有两道题错误，则先输出1号题目，再输出2号题目）</span></p><p><span style="font-size:19px;font-family:&#39;微软雅黑 Light&#39;">另：若计算题没有错误，则不输出第2行。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">4 17</span></p><p><span style="">21 19 5</span></p><p><span style="">7 + 2</span></p><p><span style="">5 * 3</span></p><p><span style="">9</span></p><p><span style="">15</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">YES</span></p><p><span style="">2016 4 17 21 19 5</span></p><p><span style="">9 15</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于100%的数据：</span></p><p><span style="">1</span><span style="">、年份、月份、日期、时、分、秒均在正常范围内</span></p><p><span style="">2</span><span style="">、2道题目中的被除数能被除数整除且除数不为0</span></p><p><span style="">By cplus<br></span></p>
</div>
</div>