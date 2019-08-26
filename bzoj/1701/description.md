
# Description

<div class="content"><p><span style="font-size: medium">Bessy 正在上学并且分数还不错. 她考了N (一个数据中1 &lt;= N &lt;= 50,000, 其余数据 1 &lt;= N &lt;= 50,00) 次试,每次考试得分为T_i, 满分为P_i(0 &lt;= T_i &lt;= P_i &lt; 40,000; 0 &lt; P_i). 在计算总分时,她的老师先将把分数(P_i/T_i)最高的D个试卷去掉,然后将其余P_i 的和除以其余T_i的和作为Bessy的分数. Bessy精通数学,所以很快发觉这并没有想象中那么好. Bessy想告诉她的老师所有附和以下条件的D: 如果令一组(D个)分数去掉,她的分数回比老师算出来的更高. Bessy 很惊讶地发现她没有两次考试得分百分点是一样的. </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">*第一行: N </span></p>
<p><span style="font-size: medium">*第2..N+1行: 第i行里有 T_i 和 P_i.</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第一行: K, 符合条件的D的个数. </span></p>
<p><span style="font-size: medium">*第2..K+1行: 按递增顺序,每行一个符合条件的D. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2<br/>
5 9<br/>
3 8<br/>
4 10<br/>
1 3<br/>
<br/>
输入解释:<br/>
<br/>
Bessy 考了5门试, 分数分别为1/2, 5/9, 3/8, 4/10, 1/3.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1<br/>
2<br/>
<br/>
输出解释:<br/>
<br/>
当D=1时, 去掉1/3将使总分变成13/29, 而去掉3/8则得到11/24.<br/>
<br/>
当D=2时, 去掉1/3和3/8得到总分10/21. 更高的7/14则能由去掉3/8和4/10<br/>
得到.<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

