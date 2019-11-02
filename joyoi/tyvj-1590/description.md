# 

 
 # 题目背景 
TYVJ八月月赛提高组第1题<BR><BR>测试点数目：5<BR>测试点分值：20<BR>--内存限制：128M<BR>--时间限制：1s<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;定义如下括号匹配序列：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1．空序列是匹配序列；<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2．如果S是匹配序列，那么(S),[S],{S}和&lt;S&gt;也是匹配序列；<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3．如果A和B都是匹配序列，那么AB也是匹配序列。<BR>&nbsp;&nbsp;&nbsp;&nbsp;例如，下面的字符串都是匹配序列：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;()，[]，(())，([])，()[]，()[()]，{{}}&lt;&gt;，([]&lt;&gt;{{}})，&lt;&lt;{}&gt;&gt;<BR>&nbsp;&nbsp;&nbsp;&nbsp;而以下几个则不是：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(，[，]，)(，())，([()，&lt;&lt;，{(})，&lt;{}&gt;)<BR>&nbsp;&nbsp;&nbsp;&nbsp;序列中可能包含通配符，含义如下：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<B>/</B>表示任意1个左括号<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<B>#</B>表示任意2个左括号<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<B>@</B>表示任意4个左括号<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<B>?</B>表示任意8个左括号<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<B>\</B>表示任意1个右括号<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<B>*</B>表示任意2个右括号<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<B>&</B>表示任意4个右括号<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<B>!</B>表示任意8个右括号<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在，给你一些由"("、")"、"["、"]"、"{"、"}"、"&lt;"、"&gt;"和通配符构成的序列，你要做的，是判断该序列是否为匹配序列。<BR> 

 
 # 输入格式 
第一行：一个正整数N，表示测试数据组数；&nbsp;<BR>接下来N行：每行一个括号序列(长度不超过L)。<BR> 

 
 # 输出格式 
共N行：对于每一个括号序列，判断其是否匹配。<BR>对于不匹配的序列，直接输出<B>FALSE</B>。<BR>对于匹配的序列，输出用单一空格隔开的3个信息：<BR>&nbsp;&nbsp;&nbsp;&nbsp;第一个信息为<B>TRUE</B><BR>&nbsp;&nbsp;&nbsp;&nbsp;第二个信息为括号的最大深度(层数)<BR>&nbsp;&nbsp;&nbsp;&nbsp;第三个信息为达到最大深度的次数<BR>详见样例<BR> 

 
 # 提示 
样例解释：<BR>对于第一组数据，<B>@</B>相当于<B>&lt;(((</B>，是匹配的，括号的最大深度为5，该深度出现了2次。<BR>对于第二组数据，<B>[</B>和<B>}</B>不匹配。<BR>第三组数据想要说明的是，通配符间可以匹配。<BR><BR>数据规模：<BR>对于20%的数据，有N=1，0&lt;L&lt;=20<BR>对于60%的数据，有0&lt;N&lt;=5，0&lt;L&lt;=2E+3<BR>对于100%的数据，有0&lt;N&lt;=10，0&lt;L&lt;=2E+6<BR>对于40%的数据，序列中没有通配符<BR>From&nbsp;tbcaaa8&nbsp;<BR> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>3
{()}@<>{})))>
([})
?\\\\\\\]</td><td>TRUE 5 2
FALSE
TRUE 8 1</td></tr></table>
