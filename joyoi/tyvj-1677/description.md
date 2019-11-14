# 

 
 # 题目背景 
“哈，我想向这个世界告别，可惜还有很多东西放不下。”<BR>“明天我去学校找你。”<BR><BR>&nbsp;似乎发生了什么事情。忽然好累……<BR> 

 
 # 题目描述 
睡梦中……<BR>“喂，西部，”朦胧中一个小女孩的声音，“……”<BR>“这是哪里？”西部郁闷的从地板上坐起来。<BR>“火车站。”声音清晰一点了。<BR>“火车开往哪里？”虽然还不是很清醒，总能有些思路。<BR>“去你要去的地方。”小女孩边说边跑开了。“如果没有经过评测机许可你将无法离开。”<BR>我想我知道我要去哪里。<BR>“你不应该出现在这里，西部。”一个似乎很熟悉的声音。“你看看你审核的比赛。”<BR>我承认我很悲剧。<BR>“如果你不能让评测机一秒算完这些运算，那你就一直在这里直到过完神棍节吧！”<BR>“运算？那是什么？”西部有点郁闷。<BR>于是出现了这样一段文字.<BR>Input&nbsp;n;<BR>Input&nbsp;a[1..n];<BR>Input&nbsp;@<BR>Sum←0;<BR>For&nbsp;i←1..n&nbsp;do<BR>&nbsp;&nbsp;For&nbsp;j←1..n&nbsp;do&nbsp;sum←sum+(a[i]&nbsp;@&nbsp;a[j]);<BR>Output&nbsp;sum;<BR>//&nbsp;50&nbsp;000&lt;=n&lt;=1&nbsp;000&nbsp;000,1&lt;=a[i]&lt;=1&nbsp;000&nbsp;000,@∈{+,-,*,/,and,or,xor,&gt;,&gt;=,L}<BR>“评测机一秒钟算完？！除了用酷睿i7还有什么方法呢……”<BR><BR>西部现在大脑很乱，想不到什么好的代码了，那么，你能解决么？<BR><BR> 

 
 # 输入格式 
<BR>第一行是一个数n，表示数组a的长度；<BR>第二行到第n+1行是n个正整数a[1]，a[2]，……，a[n]；<BR>最后一行是一个运算符@，可以是+,-,*,/,and,or,xor,&gt;,&gt;=,L，这里a&nbsp;L&nbsp;b的值为&nbsp;|a-b|.<BR>a&nbsp;&gt;&nbsp;b的意思是如果a&gt;b成立则这个表达式为1否则为0<BR>a&nbsp;&gt;=&nbsp;b的意思是如果a&gt;=b成立则这个表达式为1否则为0<BR> 

 
 # 输出格式 
<BR>仅仅一行，为一个数sum，为伪代码运行之后的结果。<BR>这里sum输出的时候保留整数部分.<BR> 

 
 # 提示 
伪代码应该很好懂<BR>这里所有数据50000&lt;=n&lt;=1000&nbsp;000，每个测试点对应一个运算符号。<BR>对sum的范围不做任何提示，请自行判断.<BR><BR>来自西部314&nbsp;七号苦情赛 
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
2011
11
11
-
</td><td>0
</td></tr></table>
