# 

 
 # 题目描述 
<p>n&nbsp;个小伙伴（编号从&nbsp;0&nbsp;到&nbsp;n-1）围坐一圈玩游戏。按照顺时针方向给&nbsp;n&nbsp;个位置编号，从&nbsp;0&nbsp;到&nbsp;n-1。最初，第&nbsp;0&nbsp;号小伙伴在第&nbsp;0&nbsp;号位置，第&nbsp;1&nbsp;号小伙伴在第&nbsp;1&nbsp;号位置，&hellip;&hellip;，依此类推。<br />
游戏规则如下：每一轮第&nbsp;0&nbsp;号位置上的小伙伴顺时针走到第&nbsp;m&nbsp;号位置，第&nbsp;1&nbsp;号位置小伙伴走到第&nbsp;m+1&nbsp;号位置，&hellip;&hellip;，依此类推，第n&nbsp;&minus;&nbsp;m号位置上的小伙伴走到第&nbsp;0&nbsp;号位置，第&nbsp;n-m+1&nbsp;号位置上的小伙伴走到第&nbsp;1&nbsp;号位置，&hellip;&hellip;，第&nbsp;n-1&nbsp;号位置上的小伙伴顺时针走到第&nbsp;m-1&nbsp;号位置。<br />
&nbsp;现在，一共进行了&nbsp;10k&nbsp;轮，请问&nbsp;x&nbsp;号小伙伴最后走到了第几号位置。</p> 

 
 # 输入格式 
<p>输入共&nbsp;1&nbsp;行，包含&nbsp;4&nbsp;个整数&nbsp;n、m、k、x，每两个整数之间用一个空格隔开。</p> 

 
 # 输出格式 
<p>输出共&nbsp;1&nbsp;行，包含&nbsp;1&nbsp;个整数，表示&nbsp;10^k&nbsp;轮后&nbsp;x&nbsp;号小伙伴所在的位置编号。</p> 

 
 # 提示 
<p>对于&nbsp;30%的数据，0&nbsp;&lt;&nbsp;k&nbsp;&lt;&nbsp;7；<br />
对于&nbsp;80%的数据，0&nbsp;&lt;&nbsp;k&nbsp;&lt;&nbsp;10<sup>7</sup>；<br />
对于&nbsp;100%的数据，1&nbsp;&lt;&nbsp;n&nbsp;&lt;&nbsp;1,000,000，0&nbsp;&lt;&nbsp;m&nbsp;&lt;&nbsp;n，1&nbsp;&le;&nbsp;x&nbsp;&le;&nbsp;n，0&nbsp;&lt;&nbsp;k&nbsp;&lt;&nbsp;10<sup>9</sup>。</p> 
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
<tr><td>10 3 4 5 </td><td>5</td></tr></table>
