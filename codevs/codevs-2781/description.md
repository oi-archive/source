<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">“<span style="">彭！”我来到了天堂、地狱和人间的交界处，要好多生物在交谈！（好像只有</span><span style=""><span>5</span></span><span style="">个</span><span style=""><span>- -!</span></span><span style="">）<br>这</span><span style=""><span>5</span></span><span style="">个生物，编号为</span><span style=""><span>A~E</span></span><span style="">，每个生物都有一个身份，人类</span><span style=""><span>(human)</span></span><span style="">、天使</span><span style=""><span>(divine)</span></span><span style="">或恶魔</span><span style=""><span>(evil)</span></span><span style="">，天使永远说真话，恶魔永远说假话，人类白天说真话，晚上说假话。我完全无法分清他们的身份，现在请你根据他们的对话告诉我，哪些生物是天使，哪些生物是人类，哪些生物是恶魔，现在是白天还是晚上。 </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行是一个正整数</span><span style=""><span>n</span></span><span style="">。</span></p>
<p style=""><span style="">接下来</span><span style=""><span>n</span></span><span style="">行，是这些生物的对话，这些对话都是以下三个句子之一：</span></p>
<p style=""><span style="text-decoration: underline;"><span style="">•</span><span style=""><span>T: X is [not] (divine|human|evil|lying).</span></span></span></p>
<p style=""><span style="text-decoration: underline;"><span style="">•</span><span style=""><span>T: I am [not] (divine|human|evil|lying).</span></span></span></p>
<p style=""><span style="text-decoration: underline;"><span style="">•</span><span style=""><span>T: It is (day|night).</span></span></span></p>
<p style=""><span style="">方括号中的词可以出现也可以不出现，圆括号中由</span><span style=""><span>|</span></span><span style="">分隔的词必须出现一个。</span><span style=""><span>T</span></span><span style="">是说话者的编号，</span><span style=""><span>X</span></span><span style="">是被说者的编号。句子中没有多余的空格。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="cjk" style="margin-bottom: 0cm;"><span style="font-family: 文泉驿微米黑,Meiryo;">如果根据规则不可能有这样的对话，输出&ldquo;</span><span style="font-family: 文泉驿微米黑,Meiryo;"><span lang="en-US">This is impossible.&rdquo;</span></span><span style="font-family: 文泉驿微米黑,Meiryo;">。否则先按照编号顺序，如果可以确定</span><span style="font-family: 文泉驿微米黑,Meiryo;"><span lang="en-US">X</span></span><span style="font-family: 文泉驿微米黑,Meiryo;">的身份，输出&ldquo;</span><span style="font-family: 文泉驿微米黑,Meiryo;"><span lang="en-US">X is (divine|evil|human).&rdquo;</span></span><span style="font-family: 文泉驿微米黑,Meiryo;">，如果不能确定</span><span style="font-family: 文泉驿微米黑,Meiryo;"><span lang="en-US">X</span></span><span style="font-family: 文泉驿微米黑,Meiryo;">的身份，输出&ldquo;</span><span style="font-family: 文泉驿微米黑,Meiryo;"><span lang="en-US">I don't know who X is.&rdquo;</span></span><span style="font-family: 文泉驿微米黑,Meiryo;">。（</span><span style="font-family: 文泉驿微米黑,Meiryo;"><span lang="en-US">X</span></span><span style="font-family: 文泉驿微米黑,Meiryo;">为编号）最后如果可以确定是白天还是晚上，就输出&ldquo;</span><span style="font-family: 文泉驿微米黑,Meiryo;"><span lang="en-US">It is (day|night).&rdquo;</span></span><span style="font-family: 文泉驿微米黑,Meiryo;">，如果不能确定是白天还是晚上，输出&ldquo;</span><span style="font-family: 文泉驿微米黑,Meiryo;"><span lang="en-US">I don't know it is day or night.&rdquo;</span></span><span style="font-family: 文泉驿微米黑,Meiryo;">。<br />输出时不要有多余空格，行末不要有多余的回车。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">【样例输入</span><span style=""><span>1</span></span><span style="">】</span></p>
<p style=""><span style=""><span>3</span></span></p>
<p style=""><span style=""><span>A: B is evil.</span></span></p>
<p style=""><span style=""><span>A: B is human.</span></span></p>
<p style=""><span style=""><span>B: A is evil.</span></span></p>
<p style=""><span style="">【样例输入</span><span style=""><span>2</span></span><span style="">】</span></p>
<p style=""><span style=""><span>6</span></span></p>
<p style=""><span style=""><span>A: B is lying.</span></span></p>
<p style=""><span style=""><span>B: A is lying.</span></span></p>
<p style=""><span style=""><span>C: D is divine.</span></span></p>
<p style=""><span style=""><span>D: C is divine.</span></span></p>
<p style=""><span style=""><span>E: D is evil.</span></span></p>
<p style=""><span style=""><span>E: D is human.</span></span></p>
<p style=""><span style="">【样例输入</span><span style=""><span>3</span></span><span style="">】</span></p>
<p style=""><span style=""><span>1</span></span></p>
<p style=""><span style=""><span>A: I am evil.</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">【样例输出</span><span style=""><span>1</span></span><span style="">】</span></p>
<p style=""><span style=""><span>A is evil.</span></span></p>
<p style=""><span style=""><span>B is divine.</span></span></p>
<p style=""><span style=""><span>I don't know it is day or night.</span></span></p>
<p style=""><span style="">【样例输出</span><span style=""><span>2</span></span><span style="">】</span></p>
<p style=""><span style=""><span>I don't know who A is.</span></span></p>
<p style=""><span style=""><span>I don't know who B is.</span></span></p>
<p style=""><span style=""><span>C is divine.</span></span></p>
<p style=""><span style=""><span>D is divine.</span></span></p>
<p style=""><span style=""><span>I don't know who E is.</span></span></p>
<p style=""><span style=""><span>I don't know it is day or night.</span></span></p>
<p style=""><span style="">【样例输出</span><span style=""><span>3</span></span><span style="">】</span></p>
<p style=""><span style=""><span>A is human.</span></span></p>
<p style=""><span style=""><span>It is night.</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style=""><span>1≤n≤100</span></span></p>
</div>
</div>