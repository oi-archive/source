# 

 
 # 题目描述 
乐乐是一个聪明而又勤奋好学的孩子。他总喜欢探求事物的规律。一天，他突然对数的正整数次幂产生了兴趣。<BR>众所周知，2的正整数次幂最后一位数总是不断的在重复2，4，8，6，2，4，8，6……我们说2的正整数次幂最后一位的循环长度是4（实际上4的倍数都可以说是循环长度，但我们只考虑最小的循环长度）。类似的，其余的数字的正整数次幂最后一位数也有类似的循环现象：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;循环&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;循环长度<BR>2&nbsp;&nbsp;&nbsp;&nbsp;2、4、8、6&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4<BR>3&nbsp;&nbsp;&nbsp;&nbsp;3、9、7、1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4<BR>4&nbsp;&nbsp;&nbsp;&nbsp;4、6&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2<BR>5&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1<BR>6&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1<BR>7&nbsp;&nbsp;&nbsp;&nbsp;7、9、3、1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4<BR>8&nbsp;&nbsp;&nbsp;&nbsp;8、4、2、6&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4<BR>9&nbsp;&nbsp;&nbsp;&nbsp;9、1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2<BR>这时乐乐的问题就出来了：是不是只有最后一位才有这样的循环呢？对于一个整数n的正整数次幂来说，它的后k位是否会发生循环？如果循环的话，循环长度是多少呢？<BR>注意：<BR>1．&nbsp;&nbsp;如果n的某个正整数次幂的位数不足k，那么不足的高位看做是0。<BR>2．&nbsp;&nbsp;如果循环长度是L，那么说明对于任意的正整数a，n的a次幂和a&nbsp;+&nbsp;L次幂的最后k位都相同。<BR> 

 
 # 输入格式 
输入只有一行，包含两个整数n（1&nbsp;&lt;=&nbsp;n&nbsp;&lt;&nbsp;10^100）和k（1&nbsp;&lt;=&nbsp;k&nbsp;&lt;=&nbsp;100），n和k之间用一个空格隔开，表示要求n的正整数次幂的最后k位的循环长度。<BR><BR> 

 
 # 输出格式 
输出包括一行，这一行只包含一个整数，表示循环长度。如果循环不存在，输出-1。<BR><BR> 

 
 # 提示 
对于30%的数据，k&nbsp;&lt;=&nbsp;4；<BR>对于全部的数据，k&nbsp;&lt;=&nbsp;100。<BR>noip2005普及组第4题 
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
<tr><td>32 2
</td><td>4</td></tr></table>
