<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">网页浏览器者有后退与前进按钮，一种实现这两个功能的方式是用两个栈，</span>“<span style="">前进栈</span>”<span style="">、</span>“<span style="">后退栈</span>”<span style="">。</span></p><p><span style="">这里你需要实现以下几个功能：</span></p><p style="">BACK: <span style="">如果</span>“<span style="">后退栈</span>”<span style="">为空则忽略此命令。否则将当前两面压入</span>“<span style="">前进栈</span>”<span style="">，从</span>“<span style="">后退栈</span>”<span style="">中取出栈顶页面，并设置为当前页面。</span></p><p style="">FORWARD: <span style="">如果</span>“<span style="">前进栈</span>”<span style="">为空则忽略此命令。否则将当前两面压入</span>“<span style="">后退栈</span>”<span style="">，从</span>“<span style="">前进栈</span>”<span style="">中取出栈顶页面，并设置为当前页面。</span></p><p style="">VISIT: <span style="">将当前页面压入</span>“<span style="">后退栈</span>”<span style="">、并将当前页面置为指定页面，并将</span>“<span style="">前进栈</span>”<span style="">置空。</span></p><p style="">QUIT: <span style="">退出。</span></p><p><span style="">假设此浏览器初始页面为</span>http://www.acm.org/</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入为一系列命令：</span>BACK, FORWARD, VISIT<span style="">和</span>QUIT<span style="">，页面网址为不含空格的字符串</span></p><p style=""><span style="">假设任一时刻任意时刻两个栈中的元素都不会超过</span>100<span style="">。</span></p><p style=""><span style="">最后一个命令为</span>QUIT<span style="">。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:28px"><span style="font-family:宋体">输对于除</span>QUIT<span style="font-family:宋体">外所有命令，输出当前页面（网址）</span></p><p style="text-indent:28px"><span style="font-family:宋体">如果该命令被忽略则输出</span>“Ignored”<span style="font-family:宋体">。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>VISIT http://acm.ashland.edu/</p><p>VISIT http://acm.baylor.edu/acmicpc/</p><p>BACK</p><p>BACK</p><p>BACK</p><p>FORWARD</p><p>VISIT http://www.ibm.com/</p><p>BACK</p><p>BACK</p><p>FORWARD</p><p>FORWARD</p><p>FORWARD</p><p>QUIT</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>http://acm.ashland.edu/</p><p>http://acm.baylor.edu/acmicpc/</p><p>http://acm.ashland.edu/</p><p>http://www.acm.org/</p><p>Ignored</p><p>http://acm.ashland.edu/</p><p>http://www.ibm.com/</p><p>http://acm.ashland.edu/</p><p>http://www.acm.org/</p><p>http://acm.ashland.edu/</p><p>http://www.ibm.com/</p><p>Ignored</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p></p><p><span style="">对于</span>&lt;font face="Calibri, sans-serif"&gt;<span style="">100</span>&lt;/font&gt;%<span style="">的数据，操作数量不超过</span><span style="font-family: 'Calibri','sans-serif';">1000</span><span style="">，每行字符串长度不超过</span><span style="font-family: 'Calibri','sans-serif';">500</span><span style="">。</span></p><p><span style="font-family: Calibri, sans-serif;">              </span></p><hr><p><span style="font-family: Calibri, sans-serif;"></span><br></p>
</div>
</div>