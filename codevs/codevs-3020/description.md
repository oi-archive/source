<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">在高老庄猪八戒过着无忧无虑的生活，他有一棵桃树，原有</span><span style="font-family: Calibri,sans-serif;"><span style=""><span>n</span></span></span><span style="">个桃子，他每天的桃数变为前一天的</span><span style="font-family: Calibri,sans-serif;"><span style=""><span>2</span></span></span><span style="">倍，猪吃</span><span style="font-family: Calibri,sans-serif;"><span style=""><span>m</span></span></span><span style="">天，每天吃</span><span style="font-family: Calibri,sans-serif;"><span style=""><span>p1,p2,p3...pm</span></span></span><span style="">个桃，求若桃被猪吃完或不够吃，输出“</span><span style="font-family: Calibri,sans-serif;"><span style=""><span>-<span style="">”</span></span></span></span><span style="">加上他不够吃的那一天，若</span><span style="font-family: Calibri,sans-serif;"><span style=""><span>m</span></span></span><span style="">天过了还有桃，输出剩下桃的个数（猪八戒先吃桃再长）</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">参见样例</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="cjk" style="margin-bottom: 0cm;"><span style="font-size: medium;">参见样例</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入样例</span><span style="font-family: Calibri,sans-serif;"><span style=""><span>1</span></span></span><span style="">：</span></p>
<p style=""><span style="font-family: Calibri,sans-serif;"><span style=""><span>30            //n</span></span></span><span style="">个桃</span></p>
<p style=""><span style="font-family: Calibri,sans-serif;"><span><span style="">5              //</span></span></span><span style="">猪吃</span><span style="font-family: Calibri,sans-serif;"><span><span style="">5</span></span></span><span style="">天</span></p>
<p style=""><span style="font-family: Calibri,sans-serif;"><span><span style="">20 20 5 10 5</span></span></span></p>
<p style=""><span style="">输入样例</span><span style="font-family: Calibri,sans-serif;"><span style=""><span>2</span></span></span><span style="">：</span></p>
<p style=""><span style="font-family: Calibri,sans-serif;"><span style=""><span>60           //n</span></span></span><span style="">个桃</span></p>
<p style=""><span style="font-family: Calibri,sans-serif;"><span><span style="">4             //4</span></span></span><span style="">天</span></p>
<p style=""><span style="font-family: Calibri,sans-serif;"><span><span style="">20 30 40 110</span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输出样例</span><span style="font-family: Calibri,sans-serif;"><span><span style="">1</span></span></span><span style="">：</span><span style="font-family: Calibri,sans-serif;"><span><span style="">-2  //</span></span></span><span style="">第二天吃完</span></p>
<p style=""> </p>
<p style=""><span style="">输出样例</span><span style="font-family: Calibri,sans-serif;"><span><span style="">2</span></span></span><span style="">：</span><span style="font-family: Calibri,sans-serif;"><span><span style="">20 </span></span></span></p>
<p style=""><span style="font-family: Calibri,sans-serif;"><span><span style="">//{</span></span></span><span style="">剩</span><span style="font-family: Calibri,sans-serif;"><span><span style="">20</span></span></span><span style="">个（</span><span style="font-family: Calibri,sans-serif;"><span><span style="">60-20</span></span></span><span style="">）</span><span style="font-family: Calibri,sans-serif;"><span><span style="">*2=80 </span></span></span><span style="">（</span><span style="font-family: Calibri,sans-serif;"><span><span style="">80-30</span></span></span><span style="">）</span><span style="font-family: Calibri,sans-serif;"><span><span style="">*2=100</span></span></span></p>
<p style=""> </p>
<p style=""><span style="">（</span><span style="font-family: Calibri,sans-serif;"><span><span style="">100-40</span></span></span><span style="">）</span><span style="font-family: Calibri,sans-serif;"><span><span style="">*2=120 </span></span></span><span style="">（</span><span style="font-family: Calibri,sans-serif;"><span><span style="">120-110</span></span></span><span style="">）</span><span style="font-family: Calibri,sans-serif;"><span><span style="">*2=20}</span></span></span></p>
<p style=""><span style=""><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">数据范围</span><span style="font-family: Calibri,sans-serif;"><span><span style="">:m&lt;=1000 n&lt;2</span><sup><span style="">64</span></sup><span style=""> p1,p2,p3...pm&lt;2</span><sup><span style="">64</span></sup></span></span></p>
<p style=""><span style="">PASCAL 选手提示</span><span style="font-family: Calibri,sans-serif;"><span><span style="">: 1: n,p1,p2,p3...pm</span></span></span><span style="">用</span><span style="font-family: Calibri,sans-serif;"><span><span style="">qword</span></span></span><span style="">存储</span></p>
<p style=""><span style="font-family: Calibri,sans-serif;"><span style=""><span>2</span></span></span><span style="">：读入一个处理一个</span></p>
<p style=""><span style="font-family: Calibri,sans-serif;"><span><span style="">3</span></span></span><span style="">：</span><span style="font-family: Calibri,sans-serif;"><span><span style="">qword</span></span></span><span style="">不可存储负数</span></p>
</div>
</div>