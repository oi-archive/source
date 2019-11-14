# 

 
 # 题目描述 
<p>总公司拥有高效生产设备M台，准备分给下属的N个公司。各分公司若获得这些设备，可以为国家提供一定的盈利。问：如何分配这M台设备才能使国家得到的盈利最大？求出最大盈利值。其中M&lt;=100，N&lt;=100。分配原则：每个公司有权获得任意数目的设备，但总台数不得超过总设备数M。保存数据的文件名从键盘输入。</p> 

 
 # 输入格式 
<p>第一行保存两个数，第一个数是公司数N，第二个数是设备数M。接下来是一个N*M的矩阵，表明了第I个公司分配J台机器的盈利。</p> 

 
 # 输出格式 
<p>输出所有公司的最大利润和</p> 

 
 # 提示 
<p>最大利润是所有公司都分得一个机器所得到。<br />
公司可以不分机器<br />
保证所有的价值都是正整数，但value[i,1..m]并不是单调的</p> 
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
30 40 50
20 30 50
20 25 30</td><td>70</td></tr></table>
