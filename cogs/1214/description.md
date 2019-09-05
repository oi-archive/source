# 题目描述


<span style="font-family:Microsoft YaHei;font-size:16px;">TYVJ八月月赛提高组第1题<br/>
<br/>
测试点数目：5<br/>
测试点分值：20<br/>
--内存限制：128M<br/>
--时间限制：1s</span> 
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【题目描述】</span> 
</h3>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">定义如下括号匹配序列：<br/>
        1．空序列是匹配序列；<br/>
        2．如果S是匹配序列，那么(S),[S],{S}和也是匹配序列；<br/>
        3．如果A和B都是匹配序列，那么AB也是匹配序列。<br/>
    例如，下面的字符串都是匹配序列：<br/>
        ()，[]，(())，([])，()[]，()[()]，{{}}&lt;&gt;，([]&lt;&gt;{{}})，&lt;&lt;{}&gt;&gt;<br/>
    而以下几个则不是：<br/>
        (，[，]，)(，())，([()，&lt;&lt;，{(})，&lt;{}&gt;)<br/>
    序列中可能包含通配符，含义如下：<br/>
        <b>/</b>表示任意1个左括号<br/>
        <b>#</b>表示任意2个左括号<br/>
        <b>@</b>表示任意4个左括号<br/>
        <b>?</b>表示任意8个左括号<br/>
        <b>\</b>表示任意1个右括号<br/>
        <b>*</b>表示任意2个右括号<br/>
        <b>&amp;</b>表示任意4个右括号<br/>
        <b>!</b>表示任意8个右括号<br/>
    现在，给你一些由&#34;(&#34;、&#34;)&#34;、&#34;[&#34;、&#34;]&#34;、&#34;{&#34;、&#34;}&#34;、&#34;&lt;&#34;、&#34;&gt;&#34;和通配符构成的序列，你要做的，是判断该序列是否为匹配序列。</span> 
</p>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【输入格式】</span> 
</h3>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">第一行：一个正整数N，表示测试数据组数； <br/>
接下来N行：每行一个括号序列(长度不超过L)。<span></span></span> 
</p>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【输出格式】</span> 
</h3>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">共N行：对于每一个括号序列，判断其是否匹配。<br/>
对于不匹配的序列，直接输出<b>FALSE</b>。<br/>
对于匹配的序列，输出用单一空格隔开的3个信息：<br/>
    第一个信息为<b>TRUE</b><br/>
    第二个信息为括号的最大深度(层数)<br/>
    第三个信息为达到最大深度的次数<br/>
详见样例</span> 
</p>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【样例输入】</span> 
</h3>
<pre>3
{()}@&lt;&gt;{})))&gt;
([})
?\\\\\\\]
</pre>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【样例输出】</span> 
</h3>
<pre>TRUE 5 2
FALSE
TRUE 8 1
</pre>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【提示】</span> 
</h3>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">样例解释：<br/>
对于第一组数据，<b>@</b>相当于<b>&lt;(((</b>，是匹配的，括号的最大深度为5，该深度出现了2次。<br/>
对于第二组数据，<b>[</b>和<b>}</b>不匹配。<br/>
第三组数据想要说明的是，通配符间可以匹配。<br/>
<br/>
数据规模：<br/>
对于20%的数据，有N=1，0<l<=20<br>
对于60%的数据，有0<n<=5，0<l<=2e+3<br>
对于100%的数据，有0<n<=10，0<l<=2e+6<br>
对于40%的数据，序列中没有通配符<br/>
<br/>
<l<=20<br>
<n<=5，0<l<=2e+3<br>
<n<=10，0<l<=2e+6<br>
</n<=10，0<l<=2e+6<br>
</n<=5，0<l<=2e+3<br>
</l<=20<br>
</n<=10，0<l<=2e+6<br>
</n<=5，0<l<=2e+3<br>
</l<=20<br>
</span> 
</p>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【来源】</span> 
</h3>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">From tbcaaa8 <a target="_blank" href="http://www.tyvj.cn/Problem_Show.aspx?id=1590">http://www.tyvj.cn/Problem_Show.aspx?id=1590</a> </span> 
</p>
