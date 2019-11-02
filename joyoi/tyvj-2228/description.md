# 

 
 # 题目描述 
<p>
TBL试图用计算器求C(N,M)，可是失败了。还是你来帮他编写一个大数计算器吧。 因为答案可能很大<br>TBL看了会晕，所以如果答案超过12位，就以“XXX…XXXXXXXXX”的格式输出。 </p> 

 
 # 输入格式 
<p>
 两个非负整数N、M。</p> 

 
 # 输出格式 
<p>
一个整数表示C(N,M)。（可能包含“…”）</p> 

 
 # 提示 
<p>
输出样例1<br>252 <br>输出样例2<br>100...812497256</p> 
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
<tr><td>10%的分数，答案不超过int64。
30%的分数，N<=1,000。
50%的分数，N<=30,000。
100%的分数，N<=1,000,000，0<=M<=N。</td><td>输入样例1
10 5
输入样例2 
100 50
</td></tr></table>
