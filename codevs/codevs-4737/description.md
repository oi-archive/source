<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">纪中分新旧校区，整个老区红墙绿瓦、</span><span style="">飞檐雕梁、厚重古朴、气势恢宏</span><span style="">。</span><span style="">新区主要为近十年先后竣工的一批与旧区格调一致的现代化建筑。校园内树木参天，花香绿浓，厚重典雅的宫殿式建筑与颇具时代感的现代化大楼交相辉映，景致怡人。</span></p><p style=""><span style="">凤凰花红 纪中最美！</span></p><p style=""><span style="">寿屏公园是纪中最独特的一个风景线，上面的道路崎岖不平。有一天你亲自走了一番，并用<span style="font-family: Courier New;">N</span><span style="">个数字表示路线上</span><span style="font-family: Courier New;">N</span><span style="">个点的高度，突然你对最大的爬坡高度产生兴趣，例如对于路线：</span><span style="font-family: Courier New;">12 3 5 7 10 6 1 11</span><span style="">，其中有两次连续爬坡，第一次是</span><span style="font-family: Courier New;">3 5 7 10</span><span style="">，爬坡高度为</span><span style="font-family: Courier New;">10-3=7</span><span style="">，第二次为</span><span style="font-family: Courier New;">1 11</span><span style="">，爬坡高度为</span><span style="font-family: Courier New;">11-1=10</span><span style="">。</span></span></p><p style=""><span style="">给定<span style="font-family: Courier New;">N</span><span style="">个数字表示高度，你决定编写程序来解决。</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">  第一行包含一个正整数<span style="font-family: Courier New;">N(1&lt;=N&lt;=1000)</span><span style="">，第二行包含</span><span style="font-family: Courier New;">N</span><span style="">个正整数</span><span style="font-family: Courier New;">Pi(1&lt;=Pi&lt;=1000)</span><span style="">，表示路线上</span><span style="font-family: Courier New;">N</span><span style="">个地方的高度。</span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style=";font-family:宋体;font-size:14px">&nbsp; 输出最大的爬坡高度，如果路线中没有出现上坡则输出<span style="font-family:Courier New">0</span><span style="font-family:宋体">。</span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例输入1：</p><p><span style="">5</span></p><p><span style="">1 2 1 4 6</span></p><p><br></p><p>样例输入2：</p><p><span style="">8</span></p><p><span style="">12 20 1 3 4 4 11 1</span></p><p><br></p><p>样例输入3：</p><p><span style="">6</span></p><p><span style="">10 8 8 6 4 3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例输出1:</p><p>5</p><p><br></p><p>样例输出2：</p><p>8</p><p><br></p><p>样例输出3：</p><p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">样例解释：</span></p><p><span style="">    样例<span style="font-family: Courier New;">2</span><span style="">中的上坡有</span><span style="font-family: Courier New;">3</span><span style="">段，分别是</span><span style="font-family: Courier New;">12-20,1-3-4</span><span style="">和</span><span style="font-family: Courier New;">4-11</span><span style="">，注意</span><span style="font-family: Courier New;">1-3-4-4-11</span><span style="">不算是上坡，因为</span><span style="font-family: Courier New;">4-4</span><span style="">这段并不是上坡。</span></span></p><p><br></p>
</div>
</div>