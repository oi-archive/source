# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;说起测试计算机的软件，排在第一位的就应当是SuperPi&nbsp;了。它不但能良好的体现机器的整体水平，而且还很小巧，更令人惊讶的是它是一款绿色软件！SuperPi&nbsp;的成绩是用毫秒计算的，如果时间越短说明成绩越好。大家都经常会把自己的SuperPi&nbsp;成绩发布到网上，以和别人比较，当然也是为了炫耀自己的机器。这样，有些网站就要对大家的成绩进行排序并输出，另外一些技术比较完善的网站就会提供成绩查询的功能。现在，你就要完成这样一个查询程序。<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在提供每个人的用户名、成绩，需要你将成绩排序并根据用户输入的排名输出对应的用户名和成绩。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行是一个正整数n，表示用户的个数。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来的n&nbsp;行每行有一个字符串和一个小数，第i&nbsp;行是编号为i-1&nbsp;的人的信息，中间用一个空格分隔，字符串代表用户名（只能由大、小写字母，数字和下划线组成），小数代表该人的成绩，每行的首尾不会有多余的空格。<BR>&nbsp;&nbsp;&nbsp;&nbsp;然后是一个正整数m，表示查询的次数。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来m&nbsp;行是每一次查询的信息，每行一个实数k。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;对应每一个数k，你都要输出用时为k&nbsp;的人的用户名及排名（一个正整数），中间用一个空格分隔，如果没有符合条件的人的话就输出”No&nbsp;Such&nbsp;User”（没有两边的引号）。<BR> 

 
 # 提示 
【数据范围】<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于10%数据，n≤100，m≤100。<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于30%数据，n≤100000，m≤100。<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于100%数据，n≤100000，m≤1000。<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于100%数据，每个人的成绩各不相同且都小于10^9，有效位数最多为9&nbsp;位，小数点后最多三位；每个人的用户名都不相同；k&nbsp;的范围和每个人成绩的范围相同；每个人的用户名长度不超过10&nbsp;个字节。<BR>【说明】<BR>&nbsp;&nbsp;&nbsp;&nbsp;输入的成绩和查询的成绩只要值相同就算相等，如123.1&nbsp;与123.100&nbsp;是同一个数。<BR> 
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
<tr><td>5
sqybi 123.345
Core2_Duo 20.203
Vista123 100
o 100.001
0987654321 987654321
2
100.0
123.346
</td><td>Vista123 2
No Such User
</td></tr></table>
