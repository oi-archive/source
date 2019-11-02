# 

 
 # 题目描述 
SHY是T国的公主，平时的一大爱好是作诗。不过这次赶潮流的SHY作了一首英文诗。<br>英文诗的长度为N，用一个仅含有26个小写拉丁字母的字符串表示。<br>SHY把这首诗拿给LYD欣赏，LYD突发奇想，想从这首诗中找出一段，使得这一段中出现最多的字母出现的次数与出现最少的字母出现的次数的差值最大。<br>现在请你求出这个最大差值吧。<br><br> 

 
 # 输入格式 
本题仅有一个测试点，该测试点中包含多组数据，以EOF结尾。<br>每组数据的第一行是一个整数N；<br>第二行是一个长度为N的字符串，字符串中只含有26个小写拉丁字母。<br><br> 

 
 # 输出格式 
对于每组数据，输出一个整数表示最大差值。<br><br> 

 
 # 提示 
样例说明<br>选取aaaba这一段，最大差值为3。<br><br>数据范围与约定<br>N≤1000000，保证字符串中至少出现两种字母。<br>要注意的是，”出现次数最少的字母“的出现次数不能为0，也就是在选取的那一段中它必须存在。<br><br> 
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
<tr><td>10
aabbaaabab

</td><td>3

</td></tr></table>
