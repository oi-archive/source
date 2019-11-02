# 

 
 # 题目背景 
<h2>版权</h2>

<p style="line-height: 20.8px;">GZEZ拥有本资料的所有版权！</p> 

 
 # 题目描述 
<p>伟哥结束了他的澳门之旅，由于他人品太好，在本地的赌场赢了很多很多的钱，因此，我们在此定义一种货币单位来衡量伟哥所持有的钱：亿元。现在伟哥要带这些钱回家，由于伟哥的钱来路不明，银行拒绝为他提供储存服务，于是，伟哥决定把用各种方式钱运回大陆并在家里慢慢花，在从澳门到广州之间有m个中转站（广州是m，澳门是1），伟哥联络了n家运输公司，由于伟哥喜欢用硬币，所以每个公司只能把z亿元从x中转站运送到y中转站。于是，他请你帮他算算他最多可以运多少亿元回家，并告诉你：把剩下的钱的90%给运输公司，其他的都归你了！运输公司和你决定串通在一起，他们把运输量缩小，那么你好我好大家好。</p> 

 
 # 输入格式 
<p>第一行n,m,&nbsp;money三个整数，分别指运输公司个数，中转站个数（含澳门广州），伟哥所持有的钱（按亿元算）；</p>

<p>接下来n行每行x,y,z三个整数，指第i个公司能把z亿元从x中转站运送到y中转站</p> 

 
 # 输出格式 
<p>求伟哥在广州可以用的钱，还有你自己可以得到的钱（直接去掉小数位）；（由于你和运输公司的串通，伟哥是不可能把所有钱运回家的）。</p> 

 
 # 提示 
<h2>数据范围</h2>

<p>对于100%数据，&nbsp;0&le;N&le;200，2<span style="line-height: 20.8px;">&le;</span>m<span style="line-height: 20.8px;">&le;</span>200，1<span style="line-height: 20.8px;">&le;</span>x,y<span style="line-height: 20.8px;">&le;</span>m，0<span style="line-height: 20.8px;">&le;</span>z<span style="line-height: 20.8px;">&le;</span>10000000</p>

<p><span style="color: rgb(255, 255, 255);">请注意数据范围！</span></p> 
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
<tr><td>5 4 60
1 2 40
1 4 20
2 4 20
2 3 30
3 4 10
</td><td>50 1</td></tr></table>
