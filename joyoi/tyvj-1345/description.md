# 

 
 # 题目描述 
&nbsp;ICG模拟赛开始了！<BR>由FF博士带领的团队要开始准备ICG模拟赛了，但他们发现机房的电脑有很多漏洞。<BR>为了修补漏洞，只有下载各种补丁。&nbsp;但是由于这些漏洞太过久远，不一定能找到能够修复漏洞的补丁。<BR>以下有n个漏洞和m个补丁，用字符串表示。<BR>若其中一个漏洞被一个补丁包含或包含一个补丁则认为这是一个可以被修复的漏洞。<BR>(不区分大小写,一个补丁可以修复多个漏洞，一个漏洞只能被修复一次)<BR>&nbsp;&nbsp;输出能被修复的漏洞总数。<BR> 

 
 # 输入格式 
第一行，两个整数n,m；<BR>&nbsp;&nbsp;第2行到第N+1行,表示漏洞的名称；<BR>&nbsp;&nbsp;接下来M行表示能下载到的各个补丁的名称。<BR><BR> 

 
 # 输出格式 
1个整数，表示能被修复的漏洞总数。<BR> 

 
 # 提示 
漏洞是<BR>Abc<BR>DGFYJJa<BR>ICG2010<BR>补丁是：<BR>aBCd<BR>YHDajfje<BR>IcG<BR>其中1号漏洞Abc被aBCd包含，可修复。3号漏洞ICG2010包含IcG.所以有2个漏洞可以被修复。<BR>(可能会出现同名的补丁或漏洞。)<BR>数据范围：<BR>对于每个给出的漏洞和补丁，长度不超过256；<BR>对于100%的数据，m,n&lt;=100<BR> 
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
<tr><td>3 3
Abc
DGFYJJa
ICG2010
aBCd
YHDajfje
ICG

</td><td>2

</td></tr></table>
