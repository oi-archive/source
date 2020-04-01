# 

 
 # 题目描述 
<p>【问题描述】<br />
&nbsp;&nbsp;&nbsp;&nbsp;我们可以用这样的方式来表示一个十进制数：&nbsp;将每个阿拉伯数字乘以一个以该数字所处位置的(值减１)为指数，以10为底数的幂之和的形式。例如：123可表示为&nbsp;1*10^2+2*10^1+3*10^0这样的形式。<br />
&nbsp;&nbsp;&nbsp;&nbsp;与之相似的，对二进制数来说，也可表示成每个二进制数码乘以一个以该数字所处位置的（值－１）为指数，以２为底数的幂之和的形式。一般说来，任何一个正整数Ｒ或一个负整数－Ｒ都可以被选来作为一个数制系统的基数。如果是以Ｒ或－Ｒ为基数，则需要用到的数码为&nbsp;０，１，．．．．Ｒ－１。例如，当Ｒ＝７时，所需用到的数码是０，１，２，３，４，５和６，这与其是Ｒ或－Ｒ无关。如果作为基数的数绝对值超过１０，则为了表示这些数码，通常使用英文字母来表示那些大于９的数码。例如对１６进制数来说，用Ａ表示１０，用Ｂ表示１１，用Ｃ表示１２，用Ｄ表示１３，用Ｅ表示１４，用Ｆ表示１５。<br />
&nbsp;&nbsp;&nbsp;&nbsp;在负进制数中是用－Ｒ&nbsp;作为基数，例如-15(十进制)相当于１１０００１（－２进制），并且它可以被表示为２的幂级数的和数：<br />
<img alt="" src="data:image/png;base64,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" style="width: 645px; height: 51px;" /><br />
<br />
【问题求解】<br />
&nbsp;&nbsp;&nbsp;&nbsp;设计一个程序，读入一个十进制数和一个负进制数的基数,&nbsp;并将此十进制数转换为此负进制下的数：－Ｒ&isin;｛－２，－３，－４，．．．，－２０｝　<br />
&nbsp;</p> 

 
 # 输入格式 
<p>【输入格式】<br />
&nbsp;&nbsp;&nbsp;&nbsp;输入有两个输入数据。<br />
&nbsp;&nbsp;&nbsp;&nbsp;第一个是十进制数Ｎ（－maxlongint&lt;=N&lt;=maxlongint）；&nbsp;&nbsp;第二个是负进制数的基数－Ｒ。</p> 

 
 # 输出格式 
<p>【输出格式】<br />
&nbsp;&nbsp;&nbsp;&nbsp;应输出此负进制数及其基数，若此基数超过１０，则参照１６进制的方式处理。</p> 
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
<tr><td>【输入样例】下面是4个样例
30000 -2
-20000 -2
28800 -16
-25000 -16
</td><td>【输出样例】
30000=11011010101110000(base-2)
-20000=1111011000100000(base-2)
28800=19180(base-16)
-25000=7FB8(base-16)

</td></tr></table>
