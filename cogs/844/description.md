# 题目描述


<p style="text-align:center;text-indent:8.0pt;" align="center">
	<span style="font-size:16pt;font-family:&#39;Microsoft YaHei&#39;;">麻将</span><b><span style="font-family:&#39;Microsoft YaHei&#39;;color:red;">（</span><span style="color:red;font-family:&#39;Microsoft YaHei&#39;;">majiang.pas/c/cpp</span></b><b><span style="font-family:&#39;Microsoft YaHei&#39;;color:red;">）</span><span style="color:red;"></span></b> 
</p>
<p style="text-indent:5.25pt;">
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;">题目描述：</span><span></span></b> 
</p>
<p style="text-indent:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">DreamTeam </span><span style="font-family:&#39;Microsoft YaHei&#39;;">成员每天晚上的必修课当然是打麻将</span><span style="font-family:&#39;Microsoft YaHei&#39;;">!</span> 
</p>
<p style="text-indent:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">可是</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Geer</span><span style="font-family:&#39;Microsoft YaHei&#39;;">每次打完都是输</span><span style="font-family:&#39;Microsoft YaHei&#39;;">(</span><span style="font-family:&#39;Microsoft YaHei&#39;;">因为她刚学会打麻将</span><span style="font-family:&#39;Microsoft YaHei&#39;;">,</span><span style="font-family:&#39;Microsoft YaHei&#39;;">经常瞎<span style="font-family:&#39;Microsoft YaHei&#39;;"><strong>和</strong><span style="font-family:&#39;Microsoft YaHei&#39;;">(音胡，意即赢得胜利)</span></span></span><span style="font-family:&#39;Microsoft YaHei&#39;;">,</span><span style="font-family:&#39;Microsoft YaHei&#39;;">该<span style="font-family:&#39;Microsoft YaHei&#39;;">和</span>不<span style="font-family:&#39;Microsoft YaHei&#39;;">和</span></span><span style="font-family:&#39;Microsoft YaHei&#39;;">----</span><span style="font-family:&#39;Microsoft YaHei&#39;;">输了又要请大家喝奶茶</span><span style="font-family:&#39;Microsoft YaHei&#39;;">)</span> 
</p>
<p style="text-indent:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">但是</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Geer</span><span style="font-family:&#39;Microsoft YaHei&#39;;">不服输</span><span style="font-family:&#39;Microsoft YaHei&#39;;">,</span><span style="font-family:&#39;Microsoft YaHei&#39;;">又仗着自己学了几天编程</span><span style="font-family:&#39;Microsoft YaHei&#39;;">,</span><span style="font-family:&#39;Microsoft YaHei&#39;;">自以为不得了</span><span style="font-family:&#39;Microsoft YaHei&#39;;">!</span> 
</p>
<p style="text-indent:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">于是她决定遍写一个程序来</span><span style="font-family:&#39;Microsoft YaHei&#39;;">,</span><span style="font-family:&#39;Microsoft YaHei&#39;;">提高自己对麻将的熟悉程度</span><span style="font-family:&#39;Microsoft YaHei&#39;;">!(</span><span style="font-family:&#39;Microsoft YaHei&#39;;">避免少输点</span><span style="font-family:&#39;Microsoft YaHei&#39;;">);</span> 
</p>
<p style="text-indent:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;"> </span> 
</p>
<p style="text-indent:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">不会打麻将的要耽误点时间看了</span><span style="font-family:&#39;Microsoft YaHei&#39;;">(</span><span style="font-family:&#39;Microsoft YaHei&#39;;">会打的阴到笑</span><span style="font-family:&#39;Microsoft YaHei&#39;;">).. 21</span><span style="font-family:&#39;Microsoft YaHei&#39;;">世纪</span><span style="font-family:&#39;Microsoft YaHei&#39;;">..</span><span style="font-family:&#39;Microsoft YaHei&#39;;">还有人不会打麻将</span><span style="font-family:&#39;Microsoft YaHei&#39;;">(</span><span style="font-family:&#39;Microsoft YaHei&#39;;">偶</span><span style="font-family:&#39;Microsoft YaHei&#39;;">5</span><span style="font-family:&#39;Microsoft YaHei&#39;;">岁就会</span><span style="font-family:&#39;Microsoft YaHei&#39;;">,</span><span style="font-family:&#39;Microsoft YaHei&#39;;">第一次帮我爸打了一盘还赢了</span><span style="font-family:&#39;Microsoft YaHei&#39;;">5</span><span style="font-family:&#39;Microsoft YaHei&#39;;">元钱</span><span style="font-family:&#39;Microsoft YaHei&#39;;">...</span><span style="font-family:&#39;Microsoft YaHei&#39;;">表鄙视我</span><span style="font-family:&#39;Microsoft YaHei&#39;;">!):</span> 
</p>
<p style="text-indent:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">麻将总共</span><span style="font-family:&#39;Microsoft YaHei&#39;;">108</span><span style="font-family:&#39;Microsoft YaHei&#39;;">张</span><span style="font-family:&#39;Microsoft YaHei&#39;;">     </span><span style="font-family:&#39;Microsoft YaHei&#39;;">筒</span><span style="font-family:&#39;Microsoft YaHei&#39;;">,</span><span style="font-family:&#39;Microsoft YaHei&#39;;">条</span><span style="font-family:&#39;Microsoft YaHei&#39;;">,</span><span style="font-family:&#39;Microsoft YaHei&#39;;">万</span> <span style="font-family:&#39;Microsoft YaHei&#39;;">分别有</span><span style="font-family:&#39;Microsoft YaHei&#39;;">4</span><span style="font-family:&#39;Microsoft YaHei&#39;;">张一样的</span><span style="font-family:&#39;Microsoft YaHei&#39;;">  1..9  </span> 
</p>
<p style="text-indent:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">如</span><span style="font-family:&#39;Microsoft YaHei&#39;;">  1</span><span style="font-family:&#39;Microsoft YaHei&#39;;">筒</span><span style="font-family:&#39;Microsoft YaHei&#39;;">4</span><span style="font-family:&#39;Microsoft YaHei&#39;;">张</span><span style="font-family:&#39;Microsoft YaHei&#39;;"> 1</span><span style="font-family:&#39;Microsoft YaHei&#39;;">条</span><span style="font-family:&#39;Microsoft YaHei&#39;;">4</span><span style="font-family:&#39;Microsoft YaHei&#39;;">张</span><span style="font-family:&#39;Microsoft YaHei&#39;;">  1</span><span style="font-family:&#39;Microsoft YaHei&#39;;">万</span><span style="font-family:&#39;Microsoft YaHei&#39;;">4</span><span style="font-family:&#39;Microsoft YaHei&#39;;">张</span><span style="font-family:&#39;Microsoft YaHei&#39;;">  2</span><span style="font-family:&#39;Microsoft YaHei&#39;;">筒</span><span style="font-family:&#39;Microsoft YaHei&#39;;">4</span><span style="font-family:&#39;Microsoft YaHei&#39;;">张</span><span style="font-family:&#39;Microsoft YaHei&#39;;"> 2</span><span style="font-family:&#39;Microsoft YaHei&#39;;">条</span><span style="font-family:&#39;Microsoft YaHei&#39;;">4</span><span style="font-family:&#39;Microsoft YaHei&#39;;">张</span><span style="font-family:&#39;Microsoft YaHei&#39;;">.......  9</span><span style="font-family:&#39;Microsoft YaHei&#39;;">筒</span><span style="font-family:&#39;Microsoft YaHei&#39;;">4</span><span style="font-family:&#39;Microsoft YaHei&#39;;">张</span><span style="font-family:&#39;Microsoft YaHei&#39;;"> 9</span><span style="font-family:&#39;Microsoft YaHei&#39;;">条</span><span style="font-family:&#39;Microsoft YaHei&#39;;">4</span><span style="font-family:&#39;Microsoft YaHei&#39;;">张</span><span style="font-family:&#39;Microsoft YaHei&#39;;"> 9</span><span style="font-family:&#39;Microsoft YaHei&#39;;">万</span><span style="font-family:&#39;Microsoft YaHei&#39;;">4</span><span style="font-family:&#39;Microsoft YaHei&#39;;">张</span> <span style="font-family:&#39;Microsoft YaHei&#39;;">没了</span><span style="font-family:&#39;Microsoft YaHei&#39;;">!  3*4*9=108  </span><span style="font-family:&#39;Microsoft YaHei&#39;;">没错吧</span><span style="font-family:&#39;Microsoft YaHei&#39;;">!  </span> 
</p>
<p style="text-indent:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">图形：<img src="/images/upload/image/20120707/20120707210626_51618.png" alt=""/></span><span></span> 
</p>
<p style="text-indent:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">字符：</span><span style="font-family:&#39;Microsoft YaHei&#39;;">W1
W2 W3 T1 T2 T3 W9 W9 W9 T7 T8 T9 T9 T9 </span><span style="font-family:&#39;Microsoft YaHei&#39;;">此样例表示已经胡了！！！</span><span></span> 
</p>
<p style="margin-left:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">例如：</span><span style="font-family:&#39;Microsoft YaHei&#39;;">3</span><span style="font-family:&#39;Microsoft YaHei&#39;;">个连续的并且都全部属于</span> <span style="font-family:&#39;Microsoft YaHei&#39;;">万或条或筒</span> <span style="font-family:&#39;Microsoft YaHei&#39;;">叫做一个</span> <span style="font-family:&#39;Microsoft YaHei&#39;;">搭子吧</span><span style="font-family:&#39;Microsoft YaHei&#39;;">  3</span><span style="font-family:&#39;Microsoft YaHei&#39;;">个一样的</span> <span style="font-family:&#39;Microsoft YaHei&#39;;">也叫一个搭子吧</span> <span style="font-family:&#39;Microsoft YaHei&#39;;">要想<strong>和</strong><strong>牌</strong></span> <span style="font-family:&#39;Microsoft YaHei&#39;;">还必须有一个对子（就是</span><span style="font-family:&#39;Microsoft YaHei&#39;;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;">个一样的）</span><span> </span> 
</p>
<p style="margin-left:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">如上面就是前</span><span style="font-family:&#39;Microsoft YaHei&#39;;">12</span><span style="font-family:&#39;Microsoft YaHei&#39;;">张牌就是</span><span style="font-family:&#39;Microsoft YaHei&#39;;">4</span><span style="font-family:&#39;Microsoft YaHei&#39;;">个搭子</span> <span style="font-family:&#39;Microsoft YaHei&#39;;">后面</span><span style="font-family:&#39;Microsoft YaHei&#39;;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;">个</span><span style="font-family:&#39;Microsoft YaHei&#39;;">9</span><span style="font-family:&#39;Microsoft YaHei&#39;;">筒叫对子！</span> <span style="font-family:&#39;Microsoft YaHei&#39;;">就算<span style="font-family:&#39;Microsoft YaHei&#39;;">和</span>牌了！</span><span></span> 
</p>
<p style="margin-left:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">唯一的特殊情况就是</span><span style="font-family:&#39;Microsoft YaHei&#39;;">7</span><span style="font-family:&#39;Microsoft YaHei&#39;;">个对子也算<span style="font-family:&#39;Microsoft YaHei&#39;;">和</span>（巧七对）</span><span></span> 
</p>
<p style="margin-left:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;"> </span><span style="font-family:&#39;Microsoft YaHei&#39;;">注意：要<span style="font-family:&#39;Microsoft YaHei&#39;;">和</span>牌必须</span><span style="font-family:&#39;Microsoft YaHei&#39;;">4</span><span style="font-family:&#39;Microsoft YaHei&#39;;">个搭子</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;">个对子或者</span><span style="font-family:&#39;Microsoft YaHei&#39;;">7</span><span style="font-family:&#39;Microsoft YaHei&#39;;">个对子！</span><span></span> 
</p>
<p style="text-indent:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;"> </span> 
</p>
<p style="text-indent:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">开始</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Geer</span><span style="font-family:&#39;Microsoft YaHei&#39;;">只有</span><span style="font-family:&#39;Microsoft YaHei&#39;;">13</span><span style="font-family:&#39;Microsoft YaHei&#39;;">牌</span><span style="font-family:&#39;Microsoft YaHei&#39;;">  </span> 
</p>
<p style="text-indent:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">如：样例假如第一张</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;">万开始的时候没有</span> <span style="font-family:&#39;Microsoft YaHei&#39;;">则刚好</span><span style="font-family:&#39;Microsoft YaHei&#39;;">13</span><span style="font-family:&#39;Microsoft YaHei&#39;;">张，你要输出的结果就是他还需要一张什么牌他才能<span style="font-family:&#39;Microsoft YaHei&#39;;">和</span>牌</span> <span style="font-family:&#39;Microsoft YaHei&#39;;">这样他继可以<span style="font-family:&#39;Microsoft YaHei&#39;;">和</span></span><span style="font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;">万</span> <span style="font-family:&#39;Microsoft YaHei&#39;;">也可以<span style="font-family:&#39;Microsoft YaHei&#39;;">和</span></span><span style="font-family:&#39;Microsoft YaHei&#39;;">4</span><span style="font-family:&#39;Microsoft YaHei&#39;;">万</span><span></span> 
</p>
<p style="text-indent:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;"> </span> 
</p>
<p style="text-indent:36.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">W2</span><span style="font-family:&#39;Microsoft YaHei&#39;;">：表示</span><span style="font-family:&#39;Microsoft YaHei&#39;;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;">万</span><span style="font-family:&#39;Microsoft YaHei&#39;;">   T1</span><span style="font-family:&#39;Microsoft YaHei&#39;;">：表示</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;">筒</span><span style="font-family:&#39;Microsoft YaHei&#39;;">   D3</span><span style="font-family:&#39;Microsoft YaHei&#39;;">：表示</span><span style="font-family:&#39;Microsoft YaHei&#39;;">3</span><span style="font-family:&#39;Microsoft YaHei&#39;;">条</span><span></span> 
</p>
<p style="text-indent:5.25pt;">
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;">输入数据：</span><span></span></b> 
</p>
<p style="text-indent:15.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">13</span><span style="font-family:&#39;Microsoft YaHei&#39;;">张牌，每张一个空格；（最后那张没空格）</span><span></span> 
</p>
<p style="margin-left:5.25pt;">
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;">输出数据：</span><span></span></b> 
</p>
<p style="margin-left:15.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">如何再需要一张能<span style="font-family:&#39;Microsoft YaHei&#39;;">和</span>牌</span> <span style="font-family:&#39;Microsoft YaHei&#39;;">输出这张牌的所有可能性（注意空格，输出的结果数字小的写到前面</span> <span style="font-family:&#39;Microsoft YaHei&#39;;">）</span><span style="font-family:&#39;Microsoft YaHei&#39;;">  </span><span style="font-family:&#39;Microsoft YaHei&#39;;">如果再要一张也不能<span style="font-family:&#39;Microsoft YaHei&#39;;">和</span>牌，则输出“</span><span style="font-family:&#39;Microsoft YaHei&#39;;">NO!</span><span style="font-family:&#39;Microsoft YaHei&#39;;">”</span><span></span> 
</p>
<p style="margin-left:5.25pt;text-indent:10.5pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">数据很符合大众化！不会很变态！大家放心做！</span><span></span> 
</p>
<p>
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;">样例：</span><span></span></b> 
</p>
<p style="text-indent:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">Input</span><span style="font-family:&#39;Microsoft YaHei&#39;;">：</span><span> </span> 
</p>
<p style="text-indent:15.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">W2 W3 T1 T2 T3 W9 W9 W9 T7 T7 T9 T9 T9 </span> 
</p>
<p style="text-indent:5.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">Output:</span> 
</p>
<p style="text-indent:15.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">W1 W4</span> 
</p>
<p>
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;">时间限制：</span><span></span></b> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;">  </span><span style="font-family:&#39;Microsoft YaHei&#39;;">每测试点时间</span><span style="font-family:&#39;Microsoft YaHei&#39;;">&lt;=2S</span> 
</p>
