# 

 
 # 题目描述 
编写一个简易机器语言解释器。<BR>st表示栈，st(0)表示栈底，st(p)表示栈顶,p初始值为0。栈中每个储存空间为1字节，所有数值无符号。<BR><BR>提示：本题陷阱很多，一定要小心，否则会死的很惨。<BR><BR>机器码含义如下：<BR><BR>00：加法<BR>p=p-1<BR>st(p-1)=st(p-1)+s(p)<BR><BR>01：减法<BR>p=p-1<BR>st(p-1)=st(p-1)-s(p)<BR><BR>02：乘法<BR>p=p-1<BR>st(p-1)=st(p-1)*s(p)<BR><BR>03：除法<BR>p=p-1<BR>st(p-1)=st(p-1)/s(p)<BR><BR>04：乘方<BR>p=p-1<BR>st(p-1)=st(p-1)^s(p)<BR><BR>05:阶乘<BR>st(p)=st(p)!<BR><BR>06??:栈底赋值<BR>st(0)=??<BR><BR>07??:入栈<BR>st(p)=??<BR>p=p+1<BR><BR>08:出栈<BR>p=p-1<BR><BR>09:退出程序<BR> 

 
 # 输入格式 
第一行：栈的大小m(字节)<BR>第二行：指令长度n(字节)<BR>第三行：指令(可能有无意义指令，忽略即可)<BR> 

 
 # 输出格式 
若程序能正常执行，输出两行：<BR>第一行为退出方式(遇到"09"指令退出为1；所有代码执行完毕，但无退出指令为0)<BR>第二行为st(0)的值<BR><BR>否则，输出一行：<BR>程序出错前已执行的指令条数（不包括出错指令）。 

 
 # 提示 
数据范围：<BR>100%:m&lt;50,n&lt;50;<BR><BR><BR> 
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
<tr><td>[示例一]
10
11
070k1070200

[示例二]
3
16
0700070007000700
</td><td>[示例一]
0
3

[示例二]
3
</td></tr></table>
