# 

 
 # 题目描述 
<p>
循环整数(circulate.pas/c/cpp)<br><br>【问题描述】<br><br>　　moreD在学习完循环小数之后发现循环是个很美好的性质。自己只需要记住短短的循环节以及循环次数(次数大于1，且是整数)就可以记住整个数字了。<br>　　因为背诵数字变得方便了，moreD决定背诵[L,R]内的所有循环的整数。moreD的背诵计划有T天，但是他不知道每天具体要背多少个数，请你帮助moreD计算出每天需要背诵的数字个数。<br>　　如果moreD在某天遇到一个曾经背过的数字，他会义无反顾地重新背诵。<br></p> 

 
 # 输入格式 
<p>
第一行给出一个整数T，表示moreD计划背诵T天的数字。<br>    接下来n行,第i行给出2个整数Li,Ri,表示moreD第i天的背诵计划。 <br></p> 

 
 # 输出格式 
<p>
输出T行，每行一个整数，表示第i天moreD需要背诵的数字个数。<br></p> 

 
 # 提示 
<p>
【数据范围】<br>对于30%的数据 T*MAX{Ri}≤2*10^6<br>对于70%的数据MAX{Ri}≤2*10^6<br>对于100%的数据 T≤50000,1≤Li≤Ri≤2*10^18<br><br>【样例解释】<br>对于第2天，moreD只需要背诵55555，66666.<br>对于第3天，moreD只需要背诵11，22，33，44，55，66，77，88，99.</p> 
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
1 10000
55555 66666
10 100
</td><td>108
2
9</td></tr></table>
