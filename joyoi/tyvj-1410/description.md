# 

 
 # 题目背景 
Tyvj最近全面招聘管理员，Admin神牛zhq同志面对着CoderSpace中漫长的等待和一堆堆没用的回复---于是就开始对着电脑屏幕上的一行字不停滴点击。。。<BR>接下来我们每隔两天都会有一个类似的故事(一道题)，它就从这里开始了。。。 

 
 # 题目描述 
把一串无限长的字符编号为1,2,3,4,5......每一个字符都有两种可能的状态，被选中或者不被选中。初始状态下，所有的字符都是不被选中的。每按一下字符，字符的状态就会改变。<BR>Admin每次做如下的操作：指定两个数a,t（a为实数，t为正整数）。它会将编号为&nbsp;{其中【k】为实数k的整数部分(取整)}【1*a】、【2*a】、、、、【t*a】的字符各点一次。<BR>他进行了n次操作后，他保证一定只有一个字符是选中的。请帮忙计算它的编号。 

 
 # 输入格式 
第一行一个数n<BR>接下来n行每行两个数ai和ti，其中ai是实数小数点后一定有6位。ti为正整数。 

 
 # 输出格式 
被选中的字符的编号。 

 
 # 提示 
对于100%的数据满足&nbsp;n&lt;=5000,&nbsp;1&lt;=ai&lt;100000,1&lt;=ti&lt;=100000，并保证a*t不超过maxlongint，n*t的值不超过2000万。<BR><BR>提示：题目实际上非常之简单，标程仅十来行，不要想复杂By&nbsp;Lydliyudong 
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
1.618034 13
2.618034 7
1.000000 21</td><td>20</td></tr></table>
