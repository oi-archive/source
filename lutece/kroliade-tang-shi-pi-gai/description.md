
# Content

Krolia的老师让每个人默写指定的一首唐诗。Krolia第一个完成默写，坐在那里无所事事。于是老师让Krolia来负责批改其他同学交上来的唐诗。批改的规则如下：
1. 该诗由四句诗组成(每句的字数随意)，每句诗由若干单词组成。单词的顺序不能改变，但是诗句的顺序可以任意改变。
2. 单词用英文大小写字母来表示，单词间必须有`-`，`_`，`.`和空格这些字符来表示分割。分割符可以出现在每个单词的两侧，可以出现在诗句的开头，但不能出现在句末符的后面。句末会有`?`，`.`，`,`，`;`来表示句子的结束(这些字符除了`.`只能出现在句末)。单词中不能有其他的符号。分隔符在单词间出现一个或者多个，句末符可以在句末省略或者出现任意个。
3. 字母的大小写不影响正确与否。

# Standard Input

第一行一个整数$T$($1\leq T\leq 100$)，表示有$T$组测试数据。每组测试数据的前四行表示唐诗的四句诗。保证该四句诗是合法的。接下来的一行一个整数$n$($1\leq n\leq 5$)，表示有多少份待批改唐诗默写。每份待批改的唐诗默写由$4$行组成。输入数据只由分割符，句末符，大小写字母还有换行符组成。每行至多有$150$个字符。

# Standard Output

对于每一行，输出一个字符串：`YES`或者`NO`，表示该同学默写对错与否。

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>1
Wei_Cheng_Zhao_Yu_Yi_Qing_Chen,
Ke_She_Qing_Qing_Liu_She_Xin.
Quan_Jun_Geng_Jin_Yi_Bei_Jiu,
Xi_Chu_Yang_Guan_Wu_Gu_Ren.
3
_Quan.Jun Geng Jin Yi Bei-Jiu_
.Wei.Cheng Zhao Yu_Yi Qing.Chen.
Ke.She Qing.Qing_Liu She-Xin.
xi_chu_yang_guan_wu_gu_ren.
xxxxxxxxx?????????
Ke_She_Qing_xxxxxxxxxxx??????????
Quan_Jun_XXXXXXXXXXXXXXX..........
Xi_Chu_XXXXXXXXXXX,,,,,,,,,,,,
YueHangJun.
ShenXiongGui.
ChaoNiuBi.
BuJieShi.</td><td>YES
NO
NO</td></tr></table>


# Constraints



# Note



# Source


