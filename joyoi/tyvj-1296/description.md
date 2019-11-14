# 

 
 # 题目描述 
来自M星的小B新学了地球上的阿拉伯数字，虽然他不知道这些拐来拐去的字符是什么意思。但是为了显摆他的才华，他用这些阿拉伯数字随便写了一段话，并称他写的是一篇日志。当小B的朋友要求小B将那个日志给他看的时候，小B拒绝了（乱写的要是被看出了破绽,面子怎么挂得住啊...)并且小B给他的"阿拉伯日志"用新学的异或方法写了个加密程序。<BR>&nbsp;&nbsp;加密的方式为：按位对每位阿拉伯数字与一个密码进行异或操作，并且一篇文章的所有密码均是一样的。<BR>&nbsp;&nbsp;由于小B的朋友也了解这种异或的方法，但是他不会编程，所以他以惊天的龟速好不容易破译了小B的原文。刚打印出来准备看的时候，小B一杯咖啡就泼了过来...于是译文变成了残文...只剩下了第一个字符没有被抹掉.<BR>&nbsp;&nbsp;由于好奇心的驱使,小B的朋友急切想看到小B的日志(老想着看别人日志是不好的....),所以他找到了你,希望你能够写一个程序来破译小B的"日志"。<BR><BR> 

 
 # 输入格式 
第一行为字符串s，s是小B加密后得到的一串字符串。<BR>&nbsp;&nbsp;第二行为一个字符c，c就是留下的"残文"<BR><BR><BR> 

 
 # 输出格式 
&nbsp;&nbsp;只有一行，为小B的"阿拉伯日志"<BR>&nbsp;&nbsp;&nbsp;<BR>【注意】<BR>&nbsp;&nbsp;如果存在一个数i和一个密码j,&nbsp;使得i&nbsp;xor&nbsp;j&gt;=10，那么请将其写成(i&nbsp;xor&nbsp;j)mod&nbsp;10,也就是说原文和译文的长度是相同的。<BR><BR><BR> 

 
 # 提示 
【数据范围】<BR>&nbsp;&nbsp;&nbsp;s的长度&lt;=10^5<BR><BR><BR>【样例解释】<BR>因为1&nbsp;xor&nbsp;4=5，所以整串字符串的密码为5，于是则有：<BR>&nbsp;s1&nbsp;xor&nbsp;5=4.<BR>&nbsp;2&nbsp;xor&nbsp;5=7.<BR>&nbsp;3&nbsp;xor&nbsp;5=6<BR>原文便是476<BR><BR><BR> 
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
<tr><td>123
4


</td><td>476

</td></tr></table>
